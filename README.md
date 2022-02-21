# ASS-1-21-02-22
PATTERN PROGRAM FOR ALPHABET
n=int(input())
for i in range (1,rows+1):
    for space in range(rows-i):
        print('',end='')
    for j in range (1,2*i):
    print('0',end="")
    print()
    OUTPUT:
    enter number:4
    a b c d
    e f g h
    i j k l
    m n o p
