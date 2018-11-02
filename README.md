# ssh-Pis
Access over different Pis without entering passwords


CHECK IF ALREADY SSH KEYS EXISTS
Check if already ssh keys are present which you are using to connect to your pi. To confirm execute the following 

    ls ~/.ssh
If it returns id_rsa.pub and id_dsa.pub then you already have keys and you can skip the net step (generate ssh keys)

    id_rsa.pub   id_dsa.pub    known_hosts

GENERATE SSH KEYS

For generation of ssh keys execute the following command feom your terminal

    ssh-keygen
The output will ask you a place to save the keys enter the following line and hit enter

    /home/pi/.ssh/id_rsa
