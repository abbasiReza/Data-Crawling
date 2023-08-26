# Data Crawling using Text Prompts and Text-to-Image Models
![Histopathology Image Retrieval](sample.jpg)
## Description

This project generates a dataset by creating text prompts and feeding them to text-to-image models to crawl corresponding images.

Text prompts are created by combining adjectives and nouns. These prompts are then passed to a text-to-image model API (e.g. Bing Image Generation) which generates images matching the prompt description. 

The crawled images are downloaded and organized into folders named after the text prompt used to generate them.

This allows creating a custom dataset by leveraging the capabilities of text-to-image models. The dataset can be used for various computer vision tasks.

## Text Prompts  

Text prompts are created by randomly combining adjectives and nouns. For example:

- yellow cat
- tall building
- round clock

This simple technique allows creating a diverse set of textual descriptions to generate images for.

## Text-to-Image Model

The [Bing Image Generation](https://www.bing.com/images/create) is used to generate images from text prompts. The model returns images matching the prompt query which are then downloaded.

Other text-to-image models can also be used.

## Usage

The project contains code to:

- Generate adjective-noun text prompts
- use text-to-image model
- Download images and organize into prompt-named folders 

The output is a dataset with categories based on textual descriptions. 

## References

- [Bing Image Generation model](https://www.bing.com/images/create)
