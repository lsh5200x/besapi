# Change Log
All notable changes to this project will be documented in this file.

### Changed

- Added support for Python3
  * Need to run this in a Python3 environment, python3 has replaced 
    the type unicode to use str. 
    ```
        elif (type(request.text) is unicode and
        elif (type(request.text) is str and
    ```
