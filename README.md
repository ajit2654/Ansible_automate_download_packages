# Ansible_automate_download_packages
This is simple script to download packages using yum modules.
you can also download multiple packages using it.
you only need small changes in this script 
using  colon(,) you can add one or more packages
like yum: rpm,vim,sysinfo
then run on terminal :
ansible-playbook ap_install_rpm_package.yml -vvv
