<sub><sup>Note: if you're here to steal a copy of my ChatGPT-based dev tools, go to the devtools/ folder. A separate repo is coming soon.</sup></sub>

# Transcripter

Transcripter is an AI-powered SASS app which generates summaries, guidelines, deliverables, TODOS, followups, etc., categorized by speaker / team member, from video captions.

The captions are generated by [AWS Transcribe](https://aws.amazon.com/transcribe/).

## CURRENT VERSION

0.45

## C++ Version

2020

## CURRENT STATUS

Currently configuring a test suite and static analysis tools.

## DEPENDENCIES

- [Clang](https://clang.llvm.org/)
- [Poco](https://pocoproject.org/)
- [JsonCpp](https://github.com/open-source-parsers/jsoncpp)
- [AMQP-CPP](https://github.com/CopernicaMarketingSoftware/AMQP-CPP)

## THIRD PARTY LIBRARIES

- [AWS Transcribe](https://aws.amazon.com/transcribe/)
- [OpenAI](https://openai.com/)
- [Jira](https://www.atlassian.com/)

## ENVIRONMENT VARIABLES

You will need these env vars set:

- OPENAI_API_KEY
- OPENAI_ORGANIZATION_ID
- AWS_TRANSCRIBE_AUTH_KEY
- AWS_TRANSCRIBE_AUTH_SECRET
- SMTP_SERVER_HOST
- SMTP_SERVER_PORT
- AMQP_USERNAME
- AMQP_PASSWORD
- JIRA_API_TOKEN
