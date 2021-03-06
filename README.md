# newrun copyright © 2011-2014 M. Kristall

newrun is meant for controlling game servers

## Getting started

1. Pick a good place to put the important files. The file "configuration" must
   be in the same directory as the file "newrun" or as "/etc/newrun.conf". The
   file "functions" and the directories "conf", "exec", and "defs" can be
   anywhere as long as you update the file "configuration" appropriately
2. Update locations in the file "configuration" if you put things in non-default
   locations
3. Make a new config for your server in "conf". The included example config
   should be a good starting point


## Start the server (args = arguments to pass to the server)
`$ ./newrun configname start [args]`


## Check if the server is running
`$ ./newrun configname status`


## Restart the server (args = arguments to pass to the server)
`$ ./newrun configname restart [args]`


## Stop the server
`$ ./newrun configname stop [message]`


## Reload the server
`$ ./newrun configname reload [message]`


## Run command on the server (command = command to run)
`$ ./newrun configname exec command`
