# Program-to-Put-Positive-and-Negative-Numbers-in-Separate-List.
NumList = []
Positive = []
Negative = []

Number = int(input(&quot;Please enter the Total Number of List Elements : &quot;))
for i in range(1, Number + 1):
value = int(input(&quot;Please enter the Value of %d Element : &quot; %i))
NumList.append(value)

for j in range(Number):
if(NumList[j] &gt;= 0):
Positive.append(NumList[j])
else:
Negative.append(NumList[j])

print(&quot;Element in Positive List is : &quot;, Positive)

print(&quot;Element in Negative List is : &quot;, Negative)
