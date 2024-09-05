# Flask & Form Submission

This Flask application provides a basic example of handling form submissions. It displays an HTML form where users can input their first name. Upon submission, the application greets the user by name on a new page. Note that alognside your .py file, include a requirements.txt so that the Dockerfile can install the necessary packages with pip.

## Essential Setup Files

1. A [Dockerfile](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/).
2. A [compose file](https://docs.defang.io/docs/concepts/compose) to define and run multi-container Docker applications (this is how Defang identifies services to be deployed). (compose.yaml file)

## Prerequisite

1. Download [Defang CLI](https://github.com/DefangLabs/defang)
2. If you are using [Defang BYOC](https://docs.defang.io/docs/concepts/defang-byoc), make sure you have properly [authenticated your AWS account (optional)](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html)

## A Step-by-Step Guide

1. Open the terminal and type `defang login`
2. Type `defang compose up` in the CLI
3. Your app should be up and running with Defang in minutes!

---

Title: Python & Form

Short Description: A short python example for form submission in flask.

Tags: Python, Flask, form

Languages: python
