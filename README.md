#  LOT_Wasserstein_Barycenters

Using LOT embeddings of the optimal transport maps between empirical distributions to find an approximate solution to the Wasserstein barycenter problem.

This is a fork of https://github.com/srjr-hkannan/LOTpython and in particular relies on Gaussians.py by Harish Kannan + collaborators. 

This work is using theory from the paper "Supervised learning of sheared distributions using linearized optimal transport" by Varun Khurana, Harish Kannan, Alexander Cloninger, and Caroline Moosmuller. https://arxiv.org/pdf/2201.10590.pdf

Known issue: Entropically regularized wasserstein barycenters aren't super well implemented.
