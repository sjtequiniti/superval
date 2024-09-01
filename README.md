superval
========

Source code for SuperVal application, translated from SF source code files into UTF-8 encoding.

extension | content
----------|--------
afn       | APL function
csv       | nested table
mat       | char matrix
str       | char vector

The serialisation/deserialsation is not comprehensive (i.e. all possible data structures) and probably does not have to be.

To do
-----

- [ ] serialise whatever is held on non-package components
- [ ] serialise SF file directories as YAML, possibly also listing package contents
- [ ] default any data structures too complex to serialise to individual SF files

