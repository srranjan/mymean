The spring boot patterns for cloud-native java had earlier been published after testing on bare metal, Bluemix cloud foundry and Pivotal cloud foundry. 
The same code base with some minor alterations in configuration has been tested using docker containers and docker internal network connectivity. 


The code was tested on Ubuntu 16 VM and subsequently on AWS. 


The details of AWS configuration has been captured separately in a Word doc and attached here. 

On public AWS, there is a need to open the ports through security group setting.


The steps required for creation of images and containers are the following respectively:

./build_images.sh

docker-compose up -d


