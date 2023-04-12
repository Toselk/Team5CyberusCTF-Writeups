# Team5CyberusCTF-Writeups
Writeups
First of all we inspected the webpage and found the default username and password and logged in into a guest account and found that 
they wanted a higher administrator privilege to access the flag.
the first thing that came to our mind was checking the cookies linked with the guest account and found that the value was encoded and remember that in 
the lesson tab before starting the challenge that the challenge was about the base64 encoding algorithm so we got the value and decoded it and found it 
to mean "login=Guest7"
and then we proceeded to change the value to "login=admin" and encoded it with the same algorithm and changed the value to it.
after all that we got the flag.
