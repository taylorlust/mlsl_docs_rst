.. MLSL documentation master file, created by
   sphinx-quickstart on Tue May 28 16:38:58 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to MLSL's documentation!
================================
   
Intel® Machine Learning Scaling Library is a library providing an efficient implementation of
communication patterns used in deep learning. Some of the library features include

- Built on top of MPI, allows for use of other communication libraries
- Optimized to drive scalability of communication patterns
- Works on various interconnects Intel® Omni-Path Architecture, InfiniBand, and Ethernet
- Common API to support Deep Learning frameworks (Caffe, Theano, Torch, etc.)

The Intel® MLSL package comprises the Intel MLSL Software Development Kit (SDK) and the Intel® MPI
Library Runtime components.
This document provides usage instructions for Intel MLSL, and its configuration reference. For
installation instructions, system requirements, and other information, refer to the README file supplied
with the library.

Contents:
*************

.. toctree::
   :glob:
   :maxdepth: 2
   
   usage.rst
   var.rst