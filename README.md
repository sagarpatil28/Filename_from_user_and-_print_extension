# Filename_from_user_and-_print_extension
#Accept filename from user anf print the extension of that 
filename = input("Input the Filename: ")
f_extns = filename.split(".")
print ("The extension of the file is : " + repr(f_extns[-1]))
