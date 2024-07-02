#!/bin/sh
echo "What is your name?" # command for print message
variable_name=variable_value # defining varibale
#Accessing Values
NAME="Zara Ali"
echo $NAME
#=============================**checking directory exist or not if not exist then create**===========================#
if [ ! -d "$dirname" ]
then
    echo "File doesn't exist. Creating now"
    mkdir ./$dirname
    echo "File created"
else
    echo "File exists"
fi


#=============================**File Test Operators**========================================
**-b file** : Checks if file is a block special file; if yes, then the condition becomes true. **Example**: [ -b $file ]
**-c file** : Checks if file is a character special file; if yes, then the condition becomes true. [ -c $file ]
**-d file** : Checks if file is a directory; if yes, then the condition becomes true. [ -d $file ]
**-e file** : Checks if file exists; is true even if file is a directory but exists.[ -e $file ]

#===================================**The if...else statements**============================================
if...fi statement
if...else...fi statement
if...elif...else...fi statement

#=======================================**Loops**=====================================
a=0
while [ "$a" -lt 10 ]    # this is loop1
do
   b="$a"
done


for var1 in 1 2 3
do
  echo "bhuwan"
done


#==============================**Relational Operators**========================================
**-eq** : Checks if the value of two operands are equal or not; if yes, then the condition becomes true. **Example**: [ $a -eq $b ] 
**-ne** : Checks if the value of two operands are equal or not; if values are not equal, then the condition becomes true. **Example** : [ $a -ne $b ]
**-gt** : Checks if the value of left operand is greater than the value of right operand; if yes, then the condition becomes true. **Example** : [ $a -gt $b ]
**-lt** : Checks if the value of left operand is less than the value of right operand; if yes, then the condition becomes true. **Example** : [ $a -lt $b ]
**-ge** : Checks if the value of left operand is greater than or equal to the value of right operand; if yes, then the condition becomes true. **Example** : [ $a -ge $b ]
**-le** : Checks if the value of left operand is less than or equal to the value of right operand; if yes, then the condition becomes true. **Example** : [ $a -le $b ]

#==================**Boolean Operators**===========================
**!** : This is logical negation. This inverts a true condition into false and vice versa. **Example** : [ ! false ]
**-o** : This is logical OR. If one of the operands is true, then the condition becomes true. **Example**: [ $a -lt 20 -o $b -gt 100 ] 
**-a** : This is logical AND. If both the operands are true, then the condition becomes true otherwise false. **Example** : [ $a -lt 20 -a $b -gt 100 ]

#====================**String Operators**============================
**=** : Checks if the value of two operands are equal or not; if yes, then the condition becomes true. **Example** : [ $a = $b ]
**!=** : Checks if the value of two operands are equal or not; if values are not equal then the condition becomes true. **Example** : [ $a != $b ]
**str** : Checks if str is not the empty string; if it is empty, then it returns false. **Example** : 

