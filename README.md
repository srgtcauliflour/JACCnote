# JACCnote (Just Another Crypto Currency)

## About

Welcome to the repository of JACCnote.

As the Name implies this is Just Another Crypto Currency or JACC for Short.

Forked from the Latest Cryptonote Repository and fiddled with by someone who knows JACC Sh!t about what he's doing.

This is a Take it or Leave it Cryptocurrency...No fancy Ribbons, just me spending way to much time Blazed off my Head and on my Computer...

Crazy Ideas are welcome... Like im fully OK with this thing turning into the Quasimodo of the Crypto World.... Help Me!

Anyway lets take it as it comes and hope for the best!

## Building JACCnote

### On *nix

Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/
* Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

**Advanced options:**

* Parallel build: run `make -j<number of threads>` instead of `make`.
* Debug build: run `make build-debug`.
* Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.
* Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.

### On Windows
Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55. You may download them from:

* http://www.microsoft.com/
* http://www.cmake.org/
* http://www.boost.org/

To build, change to a directory where this file is located, and run theas commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

And then do Build.
Good luck!
# JACCnote
