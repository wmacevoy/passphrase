# passphrase

This is a simple (auditable) python 2/3 script to generate pass phrases suitable for a master password

1. It uses the strong /dev/urandom source for randomness
2. They have the form Word1Word2Word3Word4Word5Word6Word7Word
3. The words are selected from the 1000 most common enlish words 
4. This produces 8*log(1000)/log(2)= 79.7 bits of entropy

You CAN paste this into an online interpreter to execute it, but you SHOULD run it locally.

https://www.python.org/shell/
https://www.ef.edu/english-resources/english-vocabulary/top-1000-words/
