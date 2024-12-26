# answerdotai/ModernBERT-baseCog model

This is an implementation of [answerdotai/ModernBERT-base](https://huggingface.co/answerdotai/ModernBERT-base) as a [Cog](https://github.com/replicate/cog) model.

## Development

Follow the [model pushing guide](https://replicate.com/docs/guides/push-a-model) to push your own model to [Replicate](https://replicate.com).

Download the weights with the command:

    huggingface-cli download answerdotai/ModernBERT-base --local-dir checkpoints

## Basic Usage

To run a safe user prediction:

    cog predict -i prompt="Replicate lets you run machine learning [MASK] with a cloud API."

Output

    applications