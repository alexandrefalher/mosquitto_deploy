# Pre requisites

For this example of Ansible + Docker deploy scripts, you need :
- install ansible on your "manager host"
- clone this repository to your manager host
- add a new host named 'rasp-01' to your manager host's local DNS. This host will be the managed host, the target. Those scripts are designed to work with a Raspberry Pi 4.
- establish an ssh connection from the manager host to the managed host, record fingerprint

When all the prerequisites will be fullfilled :
- execute the script "launch.sh" at the location /scripts