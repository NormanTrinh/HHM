# `Converted to python`

# Paper: [paper.pdf](paper.pdf)

# Array camera color correction
[main.m](main.m):   demo function of two images color correction, input: /6to7

[HHM.m](HHM.m):    input: two overlaps, output: map,(1X3X256)

[PA.m](PA.m):    input: map, image to be corrected, output: image after correction

[Th.m](Th.m):   find threshold, input: an image   output: threshold Th([0,255])

/data: N images and their overlaps, example data is in data1.rar and data2.rar

[run.py](run.py): same as `main.m`

# Note
- Results have been tested on Intel(R) Core(TM) i3-10100 CPU @ 3.60GHz
