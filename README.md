# My personal server

Hosted at https:/rishid.com

## Domain Name Registration
> I bought the domain name at namecheap and set up the `A Record` to the public
IP address of the VM bought in the next step

## Virtual Machine
> I did this manually by clicking in the Hetzner Cloud Web UI. Would be ideal to automate this with Terraform or Hetzner API

Hetzner Cloud
CX22 -> 2 vCPUs, 4 GB RAM, 40 GB SSD, 20 TB traffic, 3.92 EUR/month

## Utilities installed
> I did this manually now, but would be ideal to automate this with Ansible or
PyInfra or whatever alternative exists
- git
- docker
- caddy (alternative to nginx)
- golang
- pyenv (for installing python releases)

## Images:
- Silverbullet (Markdown notes)
[Docker image](https://hub.docker.com/r/zefhemel/silverbullet)

- Calibre Web (Ebook manager)
[What is Calibre?](https://calibre-ebook.com/)
[Deploying Calibre with Docker](https://hub.docker.com/r/linuxserver/calibre-web)

- Marimo (Python notebooks)
[What is marimo?](https://marimo.io/)
[Deploying marimo with Docker](https://docs.marimo.io/guides/deploying/deploying_docker.html)
