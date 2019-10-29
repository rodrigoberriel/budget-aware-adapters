## Budget-Aware Adapters for Multi-Domain Learning

Code for the [ICCV'19](http://openaccess.thecvf.com/ICCV2019.py) paper "[Budget-Aware Adapters for Multi-Domain Learning](http://openaccess.thecvf.com/content_ICCV_2019/papers/Berriel_Budget-Aware_Adapters_for_Multi-Domain_Learning_ICCV_2019_paper.pdf)"

[Rodrigo Berriel](http://rodrigoberriel.com), [Stéphane Lathuilière](http://stelat.eu/), [Moin Nabi](https://moinnabi.github.io/), [Tassilo Klein](https://scholar.google.com/citations?user=z7-L4ywAAAAJ&hl=en), [Thiago Oliveira-Santos](http://www.inf.ufes.br/~todsantos/home), [Nicu Sebe](http://disi.unitn.it/~sebe/), [Elisa Ricci](http://elisaricci.eu/)

[![Paper Thumbnail](https://github.com/rodrigoberriel/budget-aware-adapters/blob/master/images/paper.jpg)](https://arxiv.org/abs/1905.06242)

Multi-Domain Learning (MDL) refers to the problem of learning a set of models derived from a common deep architecture, each one specialized to perform a task in a certain domain (e.g., photos, sketches, paintings). This paper tackles MDL with a particular interest in obtaining domain-specific models with an adjustable budget in terms of the number of network parameters and computational complexity. Our intuition is that, as in real applications the number of domains and tasks can be very large, an effective MDL approach should not only focus on accuracy but also on having as few parameters as possible. To implement this idea we derive specialized deep models for each domain by adapting a pre-trained architecture but, differently from other methods, we propose a novel strategy to automatically adjust the computational complexity of the network. To this aim, we introduce Budget-Aware Adapters that select the most relevant feature channels to better handle data from a novel domain. Some constraints on the number of active switches are imposed in order to obtain a network respecting the desired complexity budget. Experimentally, we show that our approach leads to recognition accuracy competitive with state-of-the-art approaches but with much lighter networks both in terms of storage and computation.

![Figures](https://github.com/rodrigoberriel/budget-aware-adapters/blob/master/images/thumbnail.jpg)


#### Questions?

If you have questions, send me an e-mail or open an issue.

The code will be released soon. Subscribe to [this issue](https://github.com/rodrigoberriel/budget-aware-adapters/issues/1) if you want to be notified.


#### BibTeX

If you find this useful, consider citing:

    @InProceedings{berriel2019iccv,
      author    = {Rodrigo Berriel
                   and St'{e}phane Lathuili`{e}re
                   and Moin Nabi
                   and Tassilo Klein
                   and Thiago Oliveira-Santos
                   and Nicu Sebe
                   and Elisa Ricci},
      title     = {{Budget-Aware Adapters for Multi-Domain Learning}},
      booktitle = {The IEEE International Conference on Computer Vision (ICCV)},
      year      = {2019}
    }