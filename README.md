# Probot & Google Cloud Functions example

This repository is an example of how to deploy the "Hello, World" of probot apps to [Google Cloud Functions (GCF)](https://cloud.google.com/functions).

## Local setup

1. Create `.env` file with the values for your GitHub App registration and smee URL

   ```
   APP_ID=
   PRIVATE_KEY="-----BEGIN RSA PRIVATE KEY-----\nMII...oq5zgok=\n-----END RSA PRIVATE KEY-----\n"
   WEBHOOK_SECRET=
   WEBHOOK_PROXY_URL=
   ```

2. `npm install`
3. `npm start`

## License

[ISC](LICENSE)
