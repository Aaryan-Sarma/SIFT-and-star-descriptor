Scale Invariant Feature Transform (SIFT) is one of the most popular features in the field of
Computer Vision. David Lowe first proposed this in his seminal paper, which is available at
https://www.cs.ubc.ca/~lowe/papers/ijcv04.pdf. It has since become one of the most effective features to
use for image recognition and content analysis. It is robust against scale, orientation, intensity, and so
on. This forms the basis of our object recognition system.

SIFT feature detector is good in many cases. However, when we build object recognition systems, we
may want to use a different feature detector before we extract features using SIFT. This will give us the
flexibility to cascade different blocks to get the best possible performance.
