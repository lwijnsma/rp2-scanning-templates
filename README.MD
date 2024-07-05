# RP2 Scanning Templates

# Intro
In this repo the Docker file / code and scanning templates used during the *Evaluation of Post-Quantum Readiness of the
Dutch IPv4 Internet* Project.

## Templates
The templates in the folders were used to determine the quantum resilience of the hosts scanned. [Nuclei](https://github.com/projectdiscovery/nuclei) is needed to run these templates.

## Dockerfile
The docker file is to be used in the root of the https://github.com/projectdiscovery/nuclei repo to build a nuclei image supporting OpenSSL PQC algorithms. without this the `tls-pqc-script.yaml` won't run. Because it depends on the existence of an OpenSSL built with the [oqsprovider](https://github.com/open-quantum-safe/oqs-provider)

## Software versions used

| Software | Version |
|----------|----------|
| zmap |  4.1.1 |
| Nuclei | v3.2.9 |
| OpenSSL | 3.4.0-dev |
| oqsprovider | 0.6.2-dev |
| liboqs | 0.10.1 |

## Authors
- [Laurens Wijnsma](https://github.com/lwijnma)
- [Karlo Drvoderić](https://github.com/karlokarlo)





