# OSCON 2016


## Cool stuff to checkout

* Golang
    * Cobra
    * Viper
    * Unikernels
* Python
    * Pytest: Compatible with unittest. More pythonic than unittest.
    * Doctest: Documentation as tests. Add your API example to the top of your module and will run it to see if your API actually does do the things you document.
* Tensorflow
* Bazel
* Swagger: API Design. 
    * "If you don't use this what are you doing?!?" Angel from IBM
* Rexray: vendor agnostic storage orchestration engine.
* JSON Query tool: https://stedolan.github.io/jq/
* Github Torrent - Github Analytics on the public github data http://ghtorrent.org/

## Python

``python -m compileall <directory>``

``python -m unittest discover <directory>``

## Git

``git log --graph --oneline``


## Unikernel

Single user, single process OS. Massive performance improvements. Modern OSes take a 30-40% performance hit on context switching and isolation of process address spaces.

Cross-compile existing applications into a lightweight VM.

Pull only the stuff you need into a single executable. Stops vulnerabilities due to a huge stack that comes with the existing OS infrastructure (OpenSSL, etc).

Single address space single process.

Unikernels are NOT new.
