# ssh-swapper
to change ssh configs between work and personal environments

only swaps between 2 envs, company / personal.
Need to have 2 config files in ~/.ssh:  

config  
config-winterfell  

first line of each file must be:  
#env:ENV_NAME  


Finally move this script to /usr/local/bin  
