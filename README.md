# Experiment_Time_Table

## AIM
To Write a html webpage page to display  your timetable

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
~~~<!DOCTYPE html>
<html>

   <head>
      <title>TIME TABLE</title>
   </head>
	
   <body>
      <table border = "1" cellspacing="1" bordercolor="blue" bgcolor="yellow">
         <tr>
            <th colspan="8">TIME TABLE</th>
         </tr>
         
         <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
             <th>4</th>
            <th rowspan="6">lunch break</th>
            <th>5</th>
            <th>6</th>
         </tr>
          <tr>
             <td>MONDAY</td>
             <td>Accounts</td>
             <td>English</td>
             <td>Statistics</td>
             <td>Banking</td>
             <td align="center">-</td>
             <td align="center">EP</td>
         </tr>
  
         
      </table>
      
   </body>
</html>


~~~
# OUPUT
