# vmware-provisioning-windows

Ansible playbook for automated vmware server deployment

## **Descripción:**
Despliegue automático de máquinas virtuales de VMware de manera automatizado a través de un playbook de Ansible.

El despliegue se realiza a partir de un template windows server.

Una vez desplegada la máquina virtual se une al dominio AD.

Se instala el windows_exporter (exporta métricas al Prometheus) y el puppet agent 5.5


