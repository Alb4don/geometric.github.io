- This project is inspired by my scientific paper Curvature-Driven Geometric Flows and Their Application in Image Processing.
- It applies a smooth, uniform smoothing effect across the entire image to reduce slight, widespread noise. However, excessive use will soften sharp edges and result in a blurry result, negatively impacting your SSIM score.
- focus on noise primarily in flat, uniform areas, carefully preserving or even enhancing detected edges.
- Ricci Flow eliminates high-frequency noise, providing a massive and immediate increase in PSNR. However, it does so by fundamentally distorting the underlying geometry of the image, introducing bizarre artifacts and destroying its structural integrity.

![game](https://github.com/user-attachments/assets/8356c5ec-c0e0-4e17-84c6-3b8479c0cf60)
