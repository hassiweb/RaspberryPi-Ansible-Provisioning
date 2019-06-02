# RaspberryPi-Ansible-Provisioning
An example of provisioning using Ansible for Raspberry Pi

## Description
This example yml file is designed for Raspbian OS (Verified on Raspberry Pi Zero W/WH) and provisions below:
- NTP configuration
- Docker installation

### Configuration

You have to configure files below:
- ./inventory/inventory.ini
- ./roles/common/geerlingguy.docker_arm/defaults/main.yml
- ./roles/common/geerlingguy.ntp/defaults/main.yml


### How to run

Type the command below.
```
$ ansible-playbook -i inventory/inventory.ini raspberry_pi raspbian_provisioning.yml
```

### More informatiion
[My blog is here (in Japanese)](https://hassiweb-programming.blogspot.com/2019/06/raspberry-pi-provisioning-using-ansible.html)


## License
MIT

## Contact
hassiweb ([twitter](https://twitter.com/hassiweb)/[Github](https://github.com/hassiweb))

