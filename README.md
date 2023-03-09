# Clinical_History
Collection of scripts used in the conversion of medical record summaries into clinical disease trajectories

# Steps

1. Load and cleaned labeled sentences using explore_input_data.ipynb and labeled_sentences.xlsx (request from authors).
2. Split the data into a test and train/validation set using split_training_data.ipynb.
3. Train NLP models, using either SVC_based.ipynb , BOW_based.ipynb, or transformer_models.ipynb and compare performance metrics.
4. Retrain the best model on the full labeled sentence dataset and predict the full sentence corpus (request from authors) using best_model_full_predictions.ipynb.
5. Using the predicted dataset, create vizualisations to analyse the data, such as dotplots (with dotplots.ipynb) and temporal profile plots (with temporal_profiling.ipynb).


Contact:
n.j.mekkes@umcg.nl
i.r.holtman@umcg.nl
