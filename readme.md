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

**1**
Create a Lambda Function, running with node, inside AWS and upload the Skill package.
More information in: [Host a Custom Skill as an AWS Lambda Function](https://developer.amazon.com/en-US/docs/alexa/custom-skills/host-a-custom-skill-as-an-aws-lambda-function.html)
Add a Alexa Skill Kit as trigger (you will need the Skill ID, obtained after the next step).
*Note*: Save the Lambda ARN.

**2**
Create a new Alexa skill in the [Amazon Developer Console](https://developer.amazon.com/alexa/console/ask).
*Note*: Save the Skill Id.

**3**
Add a *Unique Invocation* and a *HelloWorldIntent* with the enunciations the user has to input to trigger the Intent.

**4**
Finally and the Lambda ARN as an Endpoint.

## Documentation

For more information visit the [Official Amazon Alexa Documentation] (https://developer.amazon.com/en-US/docs/alexa/alexa-skills-kit-sdk-for-nodejs/develop-your-first-skill.html).