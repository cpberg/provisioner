quickstart:
`packer build packer.json`

- Sources Ubuntu VM
- Early provisions OS (preseeds/ubuntu_preseed.cfg)
- Fully provisions OS (ubuntu/init.yml)
- Simple sanity checks (ubuntu/test.yml)
- Generates image.ovf

About the design:
- I wanted to make the provisioning logic fairly Linux agnostic. 
- Much of the logic can be followed with simple adjustments for other distrobutions.
- The testing portion of the stack is useful for image sanity checking, but is not as portable.

