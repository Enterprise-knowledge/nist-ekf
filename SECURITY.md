# Security Policy

This repository is a public EKF demo built from public NIST material. Please report issues that could expose sensitive data, encourage unsafe source handling, or affect the local generation and graph tooling.

## Reporting

Open a private security advisory on GitHub if available, or contact the maintainers through the repository owner.

Please include:

- the affected file or workflow,
- steps to reproduce,
- expected impact,
- any suggested mitigation.

Do not open public issues for vulnerabilities or accidental secret exposure.

## Sensitive Material

Do not contribute credentials, private keys, access tokens, customer data, confidential internal documents, or proprietary source material.

## Scope

In scope:

- unsafe generated HTML behavior,
- validator or parser issues that hide invalid EKF content,
- accidental inclusion of sensitive source material,
- documentation that encourages unsafe handling of secrets or private data.

Out of scope:

- vulnerabilities in third-party packages used only during local experimentation,
- issues requiring access to private repositories or unpublished source material.
