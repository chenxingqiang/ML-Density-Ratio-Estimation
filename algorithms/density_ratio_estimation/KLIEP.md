# Kullback-Leibler Importance Estimation Procedure (KLIEP)

- *Kullback-Leibler Importance Estimation Procedure (KLIEP)* is an algorithm to directly estimate the ratio of two density functions without going through density estimation. The optimization problem involved with KLIEP is convex so the unique global optimal solution can be obtained. Furthermore, the KLIEP solution tends to be sparse, which contributes to reducing the computation time.

  - "KLIEP.m" is the main function.
  - "demo_KLIEP.m" is a demo script.

- Examples:
  ![img](http://www.ms.k.u-tokyo.ac.jp/software/KLIEP/KLIEP-density1.png) ![img](http://www.ms.k.u-tokyo.ac.jp/software/KLIEP/KLIEP-importance1.png)

  ![img](http://www.ms.k.u-tokyo.ac.jp/software/KLIEP/KLIEP-density2.png) ![img](http://www.ms.k.u-tokyo.ac.jp/software/KLIEP/KLIEP-importance2.png)

- References:

  - Sugiyama, M., Suzuki, T., Nakajima, S., Kashima, H., von Bünau, P. & Kawanabe, M.
    Direct importance estimation for covariate shift adaptation.
    *[Annals of the Institute of Statistical Mathematics](http://www.ism.ac.jp/editsec/aism-e.html)*, vol.60, no.4, pp.699-746, 2008.
    [ [paper](http://www.ms.k.u-tokyo.ac.jp/2008/KLIEP.pdf) ]
  - Sugiyama, M., Nakajima, S., Kashima, H., von Bünau, P. & Kawanabe, M.
    Direct importance estimation with model selection and its application to covariate shift adaptation.
    In J. C. Platt, D. Koller, Y. Singer, and S. Roweis (Eds.), *[Advances in Neural Information Processing Systems 20](http://books.nips.cc/)*, pp.1433-1440, Cambridge, MA, MIT Press, 2008.
    (Presented at *[Neural Information Processing Systems (NIPS2007)](http://www.nips.cc/)*, Vancouver, B.C., Canada, Dec. 3-8, 2007.)
    [ [paper](http://www.ms.k.u-tokyo.ac.jp/2007/NIPS2007a.pdf), [poster](http://www.ms.k.u-tokyo.ac.jp/2007/NIPS2007a-poster.pdf) ]