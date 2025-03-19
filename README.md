# week2webdevindex.html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>PLP week 2 webdev assignment</title>
</head>

<body>
	<nav>
		<h2>Week 2 Web Development V2 at PLP</h2>
		<ol type="i">
			<p><b>Modules I enrolled</b></p>
			<li>Software engineering</li>
			<li>Web development</li>
			<li>Python</li>
			<li>Database design</li>
			<li>Startup building</li>
		</ol>
	</nav>
<!--	Image from pexels.com-->
	<img src="https://images.pexels.com/photos/31048476/pexels-photo-31048476/free-photo-of-colorful-mediterranean-style-houses-in-sunshine.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load" alt="Image of a beautifull housse" height="250px" width="300px">
	
	<br><br>
<!--	Line break to separate the contents-->
<!--	Start of table-->
	<div id="table">
	<table border="1">
		<thead>
			<th>Name</th>
			<th>Address</th>
			<th>Mobile</th>
			<th>Email</th>
		
		</thead>
		<tbody>
			<tr>
			<td>Caleb</td>
			<td>80108</td>
			<td>0740481871</td>
			<td>baya2@gmail.com</td>
			</tr>
			
			<tr>
			<td>Mercy</td>
			<td>90708</td>
			<td>0756738476</td>
			<td>mercy@gmail.com</td>
			</tr>
			
			<tr>
			<td>John</td>
			<td>768694</td>
			<td>0746789365</td>
			<td>john@gmail.com</td>
			</tr>
			
			<tr>
			<td>Vivian</td>
			<td>657384</td>
			<td>0778920967</td>
			<td>vivy@gmail.com</td>
			</tr>
			
			<tr>
			<td>Marcel</td>
			<td>809808</td>
			<td>0767859403</td>
			<td>rcel@gmail.com</td>
			</tr>
			
		</tbody>
	</table>
	</div>
<!--	End of table-->
<!--	Line break to separate contents-->
	<br><br>
<!--	Start of form-->
	<div id="form">
		<form>
			<label for ="name">Name:</label>
			<input type="text" placeholder="Your name" required>
			<br><br>
			
			<label for = "email">Email:</label>
			<input type="email" placeholder="you@gmail.com" required>
			<br><br>
			
			<label for = "date">Date:</label>
			<input type="date" required>
			<br><br>
			
			<label for = "password">Password:</label>
			<input type="password" required>
			<br><br>
			
			<label for="gender">Gender:</label>
			<select>
			
				<option>Male</option>
				<option>Female</option>
			</select>
			
			<p>Above 18 years?</p>
			<label for="yes">Yes</label>
			<input type="radio" name="age" required>
			<label for="no">No</label>
			<input type="radio" name="age" required>
			<br><br>
			<label for="confirm">Confirm you are human</label>
			<input type="checkbox" required>
			<br><br>
			
			<button type="submit">Submit</button>
		</form>
<!--		End of form-->
	</div>
	
	

	
</body>
</html>
