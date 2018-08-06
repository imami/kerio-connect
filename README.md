![Kerio Connect](https://raw.githubusercontent.com/imami/kerio-connect/master/logo.png)
# Kerio Connect



#### Setup as a command
```
sudo cp kerio-client /usr/bin/kerio-client
```
 
#### Create configuration file (optional)
Create file `/etc/kerio-client.conf` with following contents.

```
server=[server-address]:[server-port]
ssl=[true,false]
username=[your-username]
password=[your-password]
```

#### Command options:
`-s , --server` :  server address  
`--ssl` : Wheather or not to use https protocol  
`-u , --username `: Account's username  
`-p , --password `: Account's password  

#### Usage :
###### Login
```
kerio-client login [options]
```
###### Logout
```
kerio-client logout [options]
```


#### Future Plans
 - Insteractive configuration  
 - Clean up codes  
 - Get connection statistics  
 - ...  