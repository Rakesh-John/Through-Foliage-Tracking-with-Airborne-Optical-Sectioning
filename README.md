Data: Through-Foliage Tracking with Airborne Optical Sectioning
====================================================================

**Abstract:**
Detecting and tracking moving targets through foliage is difficult, and for many cases even impossible in regular aerial images and videos. We present an initial light-weight and drone-operated 1D camera array that supports parallel synthetic aperture aerial imaging. Our main finding is that color anomaly detection benefits significantly from image integration when compared to conventional single images or video frames (on average 97\% vs. 42\% in precision in our field experiments). We demonstrate, that these two contributions can lead to the detection and tracking of moving people through densely occluding forest.

**Authors:** **Rakesh John Amala Arokia Nathan**, Indrajit Kurmi, David C. Schedl,  Oliver Bimber



## Data

The  folder `Data` contains 20 sets of data (`SET1` to `SET20`). 
Each set contain 10 undistorted (using OpenCV pinhole camera model) single images that was captured using the 1D drone-operated camera array and the corresponding integral image generated with AOS  for the center perspective. The single images (`C0` to `C9`) represent the order of the cameras from left outermost section to the right outermost section attached equidistant (1m) to each other on a 9m long 1D camera array. 
The folder `Supplementary videos` contains the supplementary data related to the article.

Further details can be found in the main article and supplementary material of our publication: [Journal of Remote Sensing](https://spj.science.org/doi/10.34133/2022/9812765).

## Citation


```bibtex
@article{nathan2022through,
  title={Through-foliage tracking with airborne optical sectioning},
  author={Nathan, Rakesh John Amala Arokia and Kurmi, Indrajit and Schedl, David C and Bimber, Oliver},
  journal={Journal of Remote Sensing},
  year={2022},
  publisher={AAAS}
}

