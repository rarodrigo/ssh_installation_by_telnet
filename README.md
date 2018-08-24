# Executing SSH configuration via Telnet Process
The whole process about this developer action were declared inside my [BLOG - Ansible SSH Installation](https://ciscoredes.com.br/2017/12/21/ansible-instalar-ssh-usando-processo-de-automacao).

There are many resource used to in this script because was done with " ntc-ansible " to execute Telnet access and after that modules of Ansible, like " lineinfile ", " roles ", " conditionals "

We can follow description to execute those tasks:

- Access device via telnet: ` ntc-ansible modules`
- Verify if device has ssh installation: `show ip ssh by CLI`
- Which version of SSH is enabled
- Negative related ssh installation:
  - Run the SSH script and insert key on the hosts files ( management server )
- Positve:
  - Get the key and insert on the hosts files ( management server )
