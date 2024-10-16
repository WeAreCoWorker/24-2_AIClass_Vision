# GradeA+GS

## **Summary**
Novel view synthesis from unconstrained images with Deformable 3D Gaussian Splatting

## **Result Examples**
Reference image |  Trevi-fountain  |  Brandenburg-gate  |  Scare-Coeur
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
Blank | ![Trevi-fountain](result/example/Trevi-fountain.gif) | ![Brandenburg-gate](result/example/Brandenburg-gate.gif) | ![Scare-Coeur](result/example/Scare-Coeur.gif)
![Star](result/reference/Star.png) | ![Star_Trevi](result/example/Star_Trevi.gif) | ![Star_Brandenburg](result/example/Star_Brandenburg.gif) | ![Star_Scare](result/example/Star_Scare.gif)
![Picasso](result/reference/Picasso.png) | ![Picasso_Trevi](result/example/Picasso_Trevi.gif) | ![Picasso_Brandenburg](result/example/Picasso_Brandenburg.gif) | ![Picasso_Scare](result/example/Picasso_Scare.gif)
![Mountain](result/reference/Mountain.png) | ![Picasso_Trevi](result/example/Mountain_Trevi.gif) | ![Picasso_Brandenburg](result/example/Mountain_Brandenburg.gif) | ![Picasso_Scare](result/example/Mountain_Scare.gif)

## **Experiment Result**
Blank | PSNR | SSIM | LPIPS
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
Existing Methods | 30.06 | 0.946 | 0.114
W/O Diffusion | 30.13 | 0.944 | 0.112
W/O VGG | 29.33 | blank | blank
W/O LischipzMLP | 29.76 | 0.927 | 0.145
Full | 30.73 | 0.942 | 0.116
