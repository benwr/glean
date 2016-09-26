# Glean

Glean is a bitmap font. It is 5x10 pixels. It is based on the 5x10 Neep font by
Jim Knoble.

## Motivation

At work, I write and read a lot of code. I often want to see a lot of code on
my screen at once. This makes me look busier than I really am, and has the
additional benefit of letting me focus on _thinking_ rather than _remembering_
as I navigate my company's codebase.

My company has been very generous in giving me two monitors; typically I use one
for text-based activities (editing and shell), and the other for graphical
activities (stack overflow, simulations, various diagnostic tools). So I have
one monitor for code. This monitor has a lot of pixels by decade-ago standards,
but its pixel density leaves much to be desired by today standards. I have
accidentally become accustomed to crisp, small fonts by a couple of years of using
an old Retina Macbook. Bitmap fonts are better at this than scalable fonts,
especially on screens with low pixel density.

## Major changes

Neep's 5x10 size is nearly perfect for this. It has only a few flaws (all of which
are subjective, and might not be flaws from someone else's perspective):

1. No bold face
2. Non-slashed zero
3. Weird %
4. Weird #
5. Weird '
6. Weird &
7. Weird *


So I fixed these issues. I'm mostly happy with the result; at least, it handily
passes the 0OIl1 test in both bold and regular weights.

These are images of this README and some code, in regular and bold.
![regular-weight](https://raw.githubusercontent.com/benwr/glean/master/regular.png)
![bold-weight](https://raw.githubusercontent.com/benwr/glean/master/bold.png)

The bold face is totally ad-hoc, though, and looks somewhat more cartoonish than
I'd like. Perhaps this is why there is no boldface Neep at this font size. Perhaps
I'm just bad at designing these things. Oh well, it works fine for my purposes,
since only about 1% of my terminal window is bolded at any given moment.

## License

Glean is released under version 3 of the GNU GPL, or any later version.
