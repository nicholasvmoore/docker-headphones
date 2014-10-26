Headphones Docker Container
===


# Persistant files
Headphones stores its configuration files and what not in the directory you clone the gitrepo. You can also store the config in the --datadir which is the method I prefer.  Ensure you setup a volume which maps /config to persistant storage.