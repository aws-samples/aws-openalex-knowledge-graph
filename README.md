## EDA & Knowledge Graph with OpenAlex dataset and SageMaker Studio Lab (SMSL)

A Jupyter Notebook that connects to the Registry of Open Data on AWS to show exploratory data analysis and knowledge graph.

Dataset used:

- OpenAlex: https://registry.opendata.aws/openalex/

## AWS SageMaker Studio Lab

You can sign up for SageMaker Studio Lab and use it for free without an AWS account. You can run for 4 hours with GPU or 12 hours with CPU and then logout and log back in for another session. Your data and notebooks are persisted. After clicking the launch button below, choose "download whole repo".

When it's done installing and configuring the environment, open the .ipynb notebook file. Click-Enter to run each row and wait a moment to see the results of each line before proceeding to the next. The line marker should change to a number when it's successfully run that line, ie "[5]" means that it has run line 5.

<a href="https://studiolab.sagemaker.aws/import/github.com/aws-samples/aws-openalex-knowledge-graph/blob/main/eda-knowledge-graph-with-openalex-dataset.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/8c5378ff3bf6f71a57442940234293bd63c7ed2418d64f74f2bda3dc6f2904ed/68747470733a2f2f73747564696f6c61622e736167656d616b65722e6177732f73747564696f6c61622e737667" alt="Open In SageMaker Studio Lab" data-canonical-src="https://studiolab.sagemaker.aws/studiolab.svg" style="max-width: 100%;"></a></p>

## Local

```bash
git clone https://github.com/aws-samples/aws-openalex-knowledge-graph.git
cd aws-openalex-knowledge-graph/
pip install virtualenv
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
