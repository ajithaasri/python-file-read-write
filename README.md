# python-file-read-write

# Program to write to a file, append data, and read its contents

# Writing to the file
f = open('myfile.txt', 'w')
f.write('My first file')
f.close()

# Appending data to the file
f = open('myfile.txt', 'a')
f.write('\nWelcome Every one')
f.write('\nAppend Mode')
f.close()

# Reading and displaying file contents
f = open('myfile.txt', 'r')
print(f.read())
f.close()

OUTPUT:

My first file
Welcome Every one
Append Mode
