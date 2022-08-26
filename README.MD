# OpenFaas Python with Chrome Driver Template

This template for Open FaaS allows to use chrome driver for scraping process with selenium in Python3.

## Quickstart

### Get OpenFaaS

[Deploy OpenFaaS](https://docs.openfaas.com/deployment/) to Kubernetes, or to faasd (single-node with just containerd)

### Create a function with the template and deploy it to OpenFaaS

```bash
faas-cli template pull https://github.com/mariamorav/openfaas-python-chrome-driver-template

faas-cli new --lang python3-chromedriver <function_name> --prefix <registry>

faas-cli up -f <function_name>.yml

```