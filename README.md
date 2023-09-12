# Overview
This is repository contains the finalized contrastive learning model and self-superised contrastive learning model and associated data for team PixelVision.
Self supervised model was built on Tensorflow and implemented using SimCLR.Google Cloud Services was used to save the the backbones,models, and weights in a Google Cloud Bucket.
Supervised model was built on PyTorch and Implemented using Residual Networks(Resnet-50,Resnet-101).Hyper-parameter tuning was performed using two remote servers,each with two RTX Qudro-5000 GPUs,remote accessing using a SSH tunneling.
Automations were implemented for hyperparameter tuning using bash scripts,and version was saved using git syncs,and model specs were recorded in WanDB account.
