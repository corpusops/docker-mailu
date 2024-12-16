# library images on steroids for mailu

DISCLAIMER
============

**UNMAINTAINED/ABANDONED CODE / DO NOT USE**

Due to the new EU Cyber Resilience Act (as European Union), even if it was implied because there was no more activity, this repository is now explicitly declared unmaintained.

The content does not meet the new regulatory requirements and therefore cannot be deployed or distributed, especially in a European context.

This repository now remains online ONLY for public archiving, documentation and education purposes and we ask everyone to respect this.

As stated, the maintainers stopped development and therefore all support some time ago, and make this declaration on December 15, 2024.

We may also unpublish soon (as in the following monthes) any published ressources tied to the corpusops project (pypi, dockerhub, ansible-galaxy, the repositories).
So, please don't rely on it after March 15, 2025 and adapt whatever project which used this code.



## Wrapped images
- [docker-images](https://github.com/corpusops/docker-images) compatibles images (original images wrapped with tools)
- [![.github/workflows/cicd.yml](https://github.com/corpusops/docker-mailu/workflows/.github/workflows/cicd.yml/badge.svg?branch=main)](https://github.com/corpusops/docker-mailu/actions?query=workflow%3A.github%2Fworkflows%2Fcicd.yml+branch%3Amain)

| original   | wrapped  |
|------------|-----------|
| [library/mailu](https://hub.docker.com/_/mailu)                         | [corpusops/mailu](https://hub.docker.com/r/corpusops/mailu)                   |
| [mailu/postfix](https://hub.docker.com/r/mailu/postfix)([./mailu/postfix](./mailu/postfix))                                     | [corpusops/mailu-postfix](https://hub.docker.com/r/corpusops/mailu-postfix)     |
| [mailu/rspamd](https://hub.docker.com/r/mailu/rspamd)([./mailu/rspamd](./mailu/rspamd))                                     | [corpusops/mailu-rspamd](https://hub.docker.com/r/corpusops/mailu-rspamd)     |


- **TODO**: images have moved to another registry (githubm: ghcr.io/mailu), refresher code needs to be updated to be able support it.
