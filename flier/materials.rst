.. -*- mode: rst; fill-column: 78; indent-tabs-mode: nil -*-
.. vi: set ft=rst sts=4 ts=4 sw=4 et tw=79:

Python in NeuroImaging
======================

Please provide for every sub-project a brief Description, list of
Features, some nice figure if you have any.  Hopefully eventually we
get enough of tasty materials someone could compose into a flier.

Stimuli Delivery
----------------

PsychoPy
~~~~~~~~
http://www.psychopy.org


OpenSesame
~~~~~~~~~~
http://www.cogsci.nl/software/opensesame

...

Input/Output
------------

NiBabel
~~~~~~~
http://nipy.org/nibabel

.. figure:: ../pics/reggie.png
   :alt: nibabel
   :align: right
   :figwidth: 35%

Nibabel provides read and write access to some common medical and neuroimaging
file formats, including: ANALYZE_ (plain, SPM99, SPM2), GIFTI_, NIfTI1_, MINC_,
as well as PAR/REC. NiBabel is the successor of PyNIfTI_.

.. _ANALYZE: http://www.grahamwideman.com/gw/brain/analyze/formatdoc.htm
.. _NIfTI1: http://nifti.nimh.nih.gov/nifti-1/
.. _MINC: http://wiki.bic.mni.mcgill.ca/index.php/MINC
.. _PyNIfTI: http://niftilib.sourceforge.net/pynifti/
.. _GIFTI: http://www.nitrc.org/projects/gifti

The various image format classes give full or selective access to header (meta)
information and access to the image data is made available via NumPy arrays.

Analysis
--------

NiPy
~~~~
http://nipy.org/nipy

NIPY has algorithms for the analysis of neuroimaging data including:

* General linear model statistical analysis
* Combined slice time correction and motion correction
* General image registration routines with flexible cost functions, optimizers
  and resampling schemes
* Image segmentation
* Basic visualization of results in 2D and 3D
* Basic time series diagnostics
* Clustering and activation pattern analysis across subjects

NiPype
~~~~~~
http://nipy.org/nipype


DiPy
~~~~
http://nipy.org/dipy

.. figure:: ../pics/dipy-banner.png
   :alt: nibabel
   :align: right
   :figwidth: 35%

Dipy is an international, free and open soure software project for
diffusion magnetic resonance imaging analysis.

Dipy is multiplatform and will run under any standard operating system such as
*Windows*, *Linux*, *Mac OS X*.

Just some of our **state-of-the-art** applications are:

- Reconstruction algorithms e.g. GQI, DTI
- Tractography generation algorithms e.g. EuDX
- Intelligent downsampling of tracks
- Ultra fast tractography clustering
- Resampling datasets with anisotropic voxels to isotropic
- Visualizing multiple brains simultaneously
- Finding track correspondence between different brains
- Warping tractographies into another space e.g. MNI space
- Reading many different file formats e.g. Trackvis or Nifti
- Dealing with huge tractographies without memory restrictions
- Playing with datasets interactively without storing
- And much more and even more to come in next releases


NiTime
~~~~~~
http://nipy.org/nitime


PyMVPA
~~~~~~
http://www.pymvpa.org

.. figure:: ../pics/pymvpa_logo.pdf
   :alt: PyMVPA
   :align: right
   :figwidth: 35%

PyMVPA eases statistical learning analyses (or otherwise called
Multivariate pattern analysis, MVPA) of large datasets, with an accent
on neuroimaging.

Features:

 - Easy I/O to Neuroimaging data (via NiBabel)
 - Variety of machine learning methods (e.g. SVM, SMLR, kNN)
 - Uniform interfaces to other toolkits (e.g. MDP, Shogun, Scikit-learn)
 - Flexible Searchlight-ing
 - Uber-Fast GNB Searchlight-ing
 - Hyperalignment (Haxby et al 2011, Neuron)

.. figure:: ../pics/pymvpa_shot.pdf
   :alt: PyMVPA Analyses
   :align: right
   :figwidth: 100%


Visualization
-------------

PySurfer
~~~~~~~~
http://pysurfer.github.com



