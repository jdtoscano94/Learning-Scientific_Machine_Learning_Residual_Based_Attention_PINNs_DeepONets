# A comprehensive and FAIR comparison between MLP and KAN representations for differential equations and operator networks

Kolmogorov–Arnold Networks (KANs) were recently introduced as an alternative representation model to MLP. Herein, we employ KANs to construct physics-informed machine learning models (PIKANs) and deep operator models (DeepOKANs) for solving differential equations for forward and inverse problems. In particular, we compare them with physics-informed neural networks (PINNs) and deep operator networks (DeepONets), which are based on the standard MLP representation. We find that although the original KANs based on the B-splines parameterization lack accuracy and efficiency, modified versions based on low-order orthogonal polynomials have comparable performance to PINNs and DeepONet, although they still lack robustness as they may diverge for different random seeds or higher order orthogonal polynomials. We visualize their corresponding loss landscapes and analyze their learning dynamics using information bottleneck theory. Our study follows the FAIR principles so that other researchers can use our benchmarks to further advance this emerging topic.

Paper DOI: https://doi.org/10.1016/j.cma.2024.117290

# Citation

@article{shukla2024comprehensive,
  title={A comprehensive and fair comparison between mlp and kan representations for differential equations and operator networks},
  author={Shukla, Khemraj and Toscano, Juan Diego and Wang, Zhicheng and Zou, Zongren and Karniadakis, George Em},
  journal={Computer Methods in Applied Mechanics and Engineering},
  volume={431},
  pages={117290},
  year={2024},
  publisher={Elsevier}
}

@article{toscano2024pinns,
  title={From pinns to pikans: Recent advances in physics-informed machine learning},
  author={Toscano, Juan Diego and Oommen, Vivek and Varghese, Alan John and Zou, Zongren and Daryakenari, Nazanin Ahmadi and Wu, Chenxi and Karniadakis, George Em},
  journal={arXiv preprint arXiv:2410.13228},
  year={2024}
}

@article{toscano2024kkans,
  title={KKANs: Kurkova-Kolmogorov-Arnold Networks and Their Learning Dynamics},
  author={Toscano, Juan Diego and Wang, Li-Lian and Karniadakis, George Em},
  journal={arXiv preprint arXiv:2412.16738},
  year={2024}
}


Paper: https://doi.org/10.1016/j.cma.2024.116805


