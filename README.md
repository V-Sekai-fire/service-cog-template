# service-cog-template

A blank model-serving template with empty prediction and training entry points, packaged for the `cog` container tool.

## What it is for

It is the starting point for a new served model: fill in the predictor and the trainer with a model's setup, inputs and outputs, then build and publish the container.

## Building and running

```sh
cog predict
```

`cog predict` builds the container and runs the predictor; `cog train` runs the trainer.

## Licence

MIT. See [LICENSE](LICENSE).
