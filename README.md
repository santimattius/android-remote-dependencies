[![codecov](https://codecov.io/gh/santimattius/android-architecture-guide/branch/master/graph/badge.svg?token=4KNEHBG5ZF)](https://codecov.io/gh/santimattius/android-architecture-guide)

# Android Remote Dependencies

Application using [Android Architecture Guide Template](https://github.com/santimattius/android-architecture-guide)

## Remote dependencies

This application implemente remote dependencies script defined in this github repository -> [here](https://github.com/santimattius/android-dependencies-group)

``` groovy

buildscript {

    //apply script from android-dependencies-group repository.
    apply from: "https://raw.githubusercontent.com/santimattius/android-dependencies-group/main/versions.gradle"

    ....
}

```
