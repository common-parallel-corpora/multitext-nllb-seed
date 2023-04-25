# multi-text nllb-seed
This package provides a multi-text version of the original [bi-text nllb-seed dataset](https://github.com/facebookresearch/flores/blob/main/nllb_seed/README.md). It contains:
- A manually created consensus [eng_Latn](data/Multitext-NLLB-Seed/eng_Latn) reference file.
- [order_files](data/Multitext-NLLB-Seed/order_files) matching the lines of each original data and the new eng_Latn reference.
- [re-ordered](data/Multitext-NLLB-Seed/re_ordered) bitext data files
- The resulting [multitext](data/Multitext-NLLB-Seed/multitext/) nllb-seed dataset



<img src="img/multitext-alignment.jpg" />


## Ackowledgement
This work was done as part of a project supported by Meta Platforms, Inc. and Stanford University.



## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
