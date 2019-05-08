# xmr-stak-docker
# Building a self-contained docker container to mine Cryptonight on CPU/AMD/NVIDIA

## Design
* This process is intended to be use Docker, Artifactory, and Jenkins.

### Variables

* ARTIFACTORY_URL == This will be the URL for artifactory, without the reposuitory information.  Passed as an environment variable to the build system so the information is not pushed to the repository

* ARTIFACTORY_UNAME == This is the username to log into artifactory.  Passed as an environment variable to the build system so the information is not pushed to the repository

* ARTIFACTORY_PASSWD == This is the password to log into artifactory.  Passed as an environment variable to the build system so the information is not pushed to the repository

* ARTIFACTORY_API == Currently not implemented.
