# Dreambooth Class Images

For regularization when [training dreambooth models](https://github.com/huggingface/notebooks/blob/main/diffusers/sd_dreambooth_training.ipynb).

## a photo of a person

**Class prompt**: a photo of a person\
**Image size**: 512 x 512\
**Num images**: 1500\
**Generation model**: runwayml/stable-diffusion-v1-5\
**Pipeline**: StableDiffusionPipeline\
**Pipeline args**: revision="fp16", torch_dtype=torch.float16

## photo of a cat

**Class prompt**: photo of a cat\
**Image size**: 512 x 512\
**Num images**: 1500\
**Generation model**: runwayml/stable-diffusion-v1-5\
**Pipeline**: StableDiffusionPipeline\
**Pipeline args**: revision="fp16", torch_dtype=torch.float16

## dune lanescape

**Class prompt**: dune landscape\
**Image size**: 512 x 512\
**Num images**: 1500\
**Generation model**: stabilityai/stable-diffusion-2-1-base\
**Pipeline**: StableDiffusionPipeline\
**Pipeline args**: revision="fp16", torch_dtype=torch.float16\
**Note:** Used for moon/mars models
