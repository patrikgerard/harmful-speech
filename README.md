# harmful-speech
The full analysis is contained in:

- `harmful_speech_analysis_REPRODUCIBLE.ipynb`

## Data

The notebook expects:

- `harmful_speech_annotations/` — corpus-scale annotation TSVs
- `broken_up_df/filtered_clustered_df_classified_part_*.parquet` — source corpus shards and metadata
- `llm_validation_results/qwen3_14b_predictions.csv` — Qwen3-14B validation predictions

Update the data paths in the notebook's **Configuration** section before running.

Run the notebook from top to bottom to reproduce the analyses, tables, figures, and output files used in the paper.
