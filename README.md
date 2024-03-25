Bonjour 👋, my name is Olive from MBA Cybersecurity 
The VirtualBox and Vagrant app have already been installed on the local device, the virtual machine was set up using Vagrant. 

To create a new directory in the local directory, the "document" folder was added to the local machine directory manually. To do this using the command prompt, the Windows Command Prompt was utilized to execute the following commands:-
cd document       
cd lab2
![Capture PNG](https://github.com/ollyvon/ollyvon/assets/161733071/959bbf8a-e7f7-475e-90fb-1759e6d879c9)
After executing the command, a lab2 file has been created inside the directory.
To update and then add the current ubuntu version, the init option was executed. The following command was executed ; vagrant init ubuntu/trusty64 --box-version 20190425.0.0
![Capture PNG((](https://github.com/ollyvon/ollyvon/assets/161733071/114b5d09-cd84-43da-96ab-e6eec0d5fc91)
After downloading, the following was showed on the command propmpt.
![Capture PNGééé](https://github.com/ollyvon/ollyvon/assets/161733071/8953accf-e62c-46ed-abde-17e92bf9924d)
The SSH details was also provided once the command was executed successfully.
![ççç](https://github.com/ollyvon/ollyvon/assets/161733071/ee603763-fe9d-48f7-8507-e8a91c985c2e)
To start the VM via the command prompt, the following command was executed: vagrant up
![Capture PNG((((((((((](https://github.com/ollyvon/ollyvon/assets/161733071/82acfedb-ebe1-4cd5-8660-117a5cf67d99)
To connect to the VM, the followed command was executed via the SSH: vagrant ssh
![ssh](https://github.com/ollyvon/ollyvon/assets/161733071/ab54202b-148a-407e-988b-9358161e8a1f)
To install Nginx on the VM, the following command was executed;
sudo apt-get update
![sudo](https://github.com/ollyvon/ollyvon/assets/161733071/ca1f3a87-0434-4fb0-9421-4c6fcbe8c1ac)
sudo apt-get install nginx
![install](https://github.com/ollyvon/ollyvon/assets/161733071/2b4a8d25-43c4-4a14-9598-2054906a5412)
The virtual machine was exited using the exit command
![exittt](https://github.com/ollyvon/ollyvon/assets/161733071/3bca8b2f-1f40-4c1b-a109-8d5fd61a31a6)
A vagrant box from the current VM state was created using the following command: vagrant package --output lab2.box
![Capture PNGlab2](https://github.com/ollyvon/ollyvon/assets/161733071/34873beb-45da-48a8-b4eb-492f4c0091cc)
Checked and verfied manually on the local machine to confirm it has been saved.
VM name ="[ofuokwuolive/ubuntu-nginx-olive"](https://app.vagrantup.com/ofuokwuolive/boxes/ubuntu-nginx-olive)https://app.vagrantup.com/ofuokwuolive/boxes/ubuntu-nginx-olive"
