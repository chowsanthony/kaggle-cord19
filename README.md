# kaggle-cord19
Work related to the Kaggle Dataset Challenge for COVID-19

schema.json is a JSON schema for the open dataset posted on https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge. It is based on Draft 7 of the JSON schema specification: https://json-schema.org/draft/2019-09. My intention for this to become a better replacement for [json_schema.txt](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge#json_schema.txt).

schema-validation-demo.ipynb is a Python Jupyter notebook. It uses the jsonschema library (3.0.1) for schema validation. The purpose is to quickly demonstrate how validation error may be useful for understanding the dataset.

### TODO
- [x] Create sample schema validation program to demonstrate a use case
- [ ] Pull additional examples from Kaggle dataset repo to verify
- [ ] Enhance the schema with examples