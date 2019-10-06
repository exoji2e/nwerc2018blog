---
layout: post
title:  Geometry training
date:   2018-10-24
author: Måns Magnusson
sectionid: blog
---

Geometry, geometry, is very hard to code. It's very easy to miss an edge case, get a floating point rounding error or just assume something that does not hold in general.

Some geometry problems are although very standard, for example calculating the convex hull of a set of points, which is a very common step in geometric problems. It's also easy if you've already done it before. However it is also easy to become tricked into thinking a geometry problem is easy, making the team spend hours trying to find the bugs, while they could have solved 2 other problems that seemed harder. Therefore we did a specific training on geometry. I put together 15 different geometry problems, 3 were quite easy, 3 medium and the rest of the problems i consider pretty hard: likely that less than 20 out of 200+ teams would solve it at NCPC.

Within the first 30 minutes `from __future__ import solution` solved the 2 easiest problems, then they started with one of the problems I considered hard.

`iiiii` solved two other problems, but both involving lines pretty fast as well. Apparently `iiiii` are experts at lines, however when the problems only involves points it seems to become harder. After a while they found the easy problems. The last problem they solved they got a weird wrong answer. The code was really simple, what could go wrong? When casting a long to a double in java, precision is lost, from `63` bits to `53`, this means that when dividing a long, with the double `2.0` the error can become of the size of a tenth of a unit. This meant the code of `iiiii` probably printed `x.4` or `x.6` when the correct answer was `x.5`. The solution to this problem was to produce the string to be printed by hand with integer division and then append `".0"` if even or `".5"` if odd. Or one can use python, which  `from __future__ import solution` did.
![Louise, Åke and Malte]({{site.baseurl}}/assets/imgs/181024/ALM.jpg)

After 5 hours, `from __future__ import solution` managed to solve 6 problems, missing 2 problems easier problems, while trying (but failing) to solve 2 problems that _felt_ easy, but were harder. A useful lesson, especially during a competition that doesn't matters!
![Björn, Jonatan and Lars]({{site.baseurl}}/assets/imgs/181024/BJL.jpg)
