# hello-world
Learning to code
Hi Humans

Red hat in training! i prefer Linux and Python
I might not make it, but the hell I won't if I dont try!!

import hashlib
from typing import TextIO

flag = 0

pass_hash = input("Enter md5 hash: ")

wordlist = input("File name: ")

try:
    pass_file:  def add_unicode_checkmark(text: Text) -> Text:
    return text + u' \u2713'   = open(wordlist, "r")
except:
    print("No file found")
    quit()
    
for word in pass_file:
    
    enc_wrd = word.encode('utf-8')
    digest = hashlib.md5(enc_wrd.strip()).hexdigest()
    
    if digest == pass_hash:
        print("password found")
        print("password is " + word)
        flag = 1
        break
    
    if flag == 0:
        print("password")
