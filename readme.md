
## Pay and Non-pay Content of Job Ads

This repo contains the full list of pay and non-pay job attributes we extract from the text of a comprehensive data set of Norwegian job postings. The methodology is described in our paper "The Pay and Non-pay Content of Job Ads" [[pdf](https://arxiv.org/pdf/2407.13204)].

### File description

*expressions.csv* gives the full list of expressions associated with the detailed pay and amenity job attributes we retrieve in the paper: 

| Variable               | Description |
| ---------------------- | ----------- |
| aggregate_category     | Aggregate grouping of ad attribute categories. |
| attribute_category     | Detailed attribute categories. 47 detailed categories in total. |
| expression             | Original expressions in Norwegian. 1,772 expressions in total. |
| english_translation    | Initially from Google Translate. Manually edited for accuracy. |

### Citation

If you find this research helpful, please consider citing the following paper:

```
@article{audoly2024pay,
  title={The Pay and Non-Pay Content of Job Ads},
  author={Audoly, Richard and Bhuller, Manudeep and Reiremo, Tore Adam},
  journal={arXiv preprint arXiv:2407.13204},
  year={2024}
}
```
