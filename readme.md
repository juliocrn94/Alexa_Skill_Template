# "Hello World" Alexa Skill Template

Skill template that uses Amazons ASK-SDK to build a basic "Hello World" Skill.

## Installation

Clone Git Repo to local use:

```bash
npm install
```

This will install the complete **ASK-SDK Distribution**. To install individual modules:
```bash
npm uninstall ask-sdk
```
And install the desired modules.

## Usage
**Create a Skill Package**

To prepare the skill for upload to AWS Lambda, create a zip file that contains the skill file plus the node_modules folder. Make sure to compress all project files directly, NOT the project folder.


**Upload Package to Lambda**

Create a Lambda Function inside AWS and upload the Skill package.
More information in: [Host a Custom Skill as an AWS Lambda Function](https://developer.amazon.com/en-US/docs/alexa/custom-skills/host-a-custom-skill-as-an-aws-lambda-function.html)

## Documentation

For more information visit the [Official Amazon Alexa Documentation] (https://developer.amazon.com/en-US/docs/alexa/alexa-skills-kit-sdk-for-nodejs/develop-your-first-skill.html).