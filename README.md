# Learning embeddings for transitive verb phrases

This repository includes the code to learn embeddings for transitive verb phrases using predicate-argument structures presented in our papers [1, 2].
You can reproduce the experimental results reported in our CVSC 2015 paper [2].

The training data used in our paper [2] is publicly available at <a href="http://www.logos.t.u-tokyo.ac.jp/~hassy/publications/cvsc2015/">our web site</a>.
You can put the training data in the <i>train_data</i> directory and run the code to train SVO embeddings.

[1] Kazuma Hashimoto, Pontus Stenetorp, Makoto Miwa, and Yoshimasa Tsuruoka. 2014. <a href="http://www.logos.t.u-tokyo.ac.jp/~hassy/publications/emnlp2014/">Jointly Learning Word Representations and Composition Functions Using Predicate-Argument Structures<a/>. In <i>Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing</i>. pages 1544-1555.

[2] Kazuma Hashimoto and Yoshimasa Tsuruoka. 2015. <a href="http://www.logos.t.u-tokyo.ac.jp/~hassy/publications/cvsc2015/">Learning Embeddings for Transitive Verb Disambiguation by Implicit Tensor Factorization</a>. In <i>Proceedings of the 3rd Workshop on Continuous Vector Space Models and their Compositionality</i>. pages 1-11.

      @InProceedings{hashimoto-EtAl:2014:EMNLP2014,
      author    = {Hashimoto, Kazuma  and  Stenetorp, Pontus  and  Miwa, Makoto  and  Tsuruoka, Yoshimasa},
      title     = {Jointly Learning Word Representations and Composition Functions Using Predicate-Argument Structures},
      booktitle = {Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
      month     = {October},
      year      = {2014},
      address   = {Doha, Qatar},
      publisher = {Association for Computational Linguistics},
      pages     = {1544--1555},
      url       = {http://www.aclweb.org/anthology/D14-1163}
    }

      @InProceedings{hashimoto-tsuruoka:2015:CVSC,
      author    = {Hashimoto, Kazuma  and  Tsuruoka, Yoshimasa},
      title     = {Learning Embeddings for Transitive Verb Disambiguation by Implicit Tensor Factorization},
      booktitle = {Proceedings of the 3rd Workshop on Continuous Vector Space Models and their Compositionality (CVSC)},
      month     = {July},
      year      = {2015},
      address   = {Beijing, China},
      publisher = {Association for Computational Linguistics},
      pages     = {1--11},
      url       = {http://www.aclweb.org/anthology/W15-4001}
    }
