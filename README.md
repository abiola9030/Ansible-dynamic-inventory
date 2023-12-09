# ansible-dynamic-inventory

## Getting started

1. Create 2 EC2 instances (AWS-linux 2023) for the host nodes and use "common-user-code" as userdata.
2. Create 1 EC2 instance (AWS-linux 2023) as control node and use "control node user data"
3. Run ansible setup code on control node to download ansible, python and boto 3.
4. dynamic inventory is aws-ec2.yml
5. playbook is web-app.yml
6. command-to-run- aws-dynamic inventory file next

# This project contains every ncessary code to setup a control node, host nodes with a dynamic inventory. This depends hugely on the tagging convention.
