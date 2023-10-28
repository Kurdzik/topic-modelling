# topic_modelling_kedro

## How to install dependencies

Declare any dependencies in `src/requirements.txt` for `pip` installation and `src/environment.yml` for `conda` installation.

To install them, run:

```
pip install -r src/requirements.txt
```

## How to run your Kedro pipeline

You can run your Kedro project with:

```
kedro run                       collects articles and splits them into topics
kedro run -p get_articles       collects articles and saves them as cvs in data/01_raw folder
kedro run -p run_model          performs topic modelling on gathered articles and saves output to data/07_model_output folder
```

## How to visualize pipeline

run:

`kedro viz`
