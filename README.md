# EPFL-Network-Tour

Introduction
============

We plan to explore manifold learning as presented in [@isomap] for a
lower dimensional embedding of images. Since lower dimensional hidden
representations allow for generative modeling, we also plan to explore
image generation by sampling from this lower dimensional manifold.

Data Acquisition and Exploration
================================

We plan to go ahead with Celebface Attribute Dataset. For computational purposes, we randomly choose roughly 6000 images from a total set of more 200k images. To reduce the complexity, we convert all the images to grayscale.

Data Exploitation
=================

We will begin with choosing an appropriate dataset from a plethora that
is already available. We will then detect keypoints followed by
generating descriptors around those keypoints using a suitable
algorithm. Once we obtain the feature vector representation for each
image, we will try to learn a parametrized manifold space. This
parametrization would not only help us in generating new faces along
that manifold, but a suitable choice of parameter may help us in
morphing specific features of individual faces.

Conclusion : Final Goal
=======================

We were able to successfully generate the following videos :
[Exhibit A](https://drive.google.com/file/d/175sQA20qGtDfx_1nsfYilVQM5wnDLPZp/view)
[Exhibit B](https://drive.google.com/file/d/1sKCcoBNzzLRFz2pQZzzcJedq4mFZXdLm/view)
[Exhibit C](https://drive.google.com/file/d/1GtPAX8_7TZjPob0pgFtbsjdtgGbvNI0T/view)

