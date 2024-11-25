# quick_var_assign_-

### To quickly assign a varable and recall it in the same terminal
### *Useful for long commands, IP address, that will be used over and over*

```bash
#Save the IP address (in this example) 
echo "192.168.1.5" > ip.txt 

#Read the IP and assign it to a variable
IP=$(< ip.txt)

#Test if variable works
echo $IP

#Ping the IP address
ping -c 4 $IP
```


