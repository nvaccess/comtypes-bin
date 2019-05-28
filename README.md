# comtypes-bin
NVDA's comtypes-bin dependency

This repository fulfils NVDA's dependency on comtypes 1.1.7.
In the past, NVDA directly included https://github.com/enthought/comtypes as a submodule.
However, it was discovered that the syntax of comtypes' source tree is not compatible with Python 3, and that the Python 3 conversion of the comtypes code is performed at build time.
For every update of this dependency repository, it should be considered whether or not it is possible to switch back to upstream.

This repository was created with the following command: `pip3 install -t ./ comtypes==1.1.7`
