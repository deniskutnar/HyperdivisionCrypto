### Denis Kutnar

## note

Recently I got an issue with my CLI and I couldn't install the module:
" npm install --save rsa-keygen"


Thus I am using:  "keygen = require('ssh-keygen');"  for generating 'key.secret.pem' and 'key.public.pem' which is used only for the generation of the new key pair anytime the program is run.
