## How to run
`ansible-playbook attach-playbook.yml -i hosts.yml -u root`

* -i points to the host inventory file
* -u defines the user with which to utilize via ssh (this must match up with the public key on the host)
