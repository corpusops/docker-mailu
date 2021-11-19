# library images on steroids for mailu
## Wrapped images
- [docker-images](https://github.com/corpusops/docker-images) compatibles images (original images wrapped with tools)
- [![.github/workflows/cicd.yml](https://github.com/corpusops/docker-mailu/workflows/.github/workflows/cicd.yml/badge.svg?branch=main)](https://github.com/corpusops/docker-mailu/actions?query=workflow%3A.github%2Fworkflows%2Fcicd.yml+branch%3Amain)

| original   | wrapped  |
|------------|-----------|
| [library/mailu](https://hub.docker.com/_/mailu)                         | [corpusops/mailu](https://hub.docker.com/r/corpusops/mailu)                   |
| [mailu/postfix](https://hub.docker.com/r/mailu/postfix)([./mailu/postfix](./mailu/postfix))                                     | [corpusops/mailu-postfix](https://hub.docker.com/r/corpusops/mailu-postfix)     |
| [mailu/rspamd](https://hub.docker.com/r/mailu/rspamd)([./mailu/rspamd](./mailu/rspamd))                                     | [corpusops/mailu-rspamd](https://hub.docker.com/r/corpusops/mailu-rspamd)     |
