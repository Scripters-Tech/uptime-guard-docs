# UptimeGuard Documentation

This repository contains the official documentation for UptimeGuard, a simple website monitoring service designed for solo entrepreneurs.

## About UptimeGuard

UptimeGuard provides straightforward website monitoring with features including:

- Simple uptime monitoring for websites
- Instant notifications when your site goes down
- Performance tracking and metrics
- API access for custom integrations
- Mobile app for on-the-go monitoring

## Documentation Structure

This documentation includes:

- Getting started guides
- Feature documentation
- API reference
- Integration examples
- Best practices

## Development

To work on this documentation locally, follow these steps:

1. Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify):

```
npm i -g mintlify
```

2. Run the following command at the root of the documentation (where docs.json is):

```
mintlify dev
```

3. The documentation will be available at http://localhost:3000

## Publishing Changes

Changes to the documentation are automatically deployed when pushed to the main branch. The Mintlify GitHub App handles the deployment process.

## Troubleshooting

- If Mintlify dev isn't running, try `mintlify install` to re-install dependencies
- If a page loads as a 404, make sure you're running in a folder with `docs.json`
- For additional help, contact support@uptimeguard.xyz

## Contributing

If you'd like to contribute to the UptimeGuard documentation, please follow these steps:

1. Fork this repository
2. Create a new branch for your changes
3. Make your changes and test them locally
4. Submit a pull request with a clear description of your changes

## License

This documentation is copyright © UptimeGuard 2023-2024. All rights reserved.
