# PassCodeHolder2017
# Code to host passcodes in .TXT. 
# Pythonic Code

import easygui as eg

import sys

Codeholder = open("PassCodeHolder.txt",'a')

def reformatPCode(id,passw,urlpage):
    
    return (id + "-" + passw + "-" + urlpage + '\n')

msg = "Please Enter Information"

title = "PassCodeHolder"

fieldnames = ["ID:","Password:","url Link:"]

list1 = eg.multenterbox(msg,title,fieldnames)

if list1 == None or  list1[0] == "" or list1[1] == "" or list1[2] == "":
    
    sys.exit()

id = list1[0]

passw = list1[1]

urlpage = list1[2]

newline = reformatPCode(id,passw,urlpage)

print(newline)

Codeholder.write(newline)

Codeholder.close()
