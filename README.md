[![Build the Ansible Docker Image](https://github.com/khann-adill/ansible-image/actions/workflows/build.yml/badge.svg)](https://github.com/khann-adill/ansible-image/actions/workflows/build.yml)
###
```
alias ansible='docker run --name ansible -v "${PWD}":/work:ro --rm mak1806/ansible:1'
```
`now, run ansible ansible-playbook playbook.yml `

`or docker run -itd --name ansible -v "${PWD}":/work:ro  mak1806/ansible:1`

`docker image: docker pull mak1806/ansible:1`

😉
