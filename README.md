# Image Analysis with Deep Learning

[Taylor Arnold](https://statsmaths.github.io), Assistant Professor of Statistics, [@statsmaths](https://twitter.com/statsmaths)

[Lauren Tilton](https://laurentilton.com), Assistant Professor of Digital Humanities, [@nolauren](https://twitter.com/nolauren)

This repository contains notes, code, and data for our HILT 2019 workshop,
which runs from 3-7 June on the campus of IUPUI in Indianapolis, IN. Feel
free to use/share/adopt these notes for other courses.

## Description

Image Analysis with Deep Learning will examine methods for image analysis
at scale. Tasks covered include color analysis, object detection, facial
recognition, image similarity, and image clustering. The course will work
a variety of visual culture including art, photography, and moving images
to ask:

- How can we identify similar works of art using image analysis?
- How can we identify objects in 100,000 photographs?
- How can we track character’s movements in a sit-com?
- How has color in film changed over time?

While the course will introduce several out-of-the-box tools, the main
focus will be on deep learning techniques with Python. No prior programming
experience is required.

## Code of Conduct

Our workshop is dedicated to providing a harassment-free experience
for everyone. We do not tolerate harassment of participants in any form.
If someone makes you or anyone else feel unsafe or unwelcome, please report it as
soon as possible. Harassment and other code of conduct violations reduce the value
of our event for everyone. We want you to be happy at our event. People like you
make our event a better place.

In order for this tutorial to be successful, we ask that participants take note
of the following guidelines throughout the session:

- This is an interactive workshop, and we expect everyone to, as best as possible,
follow along with the tutorial.
- At the same time, please stay at the same point with us in the tutorial. If you are
finished with a section ahead of time, you are more than welcome to hack away at our
code. We find that staying together through the tutorial works best for everyone
involved.
- Hands on your own computer. Unless otherwise noted, please refrain from writing
code on other's computers. You are more than welcome to explain to your neighbors
what is going on in their notebook, but we want everyone to feel comfortable working
with the code themselves.

If you have any further questions or concerns, please let us know!

## Software

We will be using the Python programming language for the workshop, as well as
several third-party packages. All of it is free and open source. Here is the
link to the Anaconda version of Python that we suggest you use:

- [Anaconda Python 3.7](https://www.anaconda.com/)

We will help you set-up these libraries in the workshop, though please make sure
your operating system is up-to-date (in particular, you will need macOS 10.13 or
10.14 for the libraries to work properly).

## Schedule — Overview

Our specific pace and topics will adjust given the needs of those in the workshop,
but here is an overview of what we plan to cover each day:

- **Day 1**: introductions; setting up Python; understanding how to organize an image
corpus; understand how images are stored digitally; build exploratory plots from
simple image features; working with FSA-OWI photographs
- **Day 2**: machine learning terminology; linear regression for image classification;
penalized regression; applying texture filters; motivation for deep learning; using
well-known computer vision corpora such as Flowers-128 and ImageNet
- **Day 3**: setting up tensorflow, and keras; building deep learning models
from scratch; convolutions; transfer learning; embeddings; use small CV datasets for
datasets from scratch; visualization of wikiart dataset using transfer learning
- **Day 4**: more visualization techniques; the distant viewing toolkit; working
with moving images; face detection; applications to various corpora

If there is something particular you would like us to show or would like to make
sure that we get to, please let us know as soon as possible.

## Schedule — Details

**Monday, 3 June**

- Session 01 — 09:30-10:45 | Introductions and Set-up
- Session 02 — 11:00-12:00 | [session02-brief-intro-python.ipynb.zip](https://raw.githubusercontent.com/statsmaths/hilt2019-image-analysis/master/nb/session02-brief-intro-python.ipynb)
- Session 03 — 13:30-14:30 | [session03-loading-images.ipynb.zip](https://raw.githubusercontent.com/statsmaths/hilt2019-image-analysis/master/nb/session03-loading-images.ipynb), [teapot.jpg](https://raw.githubusercontent.com/statsmaths/hilt2019-image-analysis/master/images/test/teapot.jpg)
- Session 04 — 14:45-16:30 | [session04-extracting-features.ipynb.zip](https://raw.githubusercontent.com/statsmaths/hilt2019-image-analysis/master/nb/session04-extracting-features.ipynb)

**Tuesday, 4 June**

- Session 05 — 09:00-10:30
- Session 06 — 10:45-12:00
- Session 07 — 13:30-14:45
- Session 08 — 15:00-17:00

**Wednesday, 5 June**

- Session 09 — 09:00-10:30
- Session 10 — 10:45-12:00
- Session 11 — 13:30-14:30
- Session 12 — 14:45-16:30

**Thursday, 6 June**

- Session 13 — 09:00-10:30
- Session 14 — 10:45-12:00
- Session 15 — 13:30-14:30
- Session 16 — 14:45-16:30

## References

During the workshop, we will construct a bibliography of references for both
technical and conceptual topics that arise.

- Arnold, Taylor, and Lauren Tilton. *Humanities Data in R*. New York: Springer, 2015.
[link](https://link.springer.com/book/10.1007%2F978-3-319-20702-5).
- Arnold, Taylor, and Lauren Tilton. "Distant viewing: analyzing large visual corpora"
*Digital Scholarship in the Humanities*. [link](https://doi.org/10.1093/digitalsh/fqz013)
- Olga Russakovsky, Jia Deng, Hao Su, Jonathan Krause, Sanjeev Satheesh, Sean Ma, Zhiheng Huang,
Andrej Karpathy, Aditya Khosla, Michael Bernstein, Alexander C. Berg and Li Fei-Fei.
"ImageNet Large Scale Visual Recognition Challenge". IJCV, 2015. [link](https://arxiv.org/pdf/1409.0575v1.pdf)
- Wevers, Melvin, and Thomas Smits. "The visual digital turn: Using neural networks to study historical images"
*Digital Scholarship in the Humanities*. [link](https://doi.org/10.1093/llc/fqy085)
