# PassCodeHolder2017
# Code to host passcodes in .TXT. 
# Pythonic Code


Codeholder = open("PassCodeHolder.txt",'a')

def reformatPCode(id,passw,urlpage):

	return (id + "-" + passw + "-" + urlpage + '\n')


id = input("Please input user name: ")

passw = input("Please input passcode: ")

urlpage = input("Please input URL: ")


newline = reformatPCode(id,passw,urlpage)

print(newline)

Codeholder.write(newline)

Codeholder.close()
