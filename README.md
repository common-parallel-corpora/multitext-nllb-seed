# Multi-text NLLB-Seed
This package turns the original [bi-text nllb-seed dataset](https://github.com/facebookresearch/flores/blob/main/nllb_seed/README.md) into a multi-text dataset by matching the lines of the various eng_Latn reference files with a single [eng_Latn](data/Multitext-NLLB-Seed/eng_Latn) reference file.

The [matching results](data/Multitext-NLLB-Seed/order_files) are used to [re-order](data/Multitext-NLLB-Seed/re_ordered) the original dataset files to produce the [multitext-nllb dataset](data/Multitext-NLLB-Seed/multitext/).

<img src="img/multitext-alignment.jpg" />


## Ackowledgement
This work was done as part of a project supported my Meta Platforms, Inc. and Stanford University.



## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
