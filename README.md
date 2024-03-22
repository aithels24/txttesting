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
