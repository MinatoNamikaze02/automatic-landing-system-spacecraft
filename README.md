# automatic-landing-system-spacecraft

A repository containing python notebooks with (purely) Image Processing techniques applied to moon surface images to progress towards building an Automated Landing System for Spacecraft.

- spatial.ipynb
  * Spatial Filtering Techniques
    * smoothing
    * sobel
    * laplacian
    * gaussian blur
    * unsharp masking
    * highboost filtering
  
- noise.ipynb
  * Added and removed different types of noise. Used spatial noise reduction techniques. Applied metrics such as PSNR and SSIM.
    * rayleigh noise
    * erlang noise
    * geoometric mean filter
    * median filter filter
    * harmonic mean filter
    * contraharmonic mean filter
    * alpha trimmed mean filter
    * total variation denoising
 
- morph.ipynb
  * Applied morphological image processing techniques.
    * erosion
    * dilation
    * opening
    * closing 
    * thinning
    * hit or miss transform
    * object coordinate extraction and size estimation using morphological techniques and otsu's algorithm.
  
- Freq-domain.ipynb
  * Applied band-pass and band-reject filter.
  
 Libraries Used
 * `OpenCV`
 * `scikit-image`
 * `numpy`
 * `matplotlib`
 
 Remarks
 * Only covered my contributions to the project.
 
 
