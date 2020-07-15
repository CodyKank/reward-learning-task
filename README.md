# Experiment Factory Experiment

Hi Friend! This is an Experiment (adopted from [gewimmer-neuro/reward_learning_js](https://github.com/gewimmer-neuro/reward_learning_js/)) that is friendly for use in the [Experiment Factory](https://expfactory.github.io/expfactory). You can run it locally by putting these files in a web server, or use the Experiment Factory to generate a reproducible container. Check out the documentation above for more information, or [post an issue](https://www.github.com/expfactory/expfactory/issues) if you have any questions.

![https://expfactory.github.io/expfactory/img/expfactoryticketyellow.png](https://expfactory.github.io/expfactory/img/expfactoryticketyellow.png)

I (@vsoch) did not create the experiment, but it looks like images (and their corresponding id lookup) are stored under [images](images)
and then listed in [js/list.js](js/list.js)

## Build an Experiment Container

These instructions are also available [here](https://expfactory.github.io/generate#quick-start).

### 1. Create a working directory

```bash
mkdir -p /tmp/reward-learning
cd /tmp/reward-learning
```

### 2. See experiments available

```bash
docker run quay.io/vanessa/expfactory-builder list
```
