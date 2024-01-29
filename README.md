# Ansible Collection - betagouv.oots

This collection of Ansible roles aims at helping set up the software that can be
used by any European Union Member State in order to participate to the
[Only-Once Technical
System](https://ec.europa.eu/digital-building-blocks/sites/display/OOTS/About+OOTS)
(OOTS).

## How to use

This collection can be installed and its roles can be integrated to Ansible
playbooks.

Add the following to your Ansible Galaxy `requirements.yml` file:

```yaml
collections:
  - name: https://github.com/betagouv/ansible-collection-oots.git
    type: git
```

You can then install it with the command:

    ansible-galaxy collection install -r requirements.yml

You will then be able to call on the roles of this collection using the name
`betagouv.oots.<role_name>`.

## Roles documentation

All available roles are in the folder `roles` and each role is documented in
detail under its `meta/argument_specs.yml` file.
