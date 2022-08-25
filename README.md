# Paper: [paper.pdf](paper_and_slide/paper.pdf)
# Slide: [slide.pdf](paper_and_slide/slide.pdf)

# Array camera color correction
[run.py](python/run.py): same as `main.m`

[main.m](matlab/main.m):   demo function of two images color correction, input: /6to7

[HHM.m](matlab/HHM.m):    input: two overlaps, output: map,(1X3X256)

[PA.m](matlab/PA.m):    input: map, image to be corrected, output: image after correction

[Th.m](matlab/Th.m):   find threshold, input: an image   output: threshold Th([0,255])

- data: N images and their overlaps, example data is in data1.rar and data2.rar. More data: [click here](https://www.mediafire.com/file/3e7x9maa2u3wwen/utf-8%2527_%2527data110.rar/file)

# Terminal
```
conda create -n py39 python=3.9
```
```
conda activate py39
```
```
cd python/
```
```
pip install -r requirements.txt
```
```
python run.py
```
# Note
- Results have been tested on Intel(R) Core(TM) i3-10100 CPU @ 3.60GHz

`Map time`:  0.05622458457946777

`Color adjustment time`:  0.0781698226928711
