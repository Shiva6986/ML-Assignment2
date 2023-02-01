# ML-Assignment2
Video Demo Link: https://drive.google.com/drive/folders/1tQYJ_m5LhmtF13fW3toti4PwBus-0tkI?usp=share_link

DESCRIPTION:
PROGRAM 1:
Used a python code to display the following star pattern using for loop 
used rows=5 and for i range 0,rows
for j in range(0,i+1)
printed "*" and end=''
printed "/r"

PROGRAM 2:
used looping to output the elements from a provided list present at odd indexes.
my list is 10,20,30,40,50,60,70,80,90
stat from index 1 with step 2(means 1,3,5,an so on)
for i in my_list[1::2]
printed (i, end="")
output:20 40 60 80 100

PROGRAM 3:
written a code that appends the type of elements from the given list 
input x=[23,'python',23.98]
n=[]
for i in range(len(x)):
n.append(type(x[i]))
print(n)
print(x)
output: [23,'python',23.98]
[<class 'int'>,<class 'str'>,<class 'float'>

PROGRAM 4:
written a function that takes a list and returns a new list with unique items of the first list
def unique_list(l);
x=[]
for a in l;
if a not in x:
x.append(a)
return x
printed(unique_list ([1,2,3,3,3,3,4,5]))
output: 1,2,3,4,5

PROGRAM 5:

def string_test(s):
    d={"UPPER_CASE":0, "LOWER_CASE":0}
    for c in s:
        if c.isupper():
           d["UPPER_CASE"]+=1
        elif c.islower():
           d["LOWER_CASE"]+=1
        else:
           pass
    print ("Original String : ", s)
    print ("No. of Upper case characters : ", d["UPPER_CASE"])
    print ("No. of Lower case Characters : ", d["LOWER_CASE"])

string_test('The quick Brown Fox')
output:Original String :  The quick Brown Fox
No. of Upper case characters :  3
No. of Lower case Characters :  13

