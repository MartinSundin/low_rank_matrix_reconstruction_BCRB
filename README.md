low_rank_matrix_reconstruction_BCRB
====

**low_rank_matrix_reconstruction_BCRB** contains the supporting document of the conference paper
> [M. Sundin][masundi], [S. Chatterjee][saikat] and [M. Jansson][mjansson]. "Bayesian Cramér-Rao Bounds for factorized model based low-rank matrix reconstruction". *European Signal Processing Conference (EUSIPCO)*, 2016. The paper is avaliable from [IEEExplore][xplore] and [KTH DIVA][diva].

Please report any typos or errors to <sundin83martin@gmail.com>.

## Abstract
Low-rank matrix reconstruction (LRMR) problem considers
estimation (or reconstruction) of an underlying low-rank matrix
from under-sampled linear measurements. A low-rank
matrix can be represented using a factorized model. In this
article, we derive Bayesian Cramér-Rao bounds (BCRB) for LRMR
where a factorized model is used. We first show a general
informative bound, and then derive several Bayesian Cramér-
Rao bounds for different scenarios. We always considered
the low-rank matrix to be reconstructed as a random matrix,
but its model hyper-parameters for three cases - deterministic
known, deterministic unknown and random. Finally we compare
the bounds with existing practical algorithms through numerical
simulations.

## Description
The pdf document `low_rank_factor_bcrb_supporting_document.pdf` contains the supporting document with derivations and calculations necessary to derive the results in the paper.

## License and referencing
This source code is licensed under the [MIT][mit] license. If you in any way use this code for research that results in publications, please cite our original article. When citing, use the [IEEExplore][xplore] or [Goggle Scholar][scholar] citation, the following [Bibtex][bibtex] entry is a preliminary entry.

```
@INPROCEEDINGS{Sundin2016Bayesian, 
	author={M. Sundin and M. Jansson and S. Chatterjee}, 
	booktitle={Signal Processing Conference (EUSIPCO), 2015 23rd European}, 
	title={Bayesian Cramer-Rao Bounds for factorized model based low-rank matrix reconstruction}, 
	year={2016},
	month={Aug}
}
```

[masundi]: https://www.kth.se/profile/masundi/
[saikat]: https://www.kth.se/profile/sach/
[mjansson]: https://www.kth.se/profile/janssonm/
[mit]: http://choosealicense.com/licenses/mit
[bibtex]: http://www.bibtex.org/
[xplore]: http://ieeexplore.ieee.org/Xplore/home.jsp
[scholar]: https://scholar.google.com/
[diva]: http://kth.diva-portal.org/smash/record.jsf?pid=diva2%3A951514&dswid=-4369
