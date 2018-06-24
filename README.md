# EvilCorp-SASL
EvilCorp Irc SASL setup 
This is an easy tutorial made by TripleZer0 for hexchat users to conn$
SASL in EvilCorp/Fsociety IRC.(only tested on ubuntu) It's pretty sim$
as well. If you need help please contact me, TripleZer0 on EvilCorp/F$
IRC.

STEP 1:
        Add A new Network to your hexchat hetwork list. Click top lef$
"hexchat" then click add. Name it "fsocietySASL". Next click edit use
server "fsociety.evilcorp.ga/6697". Then select these boxes "connect
to this network automatically", "Use SSL for all servers on this
network", and "Use global user information". (If you would like to
add a connect command to identify you may.) Finally select "SASL
EXTERNAL (cert) as Login method, close it then connect, then close
again.

STEP 2:
        Run autosasl. To run autosasl open terminal the cd (change
directory) to where it is stored. Next use the command "chmod +x
autosasl). Then to run use the command "./startsasl". It wil ask for
some input and it doesnt need to be real. Then when the script is
done the very last long will have a string of random letter and
numbers. Copy this you will need it for step 3.

STEP 3:
        Open back up your hexchat (close and re open if needed).
Identify to your nick. Next type in "/msg nickserv cert add (paste
the string here)". If you get he msg "(string) added to (your nicks)
certificate list." You've done it right. :)

---------------------------------------------------------------
AGAIN if any help is needed come talk to me, TripleZer0, I will do my
best. Enjoy More Security :P
