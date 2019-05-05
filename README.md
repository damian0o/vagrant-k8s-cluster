# vagrant-k8s-cluster
Kubernetes Cluster for local development and testing

## Tutorials

* https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/

Small bug on this one
    
    - name: Copy join command to local file
    vars:
      ansible_become: no
    local_action: copy content="{{ join_command.stdout_lines[0] }}" dest="./join-command"
    
* https://linuxize.com/post/how-to-install-vagrant-on-ubuntu-18-04/
* https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#latest-releases-via-pip


