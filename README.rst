Fiducial Registration Educational Demonstration
===============================================

.. image:: https://github.com/UCL/scikit-surgeryfred/raw/master/project-icon.png
   :height: 128px
   :width: 128px
   :target: https://github.com/UCL/scikit-surgeryfred
   :alt: Logo

.. image:: https://github.com/UCL/scikit-surgeryfred/workflows/.github/workflows/ci.yml/badge.svg
   :target: https://github.com/UCL/scikit-surgeryfred/actions
   :alt: GitHub Actions CI status

.. image:: https://coveralls.io/repos/github/UCL/scikit-surgeryfred/badge.svg?branch=master&service=github
    :target: https://coveralls.io/github/UCL/scikit-surgeryfred?branch=master
    :alt: Test coverage

.. image:: https://readthedocs.org/projects/scikit-surgeryfred/badge/?version=latest
    :target: http://scikit-surgeryfred.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. image:: https://zenodo.org/badge/269602581.svg
    :target: https://zenodo.org/badge/latestdoi/269602581
    :alt: DOI - Zenodo


Author: Stephen Thompson

Fiducial Registration Educational Demonstration (SciKit-SurgeryFRED) is part of the `SciKit-Surgery`_ software project, developed at the `Wellcome EPSRC Centre for Interventional and Surgical Sciences`_, part of `University College London (UCL)`_.

Fiducial Registration Educational Demonstration is tested with Python 3.X

Fiducial Registration Educational Demonstration is intended to be used as part of an online tutorial in using fiducial based registration. The tutorial covers the basic theory of fiducial based registration, which is used widely in image guided interventions. The tutorial aims to help the students develop an intuitive understanding of key concepts in fiducial based registration, including Fiducial Localisation Error, Fiducial Registration Error, and Target Registration Error. 

::

    python sksurgeryfred.py

Please explore the project structure, and implement your own functionality.

Citing
------
If you use SciKit-SurgeryFRED in your research or teaching please cite it. Individual releases can be cited via the Zenodo tag. SciKit-Surgery should be cited as:

Thompson S, Dowrick T, Ahmad M, et al. "SciKit-Surgery: compact libraries for surgical navigation." International Journal of Computer Assisted Radiology and Surgery. 2020 May. DOI: 10.1007/s11548-020-02180-5.

Developing
----------

Cloning
^^^^^^^

You can clone the repository using the following command:

::

    git clone https://github.com/UCL/scikit-surgeryfred


Running tests
^^^^^^^^^^^^^
Pytest is used for running unit tests:
::

    pip install pytest
    python -m pytest


Linting
^^^^^^^

This code conforms to the PEP8 standard. Pylint can be used to analyse the code:

::

    pip install pylint
    pylint --rcfile=tests/pylintrc sksurgeryfred


Installing
----------

You can pip install directly from the repository as follows:

::

    pip install git+https://github.com/UCL/FiducialRegistrationEducationalDemonstration



Contributing
^^^^^^^^^^^^

Please see the `contributing guidelines`_.


Useful links
^^^^^^^^^^^^

* `Source code repository`_
* `Documentation`_


Licensing and copyright
-----------------------

Copyright 2020 University College London.
Fiducial Registration Educational Demonstration is released under the BSD-3 license. Please see the `license file`_ for details.


Acknowledgements
----------------

Supported by `Wellcome`_ and `EPSRC`_.


.. _`Wellcome EPSRC Centre for Interventional and Surgical Sciences`: http://www.ucl.ac.uk/weiss
.. _`source code repository`: https://github.com/UCL/scikit-surgeryfred
.. _`Documentation`: https://scikit-surgeryfred.readthedocs.io
.. _`SciKit-Surgery`: https://github.com/UCL/scikit-surgery/wiki
.. _`University College London (UCL)`: http://www.ucl.ac.uk/
.. _`Wellcome`: https://wellcome.ac.uk/
.. _`EPSRC`: https://www.epsrc.ac.uk/
.. _`contributing guidelines`: https://github.com/UCL/scikit-surgeryfred/blob/master/CONTRIBUTING.rst
.. _`license file`: https://github.com/UCL/scikit-surgeryfred/blob/master/LICENSE

