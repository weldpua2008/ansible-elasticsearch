# ansible-elasticsearch
This role will assume the setup of elasticsearch server.


Requirements
------------

- Java Runtime Envorinment. If you want to install Java take a look at the role weldpua2008.java.
- Ansible 1.6.0+

Dependencies
------------

Run the following command to install the necessary Ansible roles for this profile: `$ ansible-galaxy install -r requirements.yml`

## Installation

Using ansible galaxy:

```bash
ansible-galaxy install weldpua2008.elasticsearch
```
You can add this role as a dependency for other roles by adding the role to the meta/main.yml file of your own role:

```yaml
dependencies:
  - { role: weldpua2008.elasticsearch }
```

Example Playbook
----------------

Example of how to use weldpua2008.elasticsearch:

    - hosts: elasticsearchservers
      roles:
         - { role: weldpua2008.elasticsearch  }

License
-------

MIT

Author Information
------------------
Valeriy Solovyov