# eBiota
<i>Ab initio</i> design of microbial communities from large-scale seed pools using deep learning and rapid optimization


## Abstract
----
Many biotechnological applications rely on microbial communities. Designing optimal microbial communities from seed pools can be guided by genomic information. However, the cost of designing communities increases exponentially as the size of the seed pool grows. Furthermore, assembled microbial communities often suffer from instability. Here, we introduce eBiota, a tool for ab initio designing microbial communities from a pool of 21,514 strains. eBiota uses CoreBFS, a graph-based search method, and ProdFBA, an extension of classical flux balance analysis, to rapidly identify microbial communities optimized for a target function. The communities are potentially stable by design thanks to DeepCooc, a deep learning algorithm that recognizes co-occurrence patterns from 23,323 samples across environments. We demonstrate the capabilities of eBiota using public microbial communities, ranging from single strain to six members. Our in vitro culture experiments, involving 94 strains, further validate eBiota’s ability by selecting species that prevent pathogen growth and by conducting large microbial communities. Finally, eBiota offers scalable community predictions for a broad range of biotechnological applications.

![Fig. 1](https://github.com/LoryJiang/eBiota/blob/main/Fig.%201.png)

## Others
----
More codes, results and media are available at Github (https://github.com/allons42/eBiota) and Zenodo (https://zenodo.org/records/13895108). Sequencing data of 94 bacterial strains and R. solanacearum QL-Rs1115 have been deposited in Zenodo (https://zenodo.org/records/13764123). Raw sequencing data of the 25 in vitro culture samples are available at the National Center for Biotechnology Information database (accession number: PRJNA1163256).

## Citation:
----
<i>Ab initio</i> design of microbial communities from large-scale seed pools using deep learning and rapid optimization

## Contact:
----
If there are any problems, feel free to raise issues or ask us: jiangxiaoqing357@126.com, jhhou@pku.edu.cn, haoserzhang7733@gmail.com or hqzhu@pku.edu.cn.
