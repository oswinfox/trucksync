## trucksync

Little script to help sync (as backup) and help to make it as a simple routine. 

## Variables

The script will copy from a location to another. You need to change @ minimum:

<pre>
 LOCAL="/where/is/located/you/file"                                                       
 REMOTE="/where/it/neet/to/go" 
</pre>

The script will ask you for the last part of the path. 

e.g.: You want to sync a folder in Documents, you add in LOCAL or REMOTE:

<pre>
LOCAL=$HOME/Documents
</pre>

The script will ask you for a project name and you answer: test, it will be send this to: $HOME/Documents/test/

 
