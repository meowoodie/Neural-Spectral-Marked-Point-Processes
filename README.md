### Neural Spectral Marked Point Processes

We present a novel general non-stationary point process model based on neural networks, referred to as the neural spectral marked point process (NSMPP). The key component is a new powerful representation of the kernel function using neural networks, which enables us to go beyond stationarity (and thus go beyond Hawkes processes) and has the capacity to model high-dimensional marks. The premise of the model design is that the conditional intensity function uniquely specifies the distribution of the point process, and the most important component in the intensity function is the influence kernel. In summary, the novelty of our approach includes the following:

* The kernel function is represented by a spectral decomposition of the influence kernel with a finite-rank truncation in practice. Such a kernel representation will enable us to capture the most general non-stationary process as well as high-dimensional marks. The model also allows the distribution of marks to depend on time, which is drastically different from the separable kernels considered in the existing literature
* The spectral decomposition of asymmetric influence kernel consists of a sum of the product of feature maps, which can be parameterized by neural networks. This enable us to harvest the powerful expressiveness and scalability to high-dimensional input of neural networks for complicated tasks involving discrete events data.
* We establish theoretical guarantees of the maximum likelihood estimate for the true kernel function based on functional variational analysis and finite-dimensional asymptotic analysis, which shed light on theoretical understanding of neural network-based kernel functions.
* sing synthetic and real data (seismic and police data), we demonstrate the superior performance of our proposed method in complex situations; the performance gain is particularly outstanding for cases involving non-stationary point processes.

![architecture](https://github.com/meowoodie/Neural-Spectral-Marked-Point-Processes/blob/main/architecture.png)

### Reference
- [*Shixiang Zhu, Haoyun Wang, Xiuyuan Cheng, Yao Xie.* Neural Spectral Marked Point Processes.](https://arxiv.org/abs/2106.10773)
