# Docker container with Terraform and GCP SDK

A docker container for Hashicorp's [terraform](https://terraform.io).

It also includes [Google Cloud SDK](https://cloud.google.com/sdk/) which is needed for the [Google Cloud Provider](https://www.terraform.io/docs/providers/google/index.html)


## Security

SHA256 hashes are checked against the published list of hash files for the version from hashicorp.

The integrity of the hash list is verified against hashicorp's [public key](hashicorp.asc) which is published on thier [security page](https://www.hashicorp.com/security.html)