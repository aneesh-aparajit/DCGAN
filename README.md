# DCGAN on Pokémons

If it takes too long to render in GitHub itself, take a look at it @ Kaggle.

- Notebook Link: https://www.kaggle.com/code/aneesh10/dcgan-on-pok-mon-images

- Dataset Link: https://www.kaggle.com/datasets/kvpratama/pokemon-images-dataset

Also consider upvoting!

## Architecture Details

![DCGAN Architecture](./images/dcgan.png)


## Inputs

![Source Images](./images/source-images.png)

## Outputs

### Epoch 0

![Epoch 0 Output](./images/epoch0.png)

### Epoch 20

![Epoch 20 Output](./images/epoch20.png)

### Epoch 50

![Epoch 0 Output](./images/epoch50.png)

### Epoch 100

![Epoch 0 Output](./images/epoch100.png)

## Obersvations

The learning is quite unstable, if we look at the intermediate output on the fixed noise. Also, the model is kind off overfitting with some attributes of a few pokémons. This might be corrected, with some additional regularization. 