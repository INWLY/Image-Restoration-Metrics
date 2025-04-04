# Image-Restoration-Metrics
This is a code library that contains the calculation of metrics for various image restoration tasks. Specifically, it includes Peak Signal-to-Noise Ratio (PSNR), Structural Similarity Index Measure (SSIM), Learned Perceptual Image Patch Similarity (LPIPS), and Frechet Inception Distance (FID).  

Specifically, PSNR (Peak Signal-to-Noise Ratio) and SSIM (Structural Similarity Index Measure) are implemented using the `skimage.metrics` library, LPIPS (Learned Perceptual Image Patch Similarity) is implemented using the `lpips` library, and FID (Frechet Inception Distance) is implemented using `pytorch_fid`. The calculation of each metric is standardized and efficient. 

In addition, the calculation methods of the PyTorch version for PSNR (Peak Signal-to-Noise Ratio) and SSIM (Structural Similarity Index Measure) are also provided, which are used to quickly measure the metrics during model training! Specifically, it is achieved by converting tensor data into NumPy data, and then using the official library `skimage.metrics` for implementation.  
