# Image-Restoration-and-Digital-Image-Inpainting

Digital image processing encompasses a wide range of techniques for enhancing, analyzing,
and manipulating images. Image restoration which is a crucial area in this field, focuses on
reconstructing or recovering an image that has been degraded by various factors such as
noise, blur, or damage. <br><br>

This project explores an image inpainting technique aimed for
restoring damaged images by filling in missing or corrupted parts with senseful pixel values. <br><br>
The project is implemented based on a paper: T. K. Shih, Rong-Chi Chang, Liang-Chen Lu, Wen-Chieh Ko and Chun-Chia Wang, "Adaptive
digital image inpainting," 18th International Conference on Advanced Information Networking and
Applications, 2004. AINA 2004., Fukuoka, Japan, 2004, pp. 71-76 Vol.1, doi:
10.1109/AINA.2004.1283890.  <br><br>

This project implements the proposal of this paper with an adaptive approach, using local and global information to
achieve a high quality restoration.  <br><br>
Additionally, the implementation enhances the proposed
technique with a weighted mean coloring method to improve the inpainting results. The
original technique in the paper usually leaves residual faded lines that are still
visible in reddish, grayish, or bluish hues. An additional method that we added which is the
weighted mean color calculation, results in a clearer and more accurate restoration and
reduces residual lines, and creates a more visually pleasing result. <br><br>
