# PASGEN

## Description

PASGEN is password generator based on xxHash 32 (a very fast hashing algorithm) - see the details of this hash [here](https://github.com/pierrec/js-xxhash).
There are three basic elements to generate a password:
- master password
- login (usually email)
- click Generate to get 8-character password (smal and capital letters, numbers) plus one special symbol is addititionally attached to address typical requirements of authorization protocols.

When Generate is clicked the app takes master password adds login adds it 2 times more to itself in this way forming enough bites to generate a resistent hash sum and adds that additional sybmol.

How use: create your own system. The master password does not have to me same. In fact it should be differernt. But this app intendent to relief the user to rember or store all passwords you just need to remeber the system. How you form masterpas and what you take as a login for all your services.


## Installation
Download pasgen.html and run localy or your computer or mobile device. Or upload it as page to any server. You can also create a google site and open pasgen.html in notepad, copy and paste the code into the Google Site webpage as a script. Then just bookmark this page or memorize its url. 


## License

MIT
