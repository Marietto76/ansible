# Banco Solidario: Ansible Paybooks para prerequisitos de OpenShift
2024-12-12

## Introducción
Estos Ansible Playbooks permiten la instalación de las dependencias de Ansible automation platform

## Instalación
Para realizar la instalación se debe ejecutar el playbook appropiado configurando las variables según el escenario (no productivo, productivo, etc.).

Ambiente No Productivo:

```bash
$ ansible-playbook -e @vars/openshift-hosts-noprod.yml -i inventory/hosts-noprod.yml configure-haproxy.yml
```
