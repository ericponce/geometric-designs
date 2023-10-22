# geometric-designs
Code for generating fun geometric designs

## Blobs
Inspired by the geometric designs of the indigenous Guna people from Panamá and Colombia on their Molas.

The basis for the code was partially provided by ChatGPT-4 and modified to actually work and not require the use of node.

The prompts used (numbered to show separate sequence) are:

```
1) write javascript code to generate geometric designs that are similar to the panamanian mola on a canvas element
2) I want the shapes to be randomly spaced blobs that line up with their neighbors
3) Now, add spacing between the blobs
4) Now use an fft based algorithm to smooth and round out the points of the polygon
5) before smoothing what function would increase the number of points per polygon
```

These prompts produced code to generate voronai diagrams (blobs that line up), a shrinking algorithm to add spacing to those blobs, a linear interpolation algorithm to increase the number of points on those polygon blobs, and an fft based smoothing algorithm for those polygons. 