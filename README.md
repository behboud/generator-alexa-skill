# generator-alexa-skill [![NPM Version](https://badge.fury.io/js/generator-alexa-skill.svg)](http://badge.fury.io/js/generator-alexa-skill) [![Build Status](https://travis-ci.org/cameronhunter/generator-alexa-skill.svg)](https://travis-ci.org/cameronhunter/generator-alexa-skill)

> A [Yeoman](http://yeoman.io) generator for scaffolding an Alexa Skill for AWS Lambda

## Installation

```bash
npm install -g yo generator-alexa-skill
```

## Generating an Alexa Skill

```bash
yo alexa-skill
```

This creates a brand new Alexa Skill, add your logic into `lib/<skill-name>.js` and tests into `test/<skill-name>.spec.js`.

## Deploying to AWS Lambda

To build the skill for use on AWS Lambda:

```bash
npm run prepublish
```

This creates `dist/package.zip` exposing a single handler called `index.handler`, which you can upload to AWS Lambda.

## License

MIT
