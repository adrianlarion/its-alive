# its-alive
* Uses `host` command  to check if a subdomain/domain it's alive (by performing DNS lookups). 
* Saves the live domains/subdomains in a file.
* shows report of how many are alive and  dead (including percentages)


### Install
* go to your apps dir (or where you want this installed). eg: `cd ~/apps`
* clone the git repo 
`git clone https://github.com/truffle-dog/its-alive`
* (optional) add the directory to your .bashrc so you can run it from anywhere like so (replace `/home/apps` with the path to the dir where you cloned the repo):
```
export PATH="~/apps/its-alive:$PATH" 
```
Alternatively you could just run run `wget` with the raw version of the `its-alive.sh` like so:

`wget https://raw.githubusercontent.com/truffle-dog/its-alive/master/its-alive.sh`. Afterwards just run the script from there

### Usage 

**Domains/subdomains  file should be in the form:**
```
scanme.nmap.org
google.com
```
Using `https://google.com` won't work.

![Example](./docs/usage_example.svg)

# warnings



**USE AT YOUR OWN RISK**



**USE RESPONSIBLY**



# credits:
inspired by a technique shown this article:




https://www.hackerone.com/blog/Guide-Subdomain-Takeovers




(however the technique shown there doesn't permit to end the script with Ctrl+C for some reason)
