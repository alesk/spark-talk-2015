# Spark talk
Slides and code for the Spark talk given at [JavaSi'15](http://java.sioug.si/).
## Slides
The slides are created with [slidify](http://slidify.org/) and can be viewed with browser at [http://alesk.github.io/spark-talk-2015](http://alesk.github.io/spark-talk-2015).
## Code
### Dataset
Dataset is taken from [MovieLens.org](http://grouplens.org/datasets/movielens/). Use [ml-latest-small.zip](http://files.grouplens.org/datasets/movielens/ml-latest-small.zip) for start and unzip it to `data` folder:

```bash
curl http://files.grouplens.org/datasets/movielens/ml-latest-small.zip -O data/ml-latest-small.zip
cd data; unzip ml-latest-small.zip; cd ..
```

When you're ready to process the whole dataset, repeat the steps for [ml-latest.zip](http://files.grouplens.org/datasets/movielens/ml-latest.zip) and change `dataDir` to `ml-latest`.

### Spark-notebook
Download/clone [spark-notebook](https://github.com/andypetrella/spark-notebook) and use it's `bin/spark-notebook` to run spark environment like:

```bash
<SPARK-NOTEBOOK-INSTALLATION-DIR>/bin/spark-notebook -Dconfig.file=application.conf
```
Point your browser to your `localhost:9000` [Movie Recomendations Notebook](http://localhost:9000/notebooks/Movie%20Recomendation.snb).

See [fully rendered notebook](http://alesk.github.io/spark-talk-2015/movie-recommendation.pdf).
