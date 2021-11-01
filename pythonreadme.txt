hi
python tutorial


DATA TYPES:

str : "Hello"
int
float
complex : x=1j
list: x=["sdf","sdf"]
tuple : x=("apple","sdfdf")
range: range(6)
dict: {"sdf":56,"ty":76}
set: {"apple","fro"}
frozenset: frozenset({"apple","bann","cherry"})
bool: x=True


STRING

len(x) : length of string
if "free" in txt : check if text is found in string

if "free" not in txt : check if text is not found in string

SLICE STRING: 
b = "Hello world"
b[start_index : end_index]
e.g b[2:5]
b[:4]
b[2:]

negative indexes start from right to left
e.g b[-4 : -2]


MODIFY STRINGS
Uppercase:
a = "Hello world"
a.upper()

a.lower()

a.strip() //TRIMS SPACE ON LEFT AND WRITE

a.replace("H","J") //REPLACE H BY J

a.split(",") //SPLITS STRING INTO LIST E.G ["Hello","World"]

CONCAT STRING WITH INT
txt = "My name is john, I am {} years old"
age = 45
txt.format(age)


LIST
thislist = ['apple','banana']
len(thislist)

thislist = list(("apple","banana","cherry"))
thislist[0]
thislist[1:2] //ACCESS

thislist.append("orange") //ADD ELEMENT

thislist.insert(1,"orange") //ADD TO INDEX

thislist.extend(anotherlist) //ADD A LIST TO ANOTHER LIST

thislist.remove("banana")
thislist.pop() //REMOVE TOP MOST
thislist.pop(3) //REMOVE AT SPECIFIED INDEX

del thislist[2]
del thislist //DELETE WHOLE LIST

thislist.clear() //EMPTY LIST

//LOOP IN LIST
for x in thislist
	print x

for i in range(len(thislist))
	print x


i = 0
while i<len(thislist)
	i=i+1

//SHORTHAND WAY
[print(x) for x in thislist]


newlist = [expression for item in thislist if condition==True]

newlist = [x for x in fruits if "a" in x]

thislist.sort() //SORT ASCENDING
thislist.sort(reverse=True) //SORT DESCENDING

mylist = thislist.copy()
mylist = list(thislist)  //MAKE A COPY OF AN EXISTING LIST




