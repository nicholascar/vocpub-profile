# VocPub Profile
## How to validate

This document describes how you can use validators, such as the [VocPub Profile](https://w3id.org/profile/vocpub)'s validator, to test whether data is valid according to it a specification.

Validation using SHACL validators involves applying a [SHACL](https://www.w3.org/TR/shacl/) validator file, such as [the one provided in this profile](https://w3id.org/profile/vocpub/validator) to data using one of many available validator tools. Different approaches and tools are:

1. **Online validation**
    * [SHACL Playground](https://shacl.org/playground/)
        * Simple go to the web page, copy the validator file's contents into the _Shapes Graph_ text box and your target data into the _Data Graph_ text box and hit the "Update" button! The tool will present any errors found to you on screen.
2. **Command line validation**
    * [pySHACL](https://github.com/RDFLib/pySHACL)
        * This is a Python tool that can run as a desktop command line application - see it's docs
3. **Integrationed application validation**
    * use pySHACL above within your own Python scripts or programs. See pySHACL's documentation

Some tools also provide "single click" validation for data as they have validators, such as this VocPub one, pre-loaded:

4. **SURROUND's RDFTools Online Validator**
    * http://rdftools.surroundaustralia.com/validate
        * Add your data to the "Input Document" window, or upload a file
        * Select the VocPub, or other, validator from the list and validate
        * You will get a human-readable as well as a machine-readable result

This validator is also included automatically in some systems, such as the [Biodiversity Data Repository](https://bdr.gov.au)'s [Gateway](https://gateway.bdr.gov.au).
