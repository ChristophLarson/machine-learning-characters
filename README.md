# Hand-written digit classifier

Rohan Kadkol (rkadko1)<br>
Christoph Larson (clarso5)

## Installing dependencies

We can first install the required dependencies using the below command:

```bash
pip install -r requirements.txt
```

## Sample data from the dataset

<img src="images/sample_0.png">
<img src="images/sample_1.png">
<img src="images/sample_2.png">
<img src="images/sample_3.png">
<img src="images/sample_4.png">

## How to run code

We submitted our code as a Jupyter notebook with markdown cell explanations.

We can then run each cell to get the expected output.

<hr>

Running the `grid_search_cv()` method (`Complete Dataset Version`) is extremely time consuming. This is because it has to run 5 folds, where each fold runs on 5 epochs, where each epoch has 60,000 images.

To show a quick running of our code, we also included a `Smaller Subset Version` with just 1,000 images, instead of 60,000.