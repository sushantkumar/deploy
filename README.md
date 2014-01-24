
Deploy
=======
Git Based Deployment Scripts

Setup & Install
===============

Add private keys of deploy user to keys dir (not checked in) and chmod keys/self to 0600.

Edit deploy.conf to add a section similar to sample config section provided.

  $./deploy.sh myapp setup

To deploy

  $./deploy.sh myapp

To open a console

  $./deploy.sh myapp console

