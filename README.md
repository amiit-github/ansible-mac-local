# Setting up Mac with Ansible.
Setting up your local mac development environment with Ansible.

1. Add the homebrew package names in yaml file under 'homebrew_installed_packages'.
2. Run the command ``` ansible-playbook -K -i inventory mac-playbook.yml ```

Note : With the -i flag, define the pool of hosts to run on, mentioned in file inventory. The -K parameter prompts to enter the sudo password, otherwise the tasks will fail, just in case.
