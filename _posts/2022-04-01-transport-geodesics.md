---
layout: post
title: Transport geodesics
categories: Miscellaneous
---

The concept of _transport geodesics_ was introduced in <a href="{{ site.baseurl }}/research">[3]</a>.
They are traces of individual masses that move along a sequence of optimal transport plans. 
If the concatenation of those optimal transport plans is also optimal (i.e., triangle inequality for L<sup>1</sup>-Wasserstein metric holds with equality),
then all such traces must be geodesic. In short, transport geodesics are shortest paths which are constructed from optimal transport plans.

Here I draw transport geodesics on certain graphs. Masses are transported through a sequence of probability measures 1<sub>v<sub>0</sub></sub>,
&mu;<sub>v<sub>0</sub></sub>, &mu;<sub>v<sub>1</sub></sub>, ..., &mu;<sub>v<sub>n</sub></sub>, 1<sub>v<sub>n</sub></sub>, 
where v<sub>0</sub>,v<sub>1</sub>,...,v<sub>n</sub> is a diametral geodesic, and  1<sub>v</sub> is the dirac measure on v, and &mu;<sub>v</sub> is uniformly distributed measure on the ball of radius 1 around v.
