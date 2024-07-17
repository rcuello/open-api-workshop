# OpenAPI 3.0 Tutorial 
OpenAPI 3.0 is a freely accessible framework designed to outline and detail APIs. Within this guide, we'll create a basic API outline using the OpenAPI 3.0 standard. For users employing OpenAPI 2.0 (previously known as Swagger 2.0), an alternate tutorial is available.

# What is OpenAPI?
The OpenAPI Specification, previously recognized as the Swagger Specification, is a publicly available format utilized for outlining and elucidating APIs. Initially crafted in 2010 by Reverb Technologies, formerly known as Wordnik, the Specification aimed to harmonize API design and documentation. Over time, it has emerged as the prevalent standard for formulating and delineating RESTful APIs, adopted by numerous developers and organizations for both internal and external API development purposes.

The most recent iteration of OpenAPI is version 3.0. OpenAPI definitions can be articulated in either JSON or YAML formats. YAML is recommended due to its enhanced readability and ease of composition.

# Prerequisites
- Basic knowledge of RESTful APIs.
- Basic knowledge of YAML is recommended.

# Converter tools
- https://www.site24x7.com/tools/json-to-yaml.html

# Tutorial
- https://learn.openapis.org/specification/
- https://swagger.io/docs/specification/about/
- https://support.smartbear.com/swaggerhub/docs/en/get-started/openapi-3-0-tutorial.html

# Visual Studio Code Extensions
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
- [OpenAPI (Swagger) Editor](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi)

# Mock tools
- [Prism](https://github.com/stoplightio/prism)
- [Mockoon](https://mockoon.com/)

# Getting started with Prism
First install **prism** using the following in nodejs command:

```bash
npm install -g @stoplight/prism-cli
```

Use the following command to create a fake "mock" server based off an OpenAPI document:

```bash
prism mock -p 8087 https://raw.githubusercontent.com/rcuello/open-api-workshop/main/pet-sitter.yml
```

More about [how the mock server works.](https://github.com/stoplightio/prism/blob/master/docs/guides/01-mocking.md)