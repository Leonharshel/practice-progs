# practice-progs
ds in python


# program no 2 in ds lab-man
#prog to read strings and replace the pattern string with main string if found
print("enter the main string")
strg = input('string: ')
print("enter the pattern string")
patt = input('pattern string: ')
print("enter the string to replace if the pattern string is found")
replace = input('string to replace: ')
print('the length of the main string is ',len(strg))
print('the length of the pattern string is',len(patt))
print('the length of the string to replace is',len(replace))
if((patt in strg)== True):
    print('the pattern string is found')
    print(strg.replace(strg,replace))
    print(strg)
else:
    print('the pattern string is not found')
    
    
