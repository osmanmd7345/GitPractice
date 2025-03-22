# GitPractice
#reverse string program

#method 1 using slicing

#str="zaid"
#print(str)
#string=str[::-1]
#print(string)


#method 2 using for loop
str= input("enter a str: ")
rev=" "
for i in str:
    rev=i+rev
print(rev)

