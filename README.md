# YOLO Toy Gun Model

This repository contains models trained to detect toy guns and knives.

|Filename|Base Model Size|Number of Epochs|Results|Remarks|
|---|---|---|---|---|
|[`yolo-toy-gun-nano-311.pt`](weights/yolo-toy-gun-nano-311.pt)|nano|311|[link](images/yolo-toy-gun-nano-311-results.png)|The training run was setup for 500 epochs but terminated early because the best results were at epoch 311.|
|[`yolo-toy-gun-small-303.pt`](weights/yolo-toy-gun-small-303.pt)|small|303|[link](images/yolo-toy-gun-small-303-results.png)|The training run was setup for 500 epochs but terminated early because the best results were at epoch 303.|
|[`yolo-toy-gun-medium-233.pt`](weights/yolo-toy-gun-medium-233.pt)|medium|233|[link](images/yolo-toy-gun-medium-233-results.png)|The training run was setup for 500 epochs but terminated early because the best results were at epoch 233.|
|[`20240606-nano.pt`](weights/20240606-nano.pt)|nano|500|[link](images/20240606-nano-results.png)|The training dataset was modified to minimize false positives.|
|[`20240606-small.pt`](weights/20240606-small.pt)|small|800|[link](images/20240606-small-results.png)|The training dataset was modified to minimize false positives. The training run was setup for 800 epochs but terminated early because the best results were at epoch 291.|
