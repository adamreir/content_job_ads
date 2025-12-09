
## Repository of Pay and Non-Pay Job Attributes 

This repo contains the full list of pay and non-pay job attributes we extract from the text of a comprehensive data set of Norwegian job postings. The methodology is described in our paper "The Pay and Non-pay Content of Job Ads" [[pdf](https://arxiv.org/pdf/2407.13204)].

### File description

*expressions.csv* gives the full list of expressions associated with the detailed pay and amenity job attributes we retrieve in the paper: 

| Variable               | Description |
| ---------------------- | ----------- |
| aggregate_category     | Aggregate grouping of ad attribute categories. |
| attribute_category     | Detailed attribute categories. 47 detailed categories in total. |
| expression             | Original expressions in Norwegian. 1,772 expressions in total. |
| english_translation    | Mostly from Google Translate. Manually edited for accuracy. |

### License

[Repository of Pay and Non-Pay Job Attributes](https://github.com/raudoly/content_job_ads) by Richard Audoly, Manudeep Bhuller, and Tore Adam Reiremo is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1)

<!-- [Repository of Pay and Non-Pay Job Attributes](https://github.com/raudoly/content_job_ads) by Richard Audoly, Manudeep Bhuller, and Tore Adam Reiremo is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1) ![CC](https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1) ![BY](https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1) -->

### Citation

Please include the following citation if you use this dataset:

```
@misc{audoly2024repo, 
  title = {{Repository of Pay and Non-Pay Job Attributes}}, 
  author = {Audoly, Richard and Bhuller, Manudeep and Reiremo, Tore Adam}, 
  url = {https://github.com/raudoly/content_job_ads},
  doi={https://doi.org/10.5281/zenodo.14973628}, 
  publisher = {[Dataset]}, 
  year = {2024}
}
```

Please cite the following paper to reference the methodology:

```
@article{audoly2024pay,
  title = {The Pay and Non-Pay Content of Job Ads},
  author = {Audoly, Richard and Bhuller, Manudeep and Reiremo, Tore Adam},
  journal = {arXiv preprint arXiv:2407.13204},
  year = {2024}
}
```
