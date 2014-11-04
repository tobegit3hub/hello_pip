
# Hello Pip

## Introduction

It's the pip library to say hello.

You can learn how to distribute your Python libraries from [hello_pip](https://pypi.python.org/pypi/hello_pip).

## Usage

* `pip install hello_pip` or `python setup.py install`
* `import hello.hello`
* `hello.hello.hello_pip()`
* Then it will output "Hello pip".

## How It works

* Write the setup file like [setup.py](https://github.com/tobegit3hub/hello_pip/blob/master/setup.py).
* Registry an account in <https://pypi.python.org/pypi>.
* Run `python setup.py register`
* Then run `python setup.py sdist upload`

## Reference

* [Writing the Setup Script](https://docs.python.org/2/distutils/setupscript.html)
* [Getting Started With setuptools and setup.py](https://pythonhosted.org/an_example_pypi_project/setuptools.html)
* [Adding a Package to PyPi For the 1st Time](http://jamie.curle.io/blog/my-first-experience-adding-package-pypi/)

