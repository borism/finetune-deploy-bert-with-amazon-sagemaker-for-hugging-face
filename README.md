# Finetuning Hugging Face DistilBERT with IMDB dataset.

In this demo, we will use the Hugging Faces `transformers` and `datasets` library with Amazon SageMaker to fine-tune a pre-trained transformer on binary text classification. In particular, we will use the pre-trained DistilBERT model with the IMDB dataset.
We will then deploy the resulting model for inference using SageMaker Serverless Endpoint.

We'll be using an offshoot of [BERT](https://arxiv.org/abs/1810.04805) called [DistilBERT](https://arxiv.org/abs/1910.01108) that is smaller, and so faster and cheaper for both training and inference. A pre-trained model is available in the [`transformers`](https://huggingface.co/transformers/) library from [Hugging Face](https://huggingface.co/).

The IMDB is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. It provides a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well. It's avalaible under the [`IMDB`](https://huggingface.co/datasets/imdb) dataset on [Hugging Face](https://huggingface.co/).

## Security
See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License
This library is licensed under the MIT-0 License. See the LICENSE file.
