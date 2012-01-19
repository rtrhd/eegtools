Introduction
============

EEGtools is a set of Python libraries for EEG analysis. Most of the code was
developed as a part of the [PhD work](https://github.com/downloads/breuderink/phdthesis/reuderink2011rbc.zip) of [Boris
Reuderink](http://borisreuderink.nl) in the form of the library
"[Psychic](https://github.com/breuderink/psychic)". EEGtools is the successor of
Psychic, and does not attempt to provide a framework for analysis, but rathera
small set of well-tested functions for scientific EEG analysis.

Features
========
- Importing of BDF and EDF+ file formats
- Publication-ready visualisation of topographic activation (scalp plots)
- Spatial filters for oscillatory responses (common spatial patterns), EOG (eye
  movement) removal, whitening and the common average reference.
- PARAFAC tensor decomposition for summarization of tensors (higher order
  arrays).

Status
======
EEGtools is currently in the planning phase. Most code does already exist
in [Psychic](https://github.com/breuderink/psychic).