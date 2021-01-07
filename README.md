

# OUTLOOK

- NAME： Density Ratio Estimation in Machine Learning

- SOURCE： http://www.ms.k.u-tokyo.ac.jp/software.html

- AIM： We aim at reproduce the density ratio estimation algorithms in this book: *Density Ratio Estimation in Machine Learning*





## Fundamentals

- Density ratio estimation
  - KLIEP (Kullback-Leibler importance estimation procedure): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#KLIEP)
  - GM-KLIEP (Gaussian-mixture KLIEP): [MATLAB (by Makoto Yamada)](http://www.makotoyamada-ml.com/gmkliep.html)
  - LSIF (least-squares importance fitting): [R (by Takafumi Kanamori)](http://www.math.cm.is.nagoya-u.ac.jp/~kanamori/software/LSIF/)
  - uLSIF (unconstrained LSIF): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#uLSIF), [R (by Takafumi Kanamori)](http://www.math.cm.is.nagoya-u.ac.jp/~kanamori/software/LSIF/), [C++ (by Issei Sato)](http://www.r.dl.itc.u-tokyo.ac.jp/~sato/uLSIF/)
  - RuLSIF (relative uLSIF): [MATLAB (by Makoto Yamada)](http://www.makotoyamada-ml.com/RuLSIF.html), [R (by Max Wornowizki)](https://www.statistik.tu-dortmund.de/~wornowiz/RuLSIF.txt), [Python (by Song Liu)](http://www.ism.ac.jp/~liu/RuLSIF.html)
- Density difference estimation
  - LSDD (least-squares density difference): [MATLAB, Python (by Marthinus Christoffel du Plessis)](http://www.ms.k.u-tokyo.ac.jp/software.html#LSDD)
- Density derivative estimation
  - LSLDG (least-squares log-density gradient): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#LSLDG) (by Hiroaki Sasaki)
- Mutual information estimation
  - MLMI (maximum-likelihood mutual information): [MATLAB (with Taiji Suzuki)](http://www.ms.k.u-tokyo.ac.jp/software.html#MLMI)
  - LSMI (least-squares mutual information): [MATLAB (with Taiji Suzuki)](http://www.ms.k.u-tokyo.ac.jp/software.html#LSMI)
  - LSMI (multiplicative kernel model): [MATLAB (by Tomoya Sakai)](http://www.ms.k.u-tokyo.ac.jp/software.html#LSMI)
  - LSQMI (least-squares quadratic mutual information): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#LSQMI)
- Hetero-distributional subspace search
  - LHSS (least-squares hetero-distributional search): [MATLAB (with Makoto Yamada)](http://www.ms.k.u-tokyo.ac.jp/software.html#LHSS)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Applications

- Covariate shift adaptation
  - IWLS+IWCV+uLSIF (importance-weighted least-squares + importance-weighted cross-validation + unconstrained least-squares importance fitting): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#IWLS)
  - IWLR+KLIEP (importance-weighted logistic regression + Kullback-Leibler importance estimation procedure): [MATLAB (by Makoto Yamada)](http://www.makotoyamada-ml.com/iwklr.html)
  - IWLSPC+IWCV+KLIEP (importance-weighted least-squares probabilistic classifier + importance-weighted cross-validation + Kullback-Leibler importance estimation procedure): [MATLAB (by Hirotaka Hachiya)](http://www.ms.k.u-tokyo.ac.jp/software.html#IWLSPC)
- Class prior change adaptation
  - uLSIF-based method: [MATLAB (by Marthinus Christoffel du Plessis)](http://sugiyama-www.cs.titech.ac.jp/~christo/pages/software-page.html)
  - LSDD-based method: [MATLAB (by Marthinus Christoffel du Plessis)](http://sugiyama-www.cs.titech.ac.jp/~christo/pages/software-page.html)
- Inlier-based outlier detection
  - MLOD (maximum-likelihood outlier detection): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#MLOD)
  - LSOD (least-squares outlier detection): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#LSOD)
  - LSAD (least-squares anomaly detection): [Python (by John Quinn)](http://cit.mak.ac.ug/staff/jquinn/software/lsanomaly.html)
- Feature selection
  - MLFS (maximum-likelihood feature selection in supervised regression/classification): [MATLAB (with Taiji Suzuki)](http://www.ms.k.u-tokyo.ac.jp/software.html#MLFS)
  - LSFS (least-squares feature selection in supervised regression/classification): [MATLAB (with Taiji Suzuki)](http://www.ms.k.u-tokyo.ac.jp/software.html#LSFS)
  - L1-LSMI (L1-LSMI-based feature selection for supervised regression/classification): [MATLAB (by Wittawat Jitkrittum)](http://wittawat.com/pages/l1lsmi.html)
  - HSIC-LASSO (Hilbert-Schmidt independence criterion + least absolute shrinkage and selection operator for high-dimensional feature selection in supervised regression/classification): [MATLAB (by Makoto Yamada)](http://www.makotoyamada-ml.com/hsiclasso.html)
- Dimensionality reduction/feature extraction/metric learning
  - NGCA (non-Gaussian component analysis, unsupervised linear dimensionality reduction): [MATLAB (by Gilles Blanchard)](http://users.math.uni-potsdam.de/~blanchard/software/NGCA_demo.tgz)
  - LSDR (least-squares dimensionality reduction, supervised linear dimensionality reduction for regression/classification): [MATLAB (with Taiji Suzuki)](http://www.ms.k.u-tokyo.ac.jp/software.html#LSDR)
  - SCA (sufficient component analysis, supervised linear dimensionality reduction for regression/classification): [MATLAB (by Makoto Yamada)](http://www.makotoyamada-ml.com/sca.html)
  - LSQMID (least-squares quadratic mutual information derivative, supervised linear dimensionality reduction for regression/classification): [MATLAB (by Voot Tangkaratt)](http://www.ms.k.u-tokyo.ac.jp/software.html#LSQMID)
  - LFDA (local Fisher discriminant analysis, supervised linear dimensionality reduction for classification): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#LFDA)
  - SELF (semi-supervised LFDA, semi-supervised linear dimensionality reduction for classification): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#SELF)
  - LSCDA (least-squares canonical dependency analysis, linear dimensionality reduction for paired data): [MATLAB (by Masayuki Karasuyama)](http://www.bic.kyoto-u.ac.jp/pathway/krsym/software/LSCDA/index.html)
  - SERAPH (semi-supervised metric learning paradigm with hyper-sparsity, semi-supervised metric learning for classification): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software/SERAPH.zip) (by Gang Niu)
- Classification
  - PU classification (learning from positive and unlabeled data): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#PU) (by Tomoya Sakai)
  - PNU classification (semi-supervised learning based on PU classification): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#PNU) (by Tomoya Sakai)
- Conditinonal probability estimation
  - LSCDE (least-squares conditional density estimation): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#LSCDE)
  - LSPC (least-squares probabilitic classifier): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#LSPC), [Python (by John Quinn)](http://cit.mak.ac.ug/staff/jquinn/software/lspc.html)
  - SMIR (squared-loss mutual information regularization, semi-supervised probabilistic classification): [MATLAB (by Gang Niu and by Wittawat Jitkrittum)](http://www.ms.k.u-tokyo.ac.jp/software/SMIR.zip)
- Independence test
  - LSIT (least-squares independence test): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#LSIT)
- Two-sample test
  - LSTT (least-squares two-sample test): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#LSTT)
- Change detection
  - CD-RuLSIF (distributional change detection by RuLSIF): [MATLAB (by Song Liu)](http://www.ism.ac.jp/~liu/software.html)
  - CD-KLIEP (structural change detection by sparse KLIEP): [MATLAB (by Song Liu)](http://www.ism.ac.jp/~liu/software.html)
- Clustering
  - SMIC (clustering based on maximization of squared-loss mutual information): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#SMIC)
  - MVC (clustering based on maximization of volume): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software/MVC.zip) (by Gang Niu)
  - LSLDG (clustering based on least-squares log-density gradient): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#LSLDG) (by Hiroaki Sasaki)
- Independent component analysis
  - LICA (independent component analysis): [MATLAB (by Taiji Suzuki)](http://www.is.titech.ac.jp/~s-taiji/software/LICA/index.html)
- Causal direction inference
  - LSIR (least-squares independence regression): [MATLAB (by Makoto Yamada)](http://www.makotoyamada-ml.com/lsir.html)
- Cross-domain object matching
  - LSOM (least-squares object matching): [MATLAB (by Makoto Yamada)](http://www.makotoyamada-ml.com/lsom.html)
- Hidden Markov Model
  - DRHMM (density-ratio hidden Markov model): [MATLAB and Python (by John Quinn)](http://cit.mak.ac.ug/staff/jquinn/software/densityratioHMM.html)
- Sparse learning
  - DAL (l1/grouped-l1/trace-norm regularization solver): [MATLAB (by Ryota Tomioka)](http://ttic.uchicago.edu/~ryotat/softwares/dal/)
- Matrix/tensor factorization
  - VBMF (variational Bayesian matrix factorization): [MATLAB](http://www.ms.k.u-tokyo.ac.jp/software.html#VBMF)
  - Multitask learning with tensor factorization: [MATLAB (by Kishan Wimalawarne)](http://kishan-wimalawarne.com/software.html#nips2014)
- Reinforcement learning
  - IW-PGPE-OB (model-free policy gradient method with sample reuse): [MATLAB](https://sites.google.com/site/tingtingzhao1986phd/)
- Crowdsourcing
  - BBTA (bandit-based task assignment): [Python (by Hao Zhang)](https://github.com/justhao/bbta)