# csci476
Lab1
I first downloaded a password list using the 10,000 most common passwords. I then used hydra to brute force and used this line to as the command 	"hydra -l test -P paswords.txt 70.39.80.128 ssh -V". After a couple of minutes I was able to get the password which was changeme. http://imgur.com/HGpLACX. I then used the password changme and the username test to connect to the server and got the flag. http://imgur.com/k16IvNx.  
