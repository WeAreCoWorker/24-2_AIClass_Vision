# GradeA+GS

## **Summary**
Novel view synthesis from unconstrained images with Deformable 3D Gaussian Splatting

## **Result Examples**
Reference image |  Trevi-fountain  |  Brandenburg-gate  |  Scare-Coeur
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
Blank | ![Trevi-fountain](result/Trevi-fountain.gif) | ![Brandenburg-gate](result/Brandenburg-gate.gif) | ![Scare-Coeur](result/Scare-Coeur.gif)
![Star](result/Star.png) | ![Star_Trevi](result/Star_Trevi.gif) | ![Star_Brandenburg](result/Star_Brandenburg.gif) | ![Star_Scare](result/Star_Scare.gif)
![Picasso](result/Picasso.png) | ![Picasso_Trevi](result/Picasso_Trevi.gif) | ![Picasso_Brandenburg](result/Picasso_Brandenburg.gif) | ![Picasso_Scare](result/Picasso_Scare.gif)
![Mountain](result/Mountain.png) | ![Picasso_Trevi](result/Mountain_Trevi.gif) | ![Picasso_Brandenburg](result/Mountain_Brandenburg.gif) | ![Picasso_Scare](result/Mountain_Scare.gif)

## **Experiment Result**
Blank | PSNR | SSIM | LPIPS
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
Existing Methods | 30.06 | 0.946 | 0.114
W/O Diffusion | 30.13 | 0.944 | 0.112
W/O VGG | 29.33 | blank | blank
W/O LischipzMLP | 29.76 | 0.927 | 0.145
Full | 30.73 | 0.942 | 0.116
