[![Build Status](https://travis-ci.org/lasote/conan-openssl.svg?branch=master)](https://travis-ci.org/lasote/conan-openssl)

[![Join the chat at https://gitter.im/lasote/conan-openssl](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/lasote/conan-openssl?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# conan-openssl

[Conan.io](https://conan.io) package for OpenSSL library

<<<<<<< HEAD
The packages generated with this **conanfile** can be found in [conan.io](https://conan.io/source/OpenSSL/1.0.2k/lasote/stable1.2.8/lasote/stable).
=======
The packages generated with this **conanfile** can be found in [conan.io](https://conan.io/source/OpenSSL/1.0.2j/lasote/stable1.2.8/lasote/stable).
>>>>>>> release/1.0.2j

## Build packages

Download conan client from [Conan.io](https://conan.io) and run:

    $ python build.py
    
## Upload packages to server

<<<<<<< HEAD
    $ conan upload OpenSSL/1.0.2k@lasote/stable --all
=======
    $ conan upload OpenSSL/1.0.2j@lasote/stable --all
>>>>>>> release/1.0.2j
    
## Reuse the packages

### Basic setup

<<<<<<< HEAD
    $ conan install OpenSSL/1.0.2k@lasote/stable
=======
    $ conan install OpenSSL/1.0.2j@lasote/stable
>>>>>>> release/1.0.2j
    
### Project setup

If you handle multiple dependencies in your project is better to add a *conanfile.txt*
    
    [requires]
<<<<<<< HEAD
    OpenSSL/1.0.2k@lasote/stable
=======
    OpenSSL/1.0.2j@lasote/stable
>>>>>>> release/1.0.2j

    [options]
    OpenSSL:shared=true # false
    # Take a look for all available options in conanfile.py
    
    [generators]
    txt
    cmake

Complete the installation of requirements for your project running:</small></span>

    conan install .

Project setup installs the library (and all his dependencies) and generates the files *conanbuildinfo.txt* and *conanbuildinfo.cmake* with all the paths and variables that you need to link with your dependencies.
