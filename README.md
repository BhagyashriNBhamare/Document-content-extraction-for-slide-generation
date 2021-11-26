# Document-content-extraction-for-slide-generation


## Development

Some other information pertaining to the project are:


```sh
CUDA_VISIBLE_DEVICES=0 python3 batch_train.py
```

To test the model, run:

```sh
$CUDA_VISIBLE_DEVICES=2 python3 batch_test.py
```

To evaluate the results, run:

```sh
python3 evaluateROUGE155.
```
## Result
Model is saved in following folder.

```sh
runs/
```
slide genrated by system and human are stored in following folder
```sh
temp/
```
