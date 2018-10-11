#!/bin/bash
clear
printf "Wait 5 seconds for install java"
sleep 5
sudo apt-get update
sudo apt-get install default-jre
sudo apt-get install default-jdk
apt-get install screen
sudo apt-get install oracle-java8-installer
clear
printf "Java have been installed succesfully"
 
