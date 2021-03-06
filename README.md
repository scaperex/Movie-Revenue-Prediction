# Movie Revenue Prediction

python code to predict the revenue of movies.

Detailed report can be found under `final_report` file.

To get the code simply clone it - 
`git clone https://github.com/scaperex/Movie-Revenue-Prediction.git`

Then, to setup the environment - 
- `cd Movie-Revenue-Prediction`
- `conda env create -f environment.yml`

Activate it by -
`conda activate movie_revenue`

Finally, to evaluate the pretrained model simply run 
`python predict.py <data_path.tsv>`.

Additionally, the code consists of -
 - Applying and saving the data preprocessing steps  -
`python preprocessing.py`. This will save the processed data as 
a np.array.
- Model selection process is by `model.py`.
- Different parameters are given by `config.py`.
- To retrain the model with the best configuration that we got run `best_model_template.py`

Note, the data is expected to be given in the same format as used for training.


