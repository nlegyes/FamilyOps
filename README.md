# Ansible Workstation

This repository hosts an Ansible Playbook designed to streamline the setup process for workstations, tailored specifically for the **Fedora Silverblue/Universal Blue** project. The Ansible Playbook automates the configuration of essential software and settings, providing a quick and consistent way to prepare workstations for project development.

## Getting Started

To use this playbook, follow this simple step:

   ```bash
    ansible-pull -U https://github.com/nlegyes/FamilyOps.git universalblue-silverblue-main.yml
   ```

## Requirements

- Ansible installed on the system. Install it using:

  ```bash
  sudo rpm-ostree install ansible
  ```

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE.md](LICENSE) file for details.
