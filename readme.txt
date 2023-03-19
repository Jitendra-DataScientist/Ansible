This is to demonstrate ansible configuration management using a master and 2 slave nodes.

Step 1: Launch 3 ubuntu instances, and let us call them master, slave1 and slave2.
Step 2: Update all the instances using "apt update".
Step 3: Set up ansible on master node using:
        - sudo apt install software-properties-common -y
        - sudo add-apt-repository --yes --update ppa:ansible/ansible
        - sudo apt install ansible -y

Next, one could run any of the playbooks using:
ansible-playbook <path_to_yaml_file>