## trucksync

Little script to help sync (as backup) and help to make it as a simple routine. 

## Variables

The script will copy from a location to another. You need to change @ minimum:

 LOCAL="/where/is/located/you/file"                                                       
 REMOTE="/where/it/neet/to/go" 

The script will ask you for the last part of the path. 

e.g.: You want to sync a folder in Documents, you add in LOCAL or REMOTE:

LOCAL=$HOME/Documents

The script will ask you for a project name and you tell him as name: test, the script 
will send this to: $HOME/Documents/test/

 
