AlexaCurrency
====

A currency conversion skill for the [Amazon Echo][echo link].

# Requirements

- One [Amazon Echo][echo link]
- An [Amazon Lambda][lambda link] account, which provides the first 1M requests per month for free.

# Setup

- Clone this repository
- run `make setup`
- run `make build`
- Upload ArchiveDummy.zip to [Amazon Lambda][lambda link]. Note the ARN provided from the lambda function.
- Register for an Amazon Skills Kit developer account (free) and create a new skill
- Paste in `speechAssets/IntentSchema.json` and `speechAssets/SampleUtterances.txt` to their respective sections under "Interaction Model"
- Paste in the contents of `speechAssets/CustomSlots` into custom slot types. Makes ure the type field is the name of the file.

# Usage

- Alexa ask Currency to convert five american dollars to canadian
- Alexa ask Currency what is two hundred U.S.D. in B.T.C.
- Alexa what is the

### Feedback?

- Alexa, ask Currency how to submit feedback

### Found something broken?

- Alexa, ask Currency how to report a bug

# Contributing

My bitcoin address is [1BXiogdLRwoKsLjTmoaTYZB5Zn8ZoWCwMP](bitcoin:1BXiogdLRwoKsLjTmoaTYZB5Zn8ZoWCwMP) [click for QR](http://f.cl.ly/items/0c2N2F0C3F1X0N2R2K3Z/1BXio.png)

# Questions

[Create an issue!](https://github.com/bxio/dummyAlexa/issues/new)


[echo link]: http://www.amazon.com/dp/B00X4WHP5E/?tag=bxio-20
[lambda link]: http://aws.amazon.com/lambda
