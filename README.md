recon_backend
=============

see Reconstitution 2012 | Software Notes for more info getting setup

recon_backend server must be running for data to be received on frontend

*From the frontend,* use args 'docName' and 'delay' to simluate streaming, place documents in the /documents folder in the backend directory. If no delay is entered, it defaults to 0 (all data received at once) ex: index.html?docName=2008_2.txt&delay=100

use no args if you want live cc streaming from OF app

see Reconstitution 12 | Data and Stats doc for message specs


mongo_dumps folder contains LIWC libs, run sh mongo_dumps/loadLIWC.sh