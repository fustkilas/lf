Large format photography: how to select the f-stop

How to select the f-stop
------------------------

#### Part 3 of Setting up the view camera

**by [Q.-Tuan Luong](http://www.terragalleria.com/) for the [Large
Format Page](.)**

------------------------------------------------------------------------

*Summary: a systematic method to find the f-stop which as a function of
the displacement of the standards between the far and near points,
measured on the camera with a scale (the focus spread). Two optical
effects are taken into account: [defocus](#defocus) and
[diffraction](#diffraction). This page also contains for
[reference](#ref) the excellent original articles of Stephen Peterson
and Paul Hansma. In practice: First try to use the [optimal
f-stop](#result2) (yields the sharpest possible image at the depth of
field limits) and see what shutter speed you get. If it's too slow, then
try to use the [admissible f-stop](#result1) (based on choice of a
circle of confusion).*

### Operational summary

Using movements and focussing, you have already placed the plane of
focus.

-   If you managed to get everything in focus, then the f-stop you could
    use would be the smallest one (ie largest aperture) for which you
    have no vignetting. However, because you don't want to worry about
    misalignments and optical aberrations, you would probably choose a
    couple of f-stops from wide open. Most LF lenses just aren't
    corrected well for wide apertures, since it was assumed they wouln't
    be used that way. Film flatness is more problematic with LF than
    with other formats. The film tends to buckle and curve away from the
    film plane, so a little extra depth of focus helps.
-   Otherwise, you need to extend your depth of field by stopping down
    the lens. This article will show you how much. You will see it is a
    lot.

For example, I looked at the technical data for the 49 photographs in
John Sexton's *Listen to the trees*, done with a 4x5. The breakdown was
as follows:

    f16   f22   f32   f45   f64 
     5%   30%   50%   20%    5%

Would the project have been *Smell the tidepools*, the breakdown would
have been probably quite different, but this still gives you an idea of
what f-stops are commonly used.

If you don't want to read the explanations and wade in the math which
follows, here are the important points explaned in more details in this
article:

1.  If you stop down a lot diffraction will degrade resolution.
2.  However, if the subject is very "three-dimensional" you might have
    to stopping down a lot to have enough depth of field. In this case,
    do not worry about point 1, since the effect of not having enough
    depth of field will be more detracting than the loss of resolution
    due to diffraction, which is not that significant with large format.
3.  There is a very simple and practical way to find which f-stop you
    need to use, taking both point 1 and 2 into account. It is due to
    Paul Hansma. Make your movements first. Then focus on far, focus on
    near, read the distance "D" in millimiters between the two positions
    on your rail, refocus so as to split the distance on the rail, and
    use the following table that I recommend you carry with you all the
    time. "F" is given in decimal f-stops, as on a hand-held meter, for
    example 16.6 is 16 and 0.6 (aka between 1/2 and 1/3) of a f-stop.
    See [here](#result2) for details.

        D(mm) F        
         1   16.6      
         2   22.6      
         3   32.2      
         4   32.6      
         5   32.9       
         6   45.2       
         7   45.4       
         8   45.6       
         9   45.8       
        10   64         

Now time to get technical... []{#defocus}

### The defocus circle of confusion

Let consider a bright point in space surrounded by a dark background, or
equivalently a point light source. It is converged by the lens into a
cone. The image of the point is the intersection of the film plane with
the cone. If the point in space lies in the plane of focus, the tip of
the cone coincides with the film plane, so that the image is a point. If
the point in space lies outside the plane of focus, the cone is not
intercepted by the film plane at the right place, therefore the image is
a circle, called the circle of confusion. The more the point is out of
focus, the larger is the circle. If tilts are used, the image is
actually an ellipse, however for reasonable amounts of tilts, the circle
is a good approximation.

If the circle of confusion is large, the image will look fuzzy. If the
circle of confusion is small, then it will be indistinguishable to the
eye from a point, and the image will look sharp. There is not a
universal boundary between fuzzy and sharp. The blurring of an out of
focus point occurs gradually. The calculations done in this document
should be taken just as general guidelines. When you use a depth of
field scale, you rely on the manufacturer's choice of a value for the
acceptable circle of confusion. This value might not be the best for
your use.

The brightness within the circle of confusion is constant. If we use the
criterion that two points are resolved when their circle of confusion do
not overlap (if the circles overlap, the two points are imaged in a
continuous bright spot) then the resolution R is related to the diameter
of the circle of confusion c by R = 1/c. This is the number of
non-overlapping circles of confusion that can be fit in a unit length.
If c is expressed in millimeters, then R represents the number of lines
pairs per millimiters (lp/mm). One precision is necessary here. We have
considered two bright points, separated by a dark space. This is the
same situation as two bright lines separated by a dark line. Each
element consists of a dark line and and bright line. The separation
between each element is c. A source of confusion is that some authors
consider a line pair (a dark line and a white line) to be two lines, so
they would use R = 2/c. This corresponds to the number of pixels.

### What is an acceptable circle of confusion ?

The diameter of the largest circle of confusion which is perceived by
the eye as a point is called the acceptable (or permissible) circle of
confusion. The acceptable circle of confusion c on the negative depends
on:

-   resolvable distance by the eye c0 at mimimum viewing distance d0
-   viewing distance d
-   enlargement factor m (size of final print / size of negative)

The equation is c = c0/m \* d/d0 .

The smallest resolvable distance c0 is such that two dark lines
separated by more than this distance (by a white line) are seen as two
lines, while two dark lines separated by less than this distance would
be seen as one line. It is generally agreed that at normal minimal
viewing distance d0 (reading distance, around 25cm), the eye can resolve
elements spaced at 0.2mm. A good choice for the diameter of the
acceptable circle of confusion c on a print viewed at that distance is
therefore 0.2mm. The resolution is R0 = 1/c0 = 5 lp/mm Some people feel
that the eye can sense finer details.

The resolving power of the eye is approximatively inversely proportional
to the viewing distance d. A common practice is that a print should be
viewed from a distance approximately equal to the diagonal measurement
of the print. The rationale is that the eye would then be at the center
of projection if the image was taken with a normal lens (whose focal is
equal to the diagonal measurement of the negative), resulting in a
correct perspective. Personally I am not fond of this rule. After
viewing the image as a whole, I always like to come closer to see the
details. It is in order to preserve those details, even in extreme
enlargements, that you use a large format camera in the first place !

The enlargement factor is the ratio of the linear dimension of a feature
on the print by its corresponding feature on the negative. If the print
and the negative don't have the same aspect ratio, it is not the ratio
of the dimensions of the print and the negative.

Lets illustrate the formula c = c0/m \* d/d0 by a few examples. We
assume c0 = 0.2 (average eye resolution), and d/d0 = 1 (print viewed at
the minimal distance). The formula becomes c = 0.2/m

To make a full-format 6x8 (150mm x 200mm) from a 35mm negative (24mm x
36mm), you match the two smaller dimensions, so the magnification is m =
150/24 = 6.25, and the acceptable circle of confusion on the negative is
c= 0.2 \* 1/6.25 = 0.032mm. This value appears to be used by most of the
35mm lens manufacturers on their depth of field scale. The diagonal of a
150mm x 200mm (6x8inch) print is 250mm (10inch), which corresponds to a
normal minimal viewing distance.

To make a full-frame 8x10 (200mm x 250mm) from a 35mm negative (24mm x
36mm), you match the two larger dimensions, so the magnification is m =
250/36 = 7, and the acceptable circle of confusion on the negative is c
= 0.2 \* 1/7 = 0.028mm. This indicates the limitation of the depth of
field scales commonly used: even a 8x10 looked closely won't appear
critically sharp. To make the same print from a 4x5 (100mm x 125mm)
negative, the magnification is 250/125 = 2, and the acceptable circle of
confusion on the negative is 0.2 \* 1/2 = 0.1mm. This value is often
used for LF depth of field tables, but personally I don't find it
adequate.

In summary, the acceptable circle of confusion on the negative depends
on a number of factors, and it is better to determine the one which is
best for you, rather than rely on the manufacturer's which is often not
critical enough.

### The relation between focus spread and the circle of confusion

If you have followed the [method II.3](how-to-focus.html#focus), you
have chosen a point of nearest focus and a point of furthest focus,
measured the distance D (called here the *focus spread* between the two
focussing rail positions. If the distance D was zero, then everything is
exactly in focus because your subject is planar or at infinity.

Calculations ([see references](#ref)) show that for small
magnifications, the relation between the focus spread D and the diameter
of the circle of confusion c is extremely simple, and gives you the
*admissible f-number*:

    N = D/(2c)

where N is the f-stop number, regardless of the focal length or format
used. Once you have determined what is an acceptable circle of confusion
for you, this formula gives you the f-stop, proportional to the focus
spread. As an example, here are the tabulated values that I would use,
based on c=0.1 for 5x7. This gives a critically sharp 11x14 at minimum
viewing distance, and has the advantage of being easy to remember. I've
also included in the table the equivalent for 4x5 based on c=0.066, and
8x10 based on c=0.133 Distances are in mm. []{#result1}

#### Table of admissible fstops

This shows you the fstop to which you should stop down at a minimum if
you want to achieve a circle of confusion c=0.066 on 4x5 (resp. c=0.1 on
5x7, and c=0.133 on 8x10).

    focus spread    admissible
    4x5  5x7  8x10   fstop
      D (mm)           N
    1.4   2.2   2.8    11
    2.1   3.2   4.2    16
    3.0   4.5   6.0    22
    4.2   6.4   8.4    32
    6.0   9.0  12.0    45
    8.5  12.8  17.0    64

The focus spread is sometimes refered to as *depth of focus*, the
acceptable distance between imaging planes for a given circle of
confusion and f-stop D = 2cN.

In the previous formula N is the effective f-number. For close-ups, you
would replace the f-stop by the effective f-stop, and use instead the
relation:

    N = f/v * D/(2c) = 1/(1+M) * D/(2c)

where f is the focal and v your total belows extension. M is the
magnification. Since the ratio f/v is always smaller than 1, by using
the previous formula, you always end up stopping down more than
necessary. Note that at infinity, the ratio is exactly 1.

I think this approach is most useful for judging whether within the
constraints dictated by the shutter speeds that you can use, you can get
your subjects sufficiently in focus. For instance, you are trying to get
a field of flowers in focus at the same time as a tree behind. You
measure a focus spread of 10mm between the closest flower and the tree.
In 5x7, you'd need to stop down at 45. Is the resulting shutter speed
acceptable, given the small breeze ? If yes, you just go ahead and take
the picture. If no, you might want to change the composition so that the
closest flower would be a bit further.

As a general approach (ie independently from the constraints), the
drawback of this approach is that it relies on the choice of an
acceptable circle of confusion, which in turn depends on a number of
factors, including the dimensions and display of the final print. Since
you don't necessarily know what you'd like to do with your negative in
the future, why don't you just use a very tight acceptable circle of
confusion and stop down more ? The next two sections answer this from an
optical point of view. []{#diffraction}

### Diffraction

A beam of light passing through a circular aperture spreads out a
little, a phenomenon known as diffraction. Diffraction is a physical
phenomena which is unescapable. The smaller the aperture, the more the
spreading. For photographic lenses, diffraction depends only on the
f-number N.

Strictly speaking, diffraction is a function of aperture size or the
physical size of the hole and that is how it would be defined in a
physics textbook. Which means that the larger area aperture in a 300mm
lens at f/16 (as compared to a 50mm lens at f/16) should provide lower
diffraction. However, diffraction patterns are angular patterns and as
such are dependent on how far from the aperture you place the screen
used to view it also. In photography, the aperture is at the optical
center of the lens and the screen is (for infinity focus) one focal
length away. The physical size of the diffraction blur is then the focal
length divided by the apparent size of the aperture i.e., the definition
of the f stop. Thus, in photography, diffraction is only a function of f
stop and not a function of the focal length. In simpler terms, the
larger aperture of the 300mm lens does offer lesser diffraction at the
diaphragm (i.e., less bending around the diaphragm) but since the light
now has a longer distance to travel (as compared to the 50mm lens), the
smaller bending still results in a fair bit of blur at the viewing
screen. **N Dhananjay**

The image of a point light source (such as a star) after diffraction
appears not as a point, but as a central circular spot surrounded by a
series of dark and bright rings. See [references](#ref-diff) for details
and formulas. Because a point source is imaged as a disk rather than a
point, it will appear blured, and this limits the maximum resolution of
the lens. The formula R = 1500/N explaned below, gives the maximum
resolution of the lens as a function of the f-number N.

The central spot size due to diffraction, called the Airy disk, has a
diameter of d = 2.44 x lambda x N. Note that this formula depends on the
f-stop and not on the physical aperture of the lens. For a wavelength
near the middle of the visible, lambda = 550 x 10 exp(-9) meters , d =
1.34 x 10 exp(-6) x N meters, or d = N / 750 if d is in mm. No lens can
make a spot smaller than that value. 86% of the power is in the Airy
disk, so it can be viewed as the image of the point. However unlike in
the case of defocus, the brightness within the central diffraction spot
is not constant, but it decreases from the center to its border, where
it reaches 0, resulting in a dark ring. If we use the Rayleigh's
criterion that two points are resolved when the dark ring of one
coincides with the center of the Airy disk of the other, the
corresponding resolution is R = 2/d.

    fstop     resolution limit
      N     R (lp/mm)    d (mm)    
      11     136         .014
      16      93         .021
      22      68         .029
      32      46         .042
      45      33         .059
      64      23         .085

These values correspond to the "diffraction limit" of resolution, the
maximum resolution which could be achieved on perfect film by a perfect
lens. Don't expect a real lens to deliver 136 lp/mm at f11.

As it can be seen from these values, stopping down the lens beyond a
certain point degrades considerably the resolution. However, this is
more of a concern to small camera users than to large format users who
don't need a large enlargement ratio. At f22, the diffraction spot
equals the acceptable circle of confusion for 35mm. At f64, it barely
equals the acceptable circle of confusion for 4x5. There is still plenty
of sharpness left, and these values indicate that you shouldn't be too
worried about stopping down a lot if necessary. Some folks on the East
Coast thought that that Ansel Adams f64 Group was lame and started a
f180 Group.

An aggravation to note is that the fstop N is the effective aperture.
Therefore, if you are working at 1:1, your f-number would be doubled
(two f-stops), and the resulting resolution would be divided by two. Add
to that the fact that you need to stop down a lot a close distances to
get enough depth of field, and you see why there are not many folks
doing macro work with LF

### Finding the optimal f-stop to balance defocus and diffraction

-   Defocus, resulting in the circle of confusion of diameter c=D/(2N),
    is more important for large apertures (small N)
-   Diffraction , resulting in the spot of diameter d=N/750, is more
    important for small apertures (large N)

The more you stop down, the more you gain sharpness for the out of focus
points at the depth of field limit, but at one point, diffraction
effects outweight whatever gain is obtained. Intuitively, the optimal
point is when the two effects are equal.

Although the more rigorous way to combine both effects is the use the
MTF ([see references](#ref)), a good approximation is to use the root
mean square error of the two diameters. The total circle of confusion
is:

    ct = sqrt( (D/(2N))^2 + (N/750)^2 )

This quantity is mimimal when N = sqrt(375 D). For such a f-number, the
diameter of the defocus circle of confusion is exactly equal to the
diameter of the diffraction spot: D/(2N) = N/750.

This choice of f-stop is optimal, in the sense that it will yield the
sharpess possible image at the depth of field limits. However, the
larger your focus spread, the less sharp it will be. Sometimes you want
to know whether it results in enough resolution for the enlargements you
want to make. The resulting total circle of confusion has a diameter:

    ct = sqrt(2)/750 N =  N/530  = .0365 sqrt(D)

If you have predetermined a value for the acceptable circle of confusion
ct, this formula gives you the maximum focus spread and f-stop that you
can use:

    D = 750 ct^2     N = 530 ct

Let suppose that you are assuming average eye resolution and minimal
viewing distance, then ct = 2 \* 0.2/m, where m is the enlargement
factor. This gives you the following values:

    m      D(mm)     N
    2     30        106
    3     13        70
    4     7.5       53
    5     4.8       42
    6     3.3       35

The defocus and the diffraction result in two different light patterns,
which in turn lead to two different definitions of resolution. Remember
that in the defocus case, brightness in the circle is uniform, and two
points are considered resolved when their circle of confusion do not
overlap, resulting in a resolution R = 1/c, while in the diffraction
case, brightness is more concentrated at the center. If one accepts the
technical definition that two points are resolved using the Rayleigh's
criterion, this would result in the resolution R = 2/d. For this reason,
Bob Wheeler advocated combining the circle of confusion with the central
half of the diffraction spot, ie using N/1500 instead of N/750,
resulting in the optimum f-number: N = sqrt(750 D). In practice, this
would mean using the next f-stop in the table below (ie for D=1.3mm,
you'd use f32 instead of f22), which would imply stopping down even
more.

However, Paul Hansma suggests that from a photographic point of view,
the Rayleigh criterion is not really enough. The brightness between the
two "resolved" objects is very close to the peak brightness, so we would
not call them resolved if that is what we saw in a photo. To have a
level of resolution comparable to that obtained with the circle of
confusion, where there is no overlap, would call for having no overlap
of the two diffraction spots. This would explain why N/750 fits his
experimental results very well.

[To summarize, if D is the focus spread expressed in millimeters, then
the *optimal f-stop* which yields the sharpest possible image at the
depth of field limits is N = sqrt(375 D). This works regardless of focal
lengths, formats, and movements. The resulting resolution at the limits
of depth of field (ie for your far and near points) cannot be improved
in anyway and determine the maximum possible enlargment. Here are some
tabulated values by whole fstops:]{#result2}

#### Table of optimal fstops (1)

    focus   optimal   resolution        resolution      maximum enlargment
    spread   fstop    at DOF limits    for in-focus     based on DOF limits
    D (mm)    N      ct(mm) R(lp/mm)   d (mm) R(lp/mm)         m
    .3        11     .021   95         .014    136             19
    .7        16     .030   65         .021     93             13
    1.3       22     .042   47         .029     68              9
    2.7       32     .061   32         .042     46              6.4
    5.4       45     .085   23         .059     33              4.6
    11.0      64     .122   16         .085     23              3.2

Here are tabulated values by whole millimeters focus spread. I give the
f-stop is given in decimal values ("F"), followed by actual f-number
("N"). Now what does "decimal value" mean ? It is what you would read on
a meter graduated in 1/10th of fstops, like many hand-held meters. For
instance, "decimal" 22.33 means 22 and one third of a stop (0.33),
"decimal" 22.5 means 22 and a half stop (0.5), whereas in f-numbers this
would be respectively 25.4 and 26.9 which certainly speaks less to me.
On my camera, I have stuck only the decimal values.

#### Table of optimal fstops (2)

This shows you the best value of the f-stop to use.

    D(mm) F          N
     1   16.6       19.4
     2   22.6       27.4
     3   32.2       33.5
     4   32.6       38.7
     5   32.9       43.3
     6   45.2       47.4
     7   45.4       51.2
     8   45.6       54.8
     9   45.8       58.1
    10   64         61.2

The fstop given on these tables is optimal in the sense that it is the
choice which yields the sharpest results at the DOF limits among all the
other possible f-stops. Remark that this table implies that you have to
stop down a lot ! This assumes that other considerations (wind,
reciprocity...) do not prevent you from doing so, in which case you'd
have to compromise. By compromising, I mean you would use an f-stop
other than the optimal value. Then by applying the [admissible
f-stop](#result1) above, you would see if that non optimal f-stop gives
you a result which is acceptable, although you know now that it would
not be the best possible. In general, calculations show that results
pretty close to the optimal one are obtained within 1 fstop of the
optimal value.

The previous calculations were done at zero magnification. As before, or
close-ups, you would replace the f-stop by the effective f-stop.

### Satisfying sharpness requirements for the horizon

If you focus on the point which is 2/3 from the near, 1/3 from the far,
as suggested in the [focussing method II.3](how-to-focus.html#focus),
and the focus spread between near and far was D then the actual focus
spread is 4/3 \* D. This is because you have "wasted" 1/3 behind the far
point to ensure that the horizon is critically sharp.

-   When using the relation N = D/(2c), you need to multiply your f-stop
    by 1.33, which is quite close to just adding one more f-stop.
-   When using the relation N = sqrt(375 D), you need to multiply your
    f-stop by 1.15, which is quite close to adding one half-stop.

### What about real system resolution ?

The optics that I outlined so far give you the aerial resolution
r\_lens, assuming a perfect lens (resolution limited only by
diffraction), and ignoring the film. This is a valid approach in LF for
the two reasons discussed next.

Because of various optical aberrations, lenses are not perfect. However,
stopping down enough corrects those aberrations pretty well in modern
lenses, well enough that they can be considered diffraction limited at
f22 and smaller apertures.

The final resolution r\_final that you get on film depends not only on
the aerial resolution of the lens r\_lens but also on the resolution of
the film r\_film. However, when r\_lens becomes critical, the effect of
r\_film becomes quite neglectible. In LF, since you have to stop down so
much, this is almost always the case.

Several sources use the formula 1/r\_final = 1/r\_lens + 1/r\_film to
compute the final resolution. This formula is an approximation to the
exact calculation consisting of the convolution of the response of the
film and the response of the lens. This approximation is most valid when
both the film and lens are being used near their resolution limits
(spatial frequencies with very low contrast). This corresponds roughly
to f-stops up to f16. Thus the formula is pretty good for 35mm and MF
work. However, when the frequencies involved are nowhere near the film
limits, the formula is a poor approximation which predits a worse
1/r\_final than what you actual get. For f-stops of f32 and higher, what
you get on film is in fact practically equal to the aerial resolution,
and the formula shouldn't be used in that case.

------------------------------------------------------------------------

### Alternative methods

The method recommended in this document used measurements on the camera,
ie in image space. I don't think using depth of field calculations in
object space is a good idea with the view camera. First, unlike on
helicoidal-mounted lenses used on rigid cameras, you don't have a
focussing scale indicating at what distance your lens is focussed,
neither do you have a depth of fields scale. I guess you could use a
laser range finder and a bunch of depth of field tables. Even though,
and this is the second point, tables can be used only when the standards
are maintained parallel. Third, why use a method based on guessing, when
you can fairly easily use an exact method ?

Some people think that instead of using all that math, you should just
rely on inspecting the ground glass. You would watch it through a lupe
as you stop down, and see when the out of focus areas become sharp
enough. For several years I have relied on this approach. I eventually
found, when I switched to a higher power lupe for evaluating the
transparency on the light box, that this yielded results less sharp than
I wanted. The problem is that it is not that easy to make a good
judgement of sharpness on the ground glass. The image is grainy, and
when you stop down, it gets pretty dim, especially through a lupe in the
corners of a wide-angle view.

### References

[The idea to relate the focus spread to depth of field was first
implemented by Sinar in their cameras. As their patent ran out, other
manufacturers, including Arca-Swiss came up with a similar device.
Masayoshi Hayashi wrote a]{#ref}[document](dofknob/) detailing how to
make one for your own camera. It discusses the magnification factors,
which were ignored by Sinar. In the 35mm world, Canon incorporated it in
their EOS bodies as the "Depth" mode. Here are some articles which
detail this idea:

-   *Image sharpness and focussing the view camera*: [page
    1](articles/peterson-dof.1.gif), [page
    2](articles/peterson-dof.2.gif), [page
    3](articles/peterson-dof.3.gif) (gif files, reproduced with the
    author's permission) by [Stephen
    Peterson](http://www.summitek.com/), in Phototechniques March/April
    96. Derives the relation, discusses the circle of confusion and
    explains how to take diffraction into account in the calculations.
-   [Depth of field and the view
    camera](http://www.micronet.fr/~deriencg/DOFforLF.pdf), a draft by
    Guy de Riencourt. Derives the relation and explain how to modify it
    when sharpness at infinity is required.
-   [*Apparent Depth of Field: Practical Use in Landscape
    Photography*](http://www.englander-workshops.com/documents/depth.pdf),
    by Joe Englander. Discusses the circle of confusion and sharpness at
    infinity.

[Material on diffraction includes]{#ref-diff}[the Melles Griot
catalog](http://www.mellesgriot.com/pdf/001.20-1.22.pdf), and [David
Jacobson's lens
tutorial](http://www.photo.net/photo/optics/lensTutorial). In the latter
reference, defocus and diffraction are combined using the MTF. The
resulting [on-film resolution
values](http://bobatkinsdev.furfly.net/photography/technical/dofdiff.html)
were calculated by Bob Atkins. Using the formulas in this article, for
c=0.035, at f32, D= 2 \* 0.035 \* 32 = 2.24, ct = .0365 \* sqrt(2.24) =
.054, which gives the resolution R = 2/.054 = 37 lp/mm, which is in the
ballpark of Bob Atkins calculation of 43.5 lp/mm. Note that his data at
f32 supports the observation that at high f-numbers, on-film resolution
is pretty close to aerial resolution.

The idea of combining the effects of diffraction and defocus to find the
optimal f-stop was introduced in the article *View camera focussing in
practice*, [page 1](articles/hansma-dof.1.gif), [page
2](articles/hansma-dof.2.gif), [page 3](articles/hansma-dof.3.gif),
[page 4](articles/hansma-dof.4.gif) (gif files, reproduced with the
author's permission) by [Paul
Hansma](http://www.physics.ucsb.edu/~prasant/) in Phototechniques
March/April 96. Most of the ideas developed in this page are from this
article. Later, Bob Wheeler, in his [*Notes on view camera
geometry*](%0Ahttp://www.bobwheeler.com/photo/ViewCam.pdf), section 9.3,
advocated combining the radius of the diffraction spot N/1500 with the
circle of confusion, rather than the diameter N/750. His own data
support this argument, which is theoretically sound. However Paul
Hansma's experiments seem to have been conducted more carefully.

Struan Gray suggests this [r.p.e.l-f usenet
thread](http://groups.google.com/groups?hl=en&lr=&safe=off&th=783e23810f8662c2&start=0&ic=1)
for a discussion of system resolution (ie combining lens resolution and
film resolution).

[View or add
comments](http://www.greenspun.com/com/qtluong/photography/lf/fstop.html)


