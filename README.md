# ImageTriangulation
A short python script that tessellates any image into a mesh of triangles using weighted blue noise sampling. More details to follow soon.

Following external dependencies are required to run the script:
- PIL
- Numpy and Matplotlib
- Scipy
- Skimage
- Pandas

All other imports should be a part of Python 3's internal library suite. 

# Usage
python3 ImageTriangulation.py <input_file_path> <min_dist_between_points>

# Example
python3 ImageTriangulation.py cornell.jpg 25

# Output Images

<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/fluff.jpg" width=665 height=442 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/fluff_990_0.png" width=665 height=442 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/monalisa.jpg" width=627 height=924 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/monalisa_5674_0.png" width=627 height=924 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/kitten.jpg" width=627 height=341 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/kitten_1106_0.png" width=627 height=341 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/earth.jpg" width=613 height=472 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/earth_2824_0.png" width=613 height=472 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/cornell.jpg" width=565 height=561 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/cornell_742_0.png" width=565 height=561 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/scream.jpg" width=803 height=1024 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/scream_4896_0.png" width=803 height=1024 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/starry.jpg" width=799 height=633 />
<img src="https://raw.githubusercontent.com/pxv8270/ImageTriangulation/master/ImageTriangulation/starry_1014_0.png" width=799 height=633 />
