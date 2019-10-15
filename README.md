
# Reccoon Bot 

## is a telegram bot with an OSINT toolkit.

# Usage:

In reccoon is possible run in two ways:
> Locally:

To run locally you must set the variable token
```
token="KEY"
shodan_key="Shodan key"
export shodan_key
export token
./bot.sh
```

> Docker :
```
docker run --env token="Your KEY" --env shodan_key="Shodan KeY" St0rm-security/reconbot
```

# In the bot 

In bot the tools are separated into two groups:
**infrastructure** and **people**

You can use the tools as follows:

Using target as argument:
```
/nmap scanme.nmap.org
```

**Or**

Setting your target with /setinfra /setpeople /settarget
```
/settarget 
select "infra" 
entry your target 
/nmap
```  

## For development
To enter the branch **dev** you will need to be in the project directory and perform the command
```sh
git checkout dev
```

To view which branch it is in can be used
```sh
git branch
```
> The result will be something like
```sh
$ git branch
* dev
  master
```
  
