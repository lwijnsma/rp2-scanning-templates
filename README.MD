# RP2 Scanning Templates

# Intro
In this repo the Docker file / code and scanning templates used during the *Evaluation of Post-Quantum Readiness of the
Dutch IPv4 Internet* Project.

## Templates
The templates in the folders were used to determine the quantum resilience of the hosts scanned. [Nuclei](https://github.com/projectdiscovery/nuclei) is needed to run these templates.

## Dockerfile
The docker file is to be used in the root of the https://github.com/projectdiscovery/nuclei repo to build a nuclei image supporting OpenSSL PQC algorithms. without this the `tls-pqc-script.yaml` won't run.

## Authors
- [Laurens Wijnsma](https://github.com/lwijnma)
- [Karlo Drvoderić](https://github.com/karlokarlo)





