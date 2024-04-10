## Bedrock Model Customization Workshop Notebooks

This repository contains the notebooks for the [Bedrock Model Customization Workshop](https://aws.amazon.com/bedrock/).

This repository contains the notebooks and resources for the workshop, designed to give you hands-on experience in customizing foundation models (FMs) using Amazon Bedrock.

Amazon Bedrock is a fully managed service that provides access to FMs from third-party providers and Amazon, available via an API. Model customization involves providing training data to a model to improve its performance for specific use cases, enhancing the customer experience.

Amazon Bedrock offers the following customization methods:

### Continued Pre-training
Continued pre-training involves providing unlabeled data to a foundation model to familiarize it with specific types of inputs, improving its domain knowledge. This process adjusts the model parameters based on the input data, enhancing its performance. For example, you can train a model with private business documents that are not publicly available, continuously improving the model by retraining it with more unlabeled data as it becomes available.

### Fine-tuning
Fine-tuning entails providing labeled data to train a model for improved performance on specific tasks. By providing a training dataset of labeled examples, the model learns to associate types of outputs with certain inputs, leading to improved performance for the represented tasks.

Throughout this workshop, you'll explore common usage patterns for creating custom models using Amazon Bedrock. You'll gain hands-on experience using Bedrock from the AWS console, interacting with it via SDKs from Jupyter Notebooks, running customization training jobs, creating provisioned throughputs for hosting, deploying custom models, and interacting with the deployed models.

This workshop is intended for developers and solution builders.

Please refer to these [Step-by-step guided instructions on the workshop website](https://catalog.us-east-1.prod.workshops.aws/workshops/a4bdb007-5600-4368-81c5-ff5b4154f518/en-US) to get started.


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

