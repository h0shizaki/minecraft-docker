# Hosting minecraft server in Raspberry PI  
0. Setup your Raspberry Pi update OS and remote ssh to your **Berry**  
1. Download docker and docker-compose 
2. Clone this repo to **Berry**  
3. type docker-compose up -d  
4. Use  
```
docker exec -i [CONTAINER] rcon_cli
```
  for access to minecraft server terminal and add whitelist or OP   

```
docker exec -it [CONTAINER] bash
```
  for access to container file such as server.properties    


# File setup  
You can copy your old server data to folder data for play your old save!  


## Note 
Raspberry PI model 4 ram 4 Gb (LOW COST SERVER LOL).  
But server is stable when it does not generate new chuck for player around 4-5 players  
Remote shh with puTTy and copy file with WinSCP  
If I did not create a new repo that means I have Minecraft addiction.  
