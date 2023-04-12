# platelminto.com

A Hugo website where I will hopefully write some stuff.

## Requirements

- [Hugo](https://gohugo.io/)
- A VPS that hosts the website. I use [Hetzner](https://www.hetzner.com/).

## Installation & Deployment

1. Clone the repository
2. Copy `.env.example` to `.env` and fill in the variables.
3. Ensure that SSH keys are set up for the VPS.
4. Test changes locally with `hugo server -D`.
5. Build the website with `hugo`.
6. Run `./deploy.sh` to deploy the website.
