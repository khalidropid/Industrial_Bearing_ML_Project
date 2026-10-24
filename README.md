# Industrial Bearing Fault Diagnosis

Machine-learning project for industrial bearing fault classification and unknown-fault experiments using the Case Western Reserve University (CWRU) bearing dataset.

## Project overview

The project processes vibration signals, extracts engineered features, trains and evaluates a fault classifier, and includes experiments focused on generalization across bearing recordings and detection of an unseen fault category.

## Fault classes

- `ball`
- `inner_race`
- `outer_race`

## Data

The source dataset is not included in this repository. Obtain the CWRU dataset separately and configure the project paths according to the notebook's instructions. Do not commit raw datasets, personal access tokens, credentials, or large generated files.

## Running the notebook

1. Open the notebook in Google Colab.
2. Mount Google Drive if the project files are stored there.
3. Download the CWRU data separately.
4. Update data and project paths to match your environment.
5. Run notebook cells in order.

## Results and interpretation

Record evaluation results alongside the evaluation protocol used. Metrics from a particular file set should not be presented as evidence of performance on unseen recordings unless that set was excluded from model training.

## License

No license has been specified yet.