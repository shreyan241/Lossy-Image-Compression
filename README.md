# Lossy-Image-Compression

We used 2 datasets compare the performance of different methods.

### Dataset links:
[Kodak Dataset Download Link](https://drive.google.com/drive/folders/1KIGFr1xuTwd1PzGG3UNsfuvtuwS5lCL4?usp=share_link)

[Images4k Dataset Download Link](https://drive.google.com/drive/folders/1RNUFcwN23mSW2zF9DcBijlh6OXL0vNC7?usp=sharing)

The code reporository is structured as follows-:

|-DCT.ipynb <br />
|-SVD.ipynb <br />
|-PCA.ipynb <br />
|-PCA_4k.ipynb <br />
|-Kodak <br />
|-Dataset4K <br />
|-.gotignore <br />
|-README.md <br />
No special requirements to run the scripts (We use standard python packages including numpy, scipy, opencv_python, scikit-learn). If the files are structured as described above, you can run the scripts on each of the datasets as described in the code. You might have to change the path of the image folder directory for PCA.ipynb and PCA_4k.ipynb. PCA_4k.ipynb is just the implementation of PCA on the Dataset4K images.
