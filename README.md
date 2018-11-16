# runbooks-ipam [![runbooks-ipam](https://travis-ci.com/Dallas-Makerspace/runbooks-ipam.svg?branch=master)](https://travis-ci.com/Dallas-Makerspace/runbooks-ipam/builds)

Generic ansible and docker-compose files to setup dns and dhcp within pfsence

## Requirements
  - ansible 2.0+
  - docker-compose
  - docker
  - amatas/ansible-pfsense

## Usage

`ansible-playbooks playbook.yml`

## Deployment

```
docker stack deploy -c docker-compose.yml "$(basename $(pwd))"
```
