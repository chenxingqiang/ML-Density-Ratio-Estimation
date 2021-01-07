# Unconstrained Least-Squares Importance Fitting (uLSIF)

- *Unconstrained Least-Squares Importance Fitting (uLSIF)* is an algorithm to directly estimate the ratio of two density functions without going through density estimation. The solution of uLSIF as well as the leave-one-out score can be computed analytically, thus uLSIF is computationally very efficient and stable. Furthermore, the uLSIF solution tends to be sparse, which contributes to reducing the computation time.

- Examples:
  ![img](http://www.ms.k.u-tokyo.ac.jp/software/uLSIF/uLSIF-density1.png) ![img](http://www.ms.k.u-tokyo.ac.jp/software/uLSIF/uLSIF-importance1.png)

  ![img](http://www.ms.k.u-tokyo.ac.jp/software/uLSIF/uLSIF-density2.png) ![img](http://www.ms.k.u-tokyo.ac.jp/software/uLSIF/uLSIF-importance2.png)

- References:

  - Kanamori, T., Hido, S., & Sugiyama, M.
    A least-squares approach to direct importance estimation.
    *[Journal of Machine Learning Research](http://www.jmlr.org/)*, vol.10 (Jul.), pp.1391-1445, 2009.
    [ [paper](http://www.ms.k.u-tokyo.ac.jp/2009/LSIF.pdf) ]
  - Kanamori, T., Hido, S., & Sugiyama, M.
    Efficient direct density ratio estimation for non-stationarity adaptation and outlier detection,
    In D. Koller, D. Schuurmans, Y. Bengio, L. Botton (Eds.), *[Advances in Neural Information Processing Systems 21](http://books.nips.cc/)*, pp.809-816, Cambridge, MA, MIT Press, 2009.
    (Presented at *[Neural Information Processing Systems (NIPS2008)](http://www.nips.cc/)*, Vancouver, B.C., Canada, Dec. 8-13, 2008.)
    [ [paper](http://sugiyama-www.cs.titech.ac.jp/~sugi/2008/NIPS2008.pdf), [poster](http://sugiyama-www.cs.titech.ac.jp/~sugi/2008/NIPS2008-poster.pdf) ]

------