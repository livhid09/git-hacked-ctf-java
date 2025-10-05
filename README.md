# git-hacked-ctf-java
Welcome to our CTF for Intro to Cyber Security
## How to start
1) Download `project_files.zip` and unzip it.
2) Open `project_files/todo.txt`. Decode the last line as base64:
   `tail -n 1 todo.txt | base64 -d`
3) Use that output as the password for `secret.zip`.
4) Count how many times the word `password` appears in `wordy/big_text.txt`:
   `grep -oi 'password' wordy/big_text.txt | wc -l`
5) ROT13 the text `Cnffjbeq` → use that as a password for `rot13/secret3.zip`.
6) Collect the four fragments (in folder order), concatenate them (no spaces), and use as the password for `final.zip`.
