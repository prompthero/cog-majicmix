# Dreamshaper Cog for Replicate API

Model: [Dreamshaper](https://prompthero.com/ai-models/dreamshaper-download)

Author: [@prompthero](prompthero.com)

## Instructions

---

First, `git clone` this repo and cd into it:

```
git clone https://github.com/prompthero/cog-majicmix

cd cog-majicmix
```

### Install cog:

```
curl https://replicate.github.io/codespaces/scripts/install-cog.sh | bash
```

### Try to run a prediction:

```
sudo cog run script/download-weights
```

### Download the weights:

```
sudo cog predict -i prompt="monkey scuba diving"
```

### Create a model in Replicate:

### Publish your model

```
cog login
cog push r8.im/<your-username>/<your-model-name>
```
