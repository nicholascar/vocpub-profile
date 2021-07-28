# VocPub Profile
## How to validate

This document describes how you can use the validator in the [VocPub Profile](https://w3id.org/profile/vocpub) to test whether data is valid according to it.

Validation using VocPub's validator involves applying the [SHACL](https://www.w3.org/TR/shacl/) validator file, [provided in this profile](https://w3id.org/profile/vocpub/validator) to data using one of many available validator tools. Different approaches and tools are:

1. **Online validation**
    * [SHACL Playground](https://shacl.org/playground/)
        * Simple go to the web page, copy the validator file's contents into the _Shapes Graph_ text box and your target data into the _Data Graph_ text box and hit the "Update" button! The tool will present any errors found to you on screen.
2. **Command line validation**
    * [pySHACL](https://github.com/RDFLib/pySHACL)
        * This is a Python tool that can run as a desktop command line application - see it's docs
3. **Integrationed application validation**
    * use pySHACL above within your own Python scripts or programs. See pySHACL's documentation