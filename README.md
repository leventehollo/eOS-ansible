sudo apt-get install software-properties-common
sudo apt-add-repository -u -y ppa:ansible/ansible
sudo apt-get install -y ansible

How to use:

ansible-playbook install_elementary_os.yml -i hosts --ask-become-pass --extra-vars "username=levente" -vvv

