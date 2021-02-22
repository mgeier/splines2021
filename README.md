Rotation Splines for Spatial Audio Scenes
=========================================


Abstract
--------

A spline is a tool for smoothly creating intermediate values between given key
positions.  Different types of splines are presented, which are used in the
context of an audio scene description format.  Splines are used to compute
intermediate positions in sound source trajectories, which are defined by lists
of points in Euclidean 3D space.  Methods for creating curve segments and for
smoothly connecting those curve segments are shown.  It is desirable to also use
splines to create intermediate values within a list of given 3D rotations.  Even
though rotations don't span a Euclidean space, some of the spline techniques can
be translated to rotations, albeit with limitations.


View Slides
-----------

[click here](https://nbviewer.jupyter.org/format/slides/github/mgeier/splines2021/blob/main/presentation.ipynb)


Copyright
---------

<p xmlns:dct="http://purl.org/dc/terms/">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <span rel="dct:publisher" resource="[_:publisher]">the person who associated CC0</span>
  with this work has waived all copyright and related or neighboring
  rights to this work.
</p>
