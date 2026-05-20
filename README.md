# Puppet Infrastructure Lab

Puppet manifests for automating server configuration on a Linux system. Covers LAMP stack provisioning, user and group management, and configuration testing — demonstrating infrastructure-as-code (IaC) principles using Puppet DSL.

## Manifests

| File | Description |
|---|---|
| `lamp_stack_server.pp` | Provisions a full LAMP stack (Linux, Apache, MySQL, PHP) |
| `server_users_groups.pp` | Automates user and group creation and assignment |
| `testing_puppet.pp` | Validates Puppet configuration and resource states |
| `phpinfo.php` | PHP info page for verifying the web server stack |

## What This Covers

- **Infrastructure as Code** — declarative server configuration using Puppet DSL
- **LAMP Stack Automation** — installs and configures Apache, MySQL, and PHP
- **User Management** — manages system users and groups through Puppet resources
- **Configuration Testing** — verifies expected system state after applying manifests

## Usage

Apply a manifest with:

```bash
sudo puppet apply lamp_stack_server.pp
```

Test configuration without making changes:

```bash
sudo puppet apply --noop lamp_stack_server.pp
```

## Technologies

`Puppet` `Linux` `Apache` `MySQL` `PHP` `Infrastructure as Code` `DevOps`
