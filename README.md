# scientific-challenges-and-directions

Identifying important challenges and hypothesizing new directions to approach them is at the core of the scientific process. We consider methods that can mine large corpora of papers to automatically identify all problems faced by researchers in specific areas, and hypotheses and future directions that they may consider. We explore the novel task of large-scale extraction and search of scientific challenges and potential directions across biomedical papers, aimed at accelerating scientific discovery. We focus on literature related to the COVID-19 pandemic, constructing and releasing an expert-annotated corpus of texts sampled from full-length COVID-19 papers and labeled for problems and directions with high inter-annotator agreement. We evaluate a range of models on this dataset, and use a scientific language model fine-tuned on our dataset to index challenges and hypotheses from over 500K papers in this area. We build a novel faceted search engine for this information and evaluate its efficacy in user studies, including with MDs who have worked on the front lines of COVID-19. We find that the new search methodology outperforms a widely-used biomedical search system in assisting rapid discovery of challenges and directions in specific areas. Finally, we demonstrate good zero-shot generalization of models trained on our dataset and then applied to biomedical papers in areas extending beyond COVID-19.


# Data
The train, test, and val csvs are on git you can download them from here directly

# Model
You can download the model from here: https://challenges-directions.s3.us-west-2.amazonaws.com/Multilabel_ProblemDirection.pth

# Example notebook
You can look at an example notebook that uses the model for inference on this git, look for Inference_Notebook.ipynb
