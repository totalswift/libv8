### Unreleased

* Fix architecture detection for armv7 #226

### v5.3.332.38.0, v5.3.332.38.1 - 2016-09-07

* Update upstream v8 version to 5.3.332.38

### 5.2.361.43.0, 5.2.361.43.1 - 2016-06-26:

* Compare compiler versions part by part as integers instead of using string
  comparison on the whole version string #154 (thanks @ltk)
* Update upstream v8 to version 5.2.361.43 and refresh the patch set

### 5.1.281.67.0, 5.1.281.67.1 - 2016-06-26:

* Update upstream v8 version to 5.1.281.67 to address #219

### 5.1.281.59.0, 5.1.281.59.1 - 2016-06-15:

* Update upstream v8 version to 5.1.281.59
* Make sure the patch set is applied in the correct order

### 5.0.71.48.4, 5.0.71.48.5 - 2016-05-13:

* Enable the -fPIC flag for ARM

### 5.0.71.48.2, 5.0.71.48.3 - 2016-05-13:

* Upgrade upstream v8 version to 5.0.71.45
* Remove all workarounds for building v8 3.16 with newer compilers

### 3.16.14.14, 3.16.14.15 - 2016-04-28:

* Enhance compiler version detection and architecture detection #212
* Introduce darwin13-15 binary building #211
* Disable errors on warning for OS X #210
* Improve --with-system-v8 error message #200
* Fix the check for git-svn #199
