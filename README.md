# txttesting
#THIS READS ALL THE LINES IN THE TXT
def readAll():
    file = open('Testtx.txt', 'r')
    
    all_lines = file.read()
    
    print(all_lines)
    
    file.close()
    
def main():
    readAll()
    
main()

#THE TXT IS NOW A READ BY LINE 
def lineline():
    file = open('Testtx.txt', 'r')
    
    line = file.readline()
    print(line)
    
    file.close()
    
    
def main2():
    lineline()

main2()

# READS THE LINES WHICH GET TURNED INTO ITEMS/NUMBERS
def listread():
    file = open('Testtx.txt', 'r')
    
    wordlist = file.readlines()
    print(wordlist)
    
    wordpick = (wordlist[1])
    print("The line it picked out", wordpick)
    
    file.close()
    
def main3():
    listread()
    
main3()
