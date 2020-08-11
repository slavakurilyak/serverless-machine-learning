# Serverless Machine Learning

## About

*Serverless Machine Learning* helps ML practioners deploy ML models into production without managing servers.

*Serverless Machine Learning* uses [serverless framework](http://serverless.com/) and [serverless-python-requirements](https://github.com/UnitedIncome/serverless-python-requirements/) (serverless plugin) to deploy ML models onto [AWS](https://aws.amazon.com/) using serverless architectures (i.e. [AWS Lambda](https://aws.amazon.com/lambda/)).

## ML Models

*Serverless Machine Learning* implements the following ML models:

1. [Serverless Tensorflow](serverless-tensorflow)
2. Serverless [Keras](https://keras.io/) (coming soon)
3. Serverless [Transformers](https://github.com/huggingface/transformers) (coming soon)

## Usage

To use *Serverless Machine Learning*, complete the following steps:

1. Install [Serverless Framework](http://serverless.com/). To get started, refer to official [docs](https://www.serverless.com/framework/docs/) 
2. Setup AWS IAM Permissions. To get started, read: [The ABCs of IAM: Managing permissions with Serverless](https://www.serverless.com/blog/abcs-of-iam-permissions)

## Provider Support

1. [AWS](https://aws.amazon.com/)
2. [GCP](https://cloud.google.com/) (coming soon)
3. [Cloudflare Workers](https://workers.cloudflare.com/) (coming soon)

## Runtime Support

1. [Python 3.7](https://docs.python.org/3.7/) (release date: June 27, 2018)
2. [Python 3.8](https://docs.python.org/3.8/) (coming soon)