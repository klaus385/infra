# nagios-client Role

Installs the nagios plugins and adds users and groups for the plugins.

## Tags

install_nagios_plugins

add_nagios_group

add_nagios_users

## Dependencies

role: scripts
 
## Usage

ansible-playbook --verbose main.yml -i inventory/hosts --sudo --tags=

## Variables

users.monitoring
item
item.name
item.group
