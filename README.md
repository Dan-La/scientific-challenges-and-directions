# Scientific challenges and directions

We present a novel resource to help scientists and medical professionals discover challenges and potential directions across scientific literature, focusing on a broad corpus pertaining to the COVID-19 pandemic and related historical research. This repository contains models and datasets described in our paper: [A Search Engine for Discovery of Biomedical Challenges and Directions]().

* Please cite our paper if you use our datasets or models in your project. See the [BibTeX](#citation). 
* Feel free to [email us](#contact-us).

## Annotated datasets and model
The train, test, and val csvs are can be downloaded from our repository directly.
You can download a pre-trained model from [here](https://challenges-directions.s3.us-west-2.amazonaws.com/Multilabel_ProblemDirection.pth
). 
## Example notebook
We include an example notebook that uses the model for inference. See `Inference_Notebook.ipynb`.

## Citation

If using our dataset and models, please cite:

```
@misc{lahav2021search,
      title={A Search Engine for Discovery of Biomedical Challenges and Directions}, 
      author={Dan Lahav and Jon Saad Falcon and Bailey Kuehl and Sophie Johnson and Sravanthi Parasa and Noam Shomron and Duen Horng Chau and Diyi Yang and Eric Horvitz and Daniel S. Weld and Tom Hope},
      year={2021},
      eprint={2108.13751},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

## Contact us

Please don't hesitate to reach out.

**Email:** `lahav@mail.tau.ac.il`,`tomh@allenai.org`.
