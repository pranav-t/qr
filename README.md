# Quantile Regression
* Training data and predictions under data/
* Code in qr.ipynb

## How to run
### Setup
1. $ git clone https://github.com/pranav-t/qr.git
2. $ cd qr
3. $ virtualenv -p python3.6 venv
4. $ python3.6 -m  pip install -r requirements.txt
5. $ jupyter lab
6. $ ctrl+c to exit

### Run
1. Add training data as csv (x,y) under data/
2. Set `input_filename` in code under the Training section.
3. Open qr.ipynb
4. (Optional) select `QUANTILE_TO_VISUAIZE` between \[0.1, 0.99\] under the Visualization section.
5. Run > Run all cells
6. Predictions are available at **data/input_filename_predictions.csv** and **data/input_filename_predictions_pivoted.csv**
