# its-alive
Uses `host` command  to check if a subdomain/domain it's alive (by performing DNS lookups). 
Saves the live domains/subdomains in a file.

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


### Usage example
![Example](./docs/usage_example.svg)



# credits:
inspired by a technique shown this article:




https://www.hackerone.com/blog/Guide-Subdomain-Takeovers




(however the technique shown there doesn't permit to end the script with Ctrl+C)
