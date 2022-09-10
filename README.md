# UCL-MSc-Project

`retrieval_pipeline` is the main inference script. The rest are for training modified EPR and FPR.

To train modified EPR `get_candidate_examples_index` -> `scoring_single` -> `retriever_training_mepr`

To train FPR individual `get_candidate_examples_index` -> `scoring_single` -> `retriever_training_fpr_individual`

To train FPR pairwise `get_candidate_examples_index` -> `scoring_pair` -> `retriever_training_fpr_pairwise`

Adjust the paths to data and models accordingly
