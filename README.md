# Delta Reporter PHPUnit Tests

These tests are intended as a example to use Delta Reporter's PHPUnit client, which is cloned as a submodule to apply changes to it and test them right away.

To clone this repo along with the submodule use:

```
git clone --recurse-submodules https://github.com/delta-reporter/delta-reporter-phpunit-tests.git
```

Then install the required packages with

```
./composer.phar install
```

Finally run this test with:

```
./vendor/bin/phpunit
```

By default, the client is pointing to an instance of Delta Reporter on `http://localhost:5001`

To change it modify `phpunit.xml` accordingly
