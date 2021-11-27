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
```from http.server import HTTPServer, BaseHTTPRequestHandler
content = """
<<doctype!>
<html><head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>time table</title>
</head>
<body>
    <img src="logo.jpg" width="700" height="100"![logo](https://user-images.githubusercontent.com/94184990/143685601-c91757c3-8532-47e6-ac93-d4650ce19d91.png)
>
    <table border>
	<head>
		<tr>
			<th colspan="8">TIME TABLE</th>
		</tr>
		<tr>
			<th colspan="2">Reference number:</th>
			<th colspan="2">21500186</th>
			<th colspan="2">Name:</th>
			<th colspan="2">P.ANITHA</th>
		</tr>
		<tr>
			<th>Days</th>
			<th>8:00-9:00</th>
			<th>9:00-10:00</th>
			<th>10:00-11:00</th>
			<th>11:00-12:00</th>
			<th>12:00-1:00</th>
			<th>1:00-2:00</th>
			<th>2:00-3:00</th>
		</tr>
	</head>
	<body>
		<tr>
			<td>Monday</td>
			<td>Fundamentals of web technology</td>
			<td>Fundamentals of web technology</td>
			<td>Linear algebra laboratory</td>
			<td>Linear algebra laboratory</td>
			<td>Lunch Break</td>
			<td>Mathematics for Artificial Intelligence</td>
			<td>Mathematics for Artificial Intelligence</td>
		</tr>
		<tr>
			<td>Tuesday</td>
			<td>Soft Skills</td>
			<td>Soft Skills</td>
			<td>Engineering Design and Modeling</td>
			<td>Engineering Design and Modeling</td>
			<td>Lunch Break</td>
			<td>Engineering Mechanics and Product Development</td>
			<td>Engineering Mechanics and Product Development</td>
		</tr>
		<tr>
			<td>Wednesday</td>
			<td> - </td>
			<td> - </td>
			<td>Python Programming</td>
			<td>Python Programming</td>
			<td>Mentoring</td>
			<td>Fundamentals of Web Technology</td>
			<td>Fundamentals of Web Technology</td>
		</tr>
		<tr>
			<td>Thursday</td>
			<td>Engineering Mechanics and Product Development</td>
			<td>Engineering Mechanics and Product Development</td>
			<td>Python Programming</td>
			<td>Python Programming</td>
			<td>Lunch Break</td>
			<td>Engineering Design and Modeling</td>
			<td>Engineering Design and Modeling</td>
		</tr>
		<tr>
			<td>Friday</td>
			<td> - </td>
			<td> - </td>
		    <td>Mathematics for Artificial Intelligence</td>
			<td>Mathematics for Artificial Intelligence</td>
			<td>Lunch Break</td>
			<td>Web Technology Laboratory</td>
			<td>Web Technology Laboratory</td>
		</tr>  
		</body></table>
	<ol>
		<li>19AI401	Fundamentals of Web Technology</li>
		<li>19MA221	Linear Algebra Laboratory</li>
		<li>19AI402	Web Technology Laboratory</li>
		<li>19AI301	Python Programming</li>
		<li>19MA220	Mathematics for Artificial Intelligence</li>
		<li>19AI302	Engineering Design and Modeling</li>
		<li>19AI303	Engineering Mechanics and Product Development</li>
		<li>ECA051-AM	Mentoring - AM1</li>
		<li>19EY701	Soft Skills</li>
	</ol>


</body>
</html>

"""
class myhandler(BaseHTTPRequestHandler):
    def do_GET(self):
         print("request received")
         self.send_response(200)
         self.send_header('content-type', 'text/html; charset=utf-8')
         self.end_headers()
         self.wfile.write(content.encode())
server_address = ('',8080)
httpd = HTTPServer(server_address,myhandler)
print("my webserver is running...")
httpd.serve_forever() 
```
 # OUPUT
 ### CLIENT SIDE OUTPUT:
 ![CLIENTSIDEOUTPUT](./clientsidess.png![clientside ss](https://user-images.githubusercontent.com/94184990/143673541-fd97e88e-050c-4440-9f10-4041a1ad6402.PNG)
)
 ### SERVER SIDE OUTPUT:
 ![SERVERSIDEOUTPUT](./serversidess.png)
 ![SERVERSIDEOUTPUT](./serverside3ss.png)
 ![SERVERSIDEOUTPUT](./serverside1ss.png)
 ![SERVERSIDEOUTPUT](./serverside4ss.png)

 ![SERVERSIDEOUTPUT](./serversidess.png![serverside ss](https://user-images.githubusercontent.com/94184990/143673618-c004a371-b3e3-4471-9443-2315eca5c38a.PNG)
)
 ![SERVERSIDEOUTPUT](./serverside3ss.png![serverside 3 ss](https://user-images.githubusercontent.com/94184990/143673582-fb72e028-efaa-4fac-be42-02b088db6e7c.png)
)
 ![SERVERSIDEOUTPUT](./serverside1ss.png![serverside1 ss](https://user-images.githubusercontent.com/94184990/143673594-97f8f7d8-11d4-4db6-a941-9b8dc93284b4.PNG)
)
 ## Result
 Thus, a html webpage is created to display the timetable

 

