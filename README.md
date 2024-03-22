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
