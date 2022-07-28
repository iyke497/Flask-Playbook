# Flask-Ansible-Playbook
Ansible playbook for deploying simple flask applications utilizing sqlite database. This is a learning experience for Ansible that configures a server and deploys a simple Flask
application written following guidelines from this tutorial [Flask Tutorial - Corey .M Schafer](https://www.youtube.com/playlist?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH)

To make use of this playbook, you're project files should be arranged as described in the tutorial linked above. 

Run the playbok to deploy the application using
`ansible-playbook -i hosts main.yml`
