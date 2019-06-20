quickstart:
`packer build packer.json`

- Sources Ubuntu VM
- Early provisions OS (preseeds/ubuntu_preseed.cfg)
- Fully provisions OS (ubuntu/init.yml)
- Simple sanity checks (ubuntu/test.yml)
- Generates image.ovf

About the design:
I wanted to make the Ansible stack fairly agnostic.   