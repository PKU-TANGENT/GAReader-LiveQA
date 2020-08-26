# Gated Attention Reader Baseline for LiveQA

LiveQA: A Question Answering Dataset over Sports Live. The Nineteenth China National Conference on Computational Linguistics, CCL 2020.

The data in this repo has already been selected from the original timeline.

Forked from Code for the paper: [RACE: Large-scale ReAding Comprehension Dataset From Examination](https://arxiv.org/pdf/1704.04683.pdf). Guokun Lai*, Qizhe Xie*, Hanxiao Liu, Yiming Yang and Eduard Hovy. EMNLP 2017


## Dependencies
* Python 2.7
* Theano >= 0.7
* Lasagne 0.2.dev1

## Datasets
* LiveQA:
raw data could be found [here](https://github.com/PKU-TANGENT/LiveQA)

## Usage
### Preprocessing
    * python preprocess.py

### Stanford AR
    * test pre-trained model: bash test_SAR.sh
    * train: bash train_SAR.sh (The pre-trained model will be replaced)

### GA
    * test pre-trained model: bash test_GA.sh
    * train: bash train_GA.sh (The pre-trained model will be replaced)


## Acknowledgement
* The code is adapted from Stanford AR https://github.com/danqi/rc-cnn-dailymail and GA https://github.com/bdhingra/ga-reader


## License
MIT
