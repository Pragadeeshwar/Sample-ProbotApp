# Sample-Probot-App

> A GitHub App built with [Probot](https://github.com/probot/probot) that A sample probot app

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t Sample-Probot-App .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> Sample-Probot-App
```

## Contributing

If you have suggestions for how Sample-Probot-App could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2022 Pragadeeshwar <pragadeeshwar0801@gmail.com>
