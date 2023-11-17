# Progress Updates
I tried to implement some of the methods mentioned in [Inverse molecular design using machine learning: Generative models for matter engineering](https://doi.org/10.1126/science.aat2663) [1]
1. i tried implementing:
    a. [PHOENICS](https://pubs.acs.org/doi/full/10.1021/acscentsci.8b00307) [2] - was able to run it and test it out
    b. [SELFIES](https://pubs.rsc.org/en/content/articlelanding/2023/DD/D3DD00044C) [3] - Molecular graph representations and SELFIES: A 100% robust molecular string representation - Was able to implement it
    c. [ChemVAE](https://arxiv.org/pdf/1610.02415.pdf) [4] - the repo was outdated and had some bugs even after i updated the code, i was then able to implement its equivalent
    d. [MolGAN](https://arxiv.org/abs/1805.11973) [5]- was successfully able to run it through the deepchem package
2. I went through the respective papers
    a. some thoughts were to try newer generative models like diffusion models
    b. try using a GPT like model to generate molecules
    c. Try using Bayesian Flow Networks

[Github Link](https://github.com/shreyasvinaya/Paper-reviews)

## References:
[1] Sanchez-Lengeling B, Aspuru-Guzik A. Inverse molecular design using machine learning: Generative models for matter engineering. Science (New York, N.Y.). 2018 Jul;361(6400):360-365. DOI: 10.1126/science.aat2663. PMID: 30049875.

[2] Hase F, Roch LM, Kreisbeck C, Aspuru-Guzik A. Phoenics: a Bayesian optimizer for chemistry. ACS central science. 2018 Aug 24;4(9):1134-45.

[3] Lo A, Pollice R, Nigam A, White AD, Krenn M, Aspuru-Guzik A. Recent advances in the Self-Referencing Embedding Strings (SELFIES) library. arXiv preprint arXiv:2302.03620. 2023 Feb 7.

[4] Gómez-Bombarelli R, Wei JN, Duvenaud D, Hernández-Lobato JM, Sánchez-Lengeling B, Sheberla D, Aguilera-Iparraguirre J, Hirzel TD, Adams RP, Aspuru-Guzik A. Automatic chemical design using a data-driven continuous representation of molecules. ACS central science. 2018 Feb 28;4(2):268-76.

[5] De Cao, N., & Kipf, T. (2018). MolGAN: An implicit generative model for small molecular graphs. arXiv preprint arXiv:1805.11973.

