# OPEN API documentation demo

Testing documentation using [Insomnia](https://insomnia.rest/)

Based on the tuturial from [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-create-documentation-for-your-rest-api-with-insomnia)

## Published preview

View the docs at [docs.jonathancrider.com/](https://docs.jonathancrider.com/)

## Building the docs locally

Use the [Redocly CLI](https://redocly.com/docs/cli) to build from the YAML file

```bash
npx @redocly/cli build-docs openapi.yaml
```

## Preview the docs locally

Download the repo and run the docs locally

```bash
npx @redocly/cli preview-docs openapi.yaml
```
