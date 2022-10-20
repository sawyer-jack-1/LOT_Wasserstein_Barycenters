#  LOT_Wasserstein_Barycenters

Using LOT embeddings of the optimal transport maps between empirical distributions to find an approximate solution to the Wasserstein barycenter problem.

This is a fork of https://github.com/srjr-hkannan/LOTpython and in particular relies on Gaussians.py

This work is using theory from the paper "Supervised learning of sheared distributions using linearized optimal transport" by Varun Khurana, Harish Kannan, Alexander Cloninger, and Caroline Moosmuller. https://arxiv.org/pdf/2201.10590.pdf

Known issue: Entropically regularized wasserstein barycenters aren't super well implemented.

![ExampleGaussians](https://user-images.githubusercontent.com/114702597/196860443-cbbb553f-f96f-4328-9153-4a488c874791.png)
![Geodesic](https://user-images.githubusercontent.com/114702597/196860447-05258b0b-7a41-456b-8e65-08ce1eb36f19.png)
![Midpoint](https://user-images.githubusercontent.com/114702597/196860454-3991fd98-eacb-4faa-8b22-b2f68c56c2d4.png)
![TestGaussians](https://user-images.githubusercontent.com/114702597/196860465-82ad7576-6d01-444b-8ad7-7c979babdd23.png)
![SinkhornGrid](https://user-images.githubusercontent.com/114702597/196860455-e51c4815-3472-4771-896d-13aac6420a9dpng)
![LOTGrid](https://user-images.githubusercontent.com/114702597/196860450-3aa40af0-2b95-4bdf-a948-309440f06812.png)

