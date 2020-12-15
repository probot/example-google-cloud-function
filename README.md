# Probot & Google Cloud Functions example

This repository is an example of how to deploy the "Hello, World" of probot apps to [Google Cloud Functions (GCF)](https://cloud.google.com/functions).

## Local setup

Install dependencies

```
npm install
```

Start the server

```
npm start
```

Follow the instructions to register a new GitHub app.

## Deployment

The app is continuously deployed to Google Cloud using the [`setup-gcloud` GitHub Action](https://github.com/google-github-actions/setup-gcloud). See [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) for the deployment workflow.

## License

[ISC](LICENSE)
