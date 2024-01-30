
python 3.10
make environment
pip install -r requirements.txt



TUNING
In order to do the tuning run:
python tuning.<dataset>.py -o <optim> -m <model> (-lr or -all)

<dataset> is one of the following (mnli, mrpc, sst2, stsb, cola)
<optim> is one of the following (adam, adamw, nadam, adamax, adabound, sgd, sgdm)
choose -lr if you want to tune only learning rate or -all if you want to tune all hyperparameters



TRAIN
In order to train run:
python train.<data>.py -o <optim> -m <model> -s <seed>

<dataset> is one of the following (mnli, mrpc, sst2, stsb, cola)
<optim> is one of the following (adam, adamw, nadam, adamax, adabound, sgd, sgdm)
<seed> is the seed for splitting the dataset to train/validation/test 