Unless otherwise noted, the *.gz files were generated by the gzip command line
tool and the *.flate and *.zlib versions were then generated by
script/extract-flate-offsets.go. Similarly, the *.giflzw files were generated
by script/extract-giflzw.go and the *.palette and *.indexes files were
generated by script/extract-palette-indexes.go

The *.jpeg files are usually the canonical versions of the testdata images, and
other versions (*.bmp, *.gif, *.png, *.tiff) were generated by ImageMagick's
convert command line tool. The *.webp versions were generated by the cwebp
command line tool.



The artificial directory holds artificially generated test data, often to
explicitly test corner cases of various file formats. The files there usually
come in families whose names have a common prefix, such as three files
"foo.bar", "foo.bar.qux", "foo.bar.commentary.txt" all prefixed by "foo.bar".
The file whose name is that prefix is usually the canonical (typically
hand-crafted) file, and the other files are then derived from that. Outside of
the artificial directory, the other files in this directory are typically real
world examples of various file formats, or deriviations of them.



bricks-* are various encodings of an original photo by Nigel Tao
<nigeltao@golang.org>.

harvesters.* are various encodings of a photo of "The Harvesters" by Pieter
Bruegel the Elder, held by the Metropolitan Museum of Art.
http://www.metmuseum.org/art/collection/search/435809 lists that image as in
the public domain.

hat.* are various encodings of a photo of "Self-Portrait with a Straw Hat
(obverse: The Potato Peeler)" by Vincent van Gogh, held by the Metropolitan
Museum of art. http://www.metmuseum.org/art/collection/search/436532 lists that
image as in the public domain.

hibiscus.* are various encodings of a photo of "Hibiscus and Parrots" by Louis
Comfort Tiffany, held by the Metropolitan Museum of Art.
http://www.metmuseum.org/art/collection/search/13503 lists that image as in the
public domain.

http://www.metmuseum.org/about-the-met/policies-and-documents/image-resources
says that "You are welcome to use images of artworks in The Met collection that
the Museum believes to be in the public domain, or those to which the Museum
waives any copyright it might have, for any purpose, including commercial and
noncommercial use, free of charge and without requiring permission from the
Museum."

midsummer.txt is an excerpt of Shakespeare's "A Midsummer Night's Dream",
copied from http://shakespeare.mit.edu/midsummer/midsummer.1.1.html

pi.txt contains the digits of pi.

pjw-thumbnail.* are various encodings of an image derived from an iconic,
original photo of Peter J. Weinberger by Rob Pike <r@golang.org>.

romeo.txt is an excerpt of Shakespeare's "Romeo and Juliet", copied from
http://shakespeare.mit.edu/romeo_juliet/romeo_juliet.2.2.html

romeo.txt.fixed-huff.flate was derived from romeo.txt by a custom program to
use fixed (not dynamic) Huffman tables for the flate encoding.
