### Project setup

If you handle multiple dependencies in your project is better to add a *conanfile.txt*

    [requires]
    TBB/2019_U4@conan/stable

    [generators]
    txt

Complete the installation of requirements for your project running:

    $ mkdir build && cd build && conan install ..

### Available Options
| Option        | Default | Possible Values  |
| ------------- |:----------------- |:------------:|
| shared      | False |  [True, False] |
| tbbmalloc      | False |  [True, False] |
| tbbproxy      | False |  [True, False] |
