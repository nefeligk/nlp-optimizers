In order to do the tuning run
python tuning.<dataset>.py -o <optim> -m <model> (-lr or -all)

where dataset is one of the following (mnli, mrpc, sst2, stsb, cola)
optim is one of the following (adam, adamw, nadam, adamax, adabound, sgd, sgdm)
choose -lr if you want to tune only learning rate or -all if you want to tune all hyperparameters



In order to train run
python train.<data>.py -o <optim> -m <model> -s <seed>

where dataset is one of the following (mnli, mrpc, sst2, stsb, cola)
optim is one of the following (adam, adamw, nadam, adamax, adabound, sgd, sgdm)
seed is 