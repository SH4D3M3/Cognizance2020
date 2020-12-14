# Algorithm For Detecting an amstrong number within the given range.
___declare integer n___
___declare  another integer as numbers___
___Declare again num which is an integer__
___declare integer orginal___
__Declare sum__
__declare r__
___Give the output as "How many numbers yo are looking for"which is to give the range for your program__
__give input as numbers___
___In a for loop give the condition as n=1 to numbers___
___in the loop initialise sum = 0, num = 0, and assign that orginal=num___
___create a while loop within the for loop and give condition as num=0___
__Whithin the while loop assign that r=numMOd 10 , sum = sum+(r* r* r*) and num= num/10___
___then in the for loop as continuation of while loop give if condition as sum = original__
__whithin the if condition give out put as To string(sum)&is an amstrong number__
__run the program__
__give the range__
