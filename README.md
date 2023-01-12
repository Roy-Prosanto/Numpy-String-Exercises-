# Numpy-String-Exercises-
this is Numpy (String  Exercises ). make your level grow up . And you learn new some things 
import numpy as np

# Problem 01 Two String add
Array1=np.array( ['Python' ,'PHP'] ,)
Array2=np.array([' Java' ,' C++'])

array3=np.char.add(Array1,Array2)
print(array3)

# Problem 02 repeat
Array4= np.array(["Python","PHP","Java","c++"])
Array5=np.repeat(Array4,3)
print(Array5)
array6=np.char.multiply(Array4,3)
print(array6)

#Problem  03 (Tital ,upper ,lower,swapcase)
Array07=np.array(['python', 'PHP' ,'java', 'C++'])
Array08=np.char.capitalize(Array07)
print(Array08)
Array09=np.char.lower(Array07)
print(Array09)
Array010=np.char.upper(Array07)
print(Array010)
Array011=np.char.swapcase(Array07)
print(Array011)
Array012=np.char.title(Array07)
print(Array012)


# Problem 04 paddings of "-"
Original_Array=(['python exercises' ,'PHP' ,'java' ,'C++'])
Original_Array1=np.char.ljust(Original_Array ,15,fillchar="-" )
print(Original_Array1)
Original_Array2=np.char.rjust(Original_Array ,15,fillchar="-" )
print(Original_Array2)
Original_Array3=np.char.center(Original_Array ,15,fillchar="-" )
print(Original_Array3)

# problem 05 ( space between characters)
Array21= np.array(["Python","c++","jave"])
np1=np.char.join("-",Array21)
print(np1)



# problem  06 (decoding  ,Encoding  )
encoders=np.array([b'\x97\xa8\xa3\x88\x96\x95@\x85\xa7\x85\x99\x83\x89\xa2\x85\xa2'
b'\xd7\xc8\xd7' b'\x91\x81\xa5\x81' b'\xc3NN'])

x = np.array(['python exercises', 'PHP', 'java', 'C++'])
e = np.char.encode(x, encoding='cp037')
print(e)
decoder=np.char.decode(encoders,encoding='cp037')
print(decoder)
print("Decode")

# Problem 07 remove the leading

x = np.array([' python exercises ', ' PHP  ', ' java  ', '  C++'])
x1=np.char.strip(x)
print(x1)

# problem 08
x2=([' python exercises ', ' PHP  ', ' java  ', '  C++'])
x3=np.char.lstrip(x2)
print(x2)

# Problem 10
x = np.array([' python exercises ', ' PHP  ', ' java  ', '  C++'])
x1= np.char.rstrip(x)
print(x1)

# Problem 11 (
Sample_output=np.array(['Python\\Exercises, Practice, Solution'])
Original_Array=np.char.split(Sample_output)
print(Original_Array)

# Problem 12

x = np.array(['2', '11', '234', '1234', '12345'])
r = np.char.zfill(x, 5)
print(r)


# Problem 13 Replace 
Array=np.array(
['PHP Exercises, Practice, Solution'])

Array1= np.char.replace(Array,"PHP","Python")
print(Array1)

# Problem 14
Array1= (['Hello' ,'PHP', 'JS' ,'examples' ,'html'])
Array2=(['Hello' ,'php', 'Java', 'examples', 'html'])
equal= np.char.equal(Array1,Array2)
print(equal)
print("Part 01")
notequal=np.char.not_equal(Array1,Array2)
print(notequal)
print("Part 02")
greaterequal=np.char. greater_equal(Array1,Array2)
print(greaterequal)
print("Part 03")
r = np.char.greater_equal(Array1,Array2)
print(r)

# Problem 15 count "P"
Input=np.array(['Python', 'PHP' ,'JS' ,'examples', 'html'])
inp=np.char.count(Input, "P")
print(inp)

# Problem 16
input1=np.array(['Python', 'PHP', 'JS' ,'EXAMPLES', 'HTML'])
input2=np.char.find (input1,"P")
print(input2)

# problem 17 (Digite , lower , upper True false )
Original=np.array(['Python', 'PHP', 'JS', 'Examples', 'html5' ,'5'])
Digits=np.char.isdigit(Original)
print(Digits)
print(" Part 01 ")
Lower = np.char.islower(Original)
print(Lower)
print(" Part 02 ")
Upper=np.char.isupper(Original)
print(Upper)

# Problem 18  Whether
Sample =np.array(['Python', 'PHP', 'JS' ,'examples', 'html'] )
Sample1=np.char.startswith(Sample,"P")
print(Sample1)
"""
string  = np.array([['Python', 'NumPy' ,'Exercises'],
 ['Python', 'Pandas', 'Exercises'],
 ['Python' ,'Machine learning' ,'Python']])

np= np.char.count(string,"Python")
print(np)
"""




