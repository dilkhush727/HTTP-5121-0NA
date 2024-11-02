# Files from HTTP-5121
## Web Design
### Course Code: HTTP 5121

### Academic Year: 2025-2026

This course covers the fundamentals of semantic HTML markup and CSS. Students will design and create responsive web interfaces based on mockups that are optimized for accessibility and search engine optimization (SEO).


# links
https://www.w3schools.com/html/default.asp

# Images
![Web Design Overview](webdesign.jpg)

***Notice:*** This repository contains my weekly work for this course. Understanding HTML and CSS fundamentals is crucial for creating effective and accessible web designs.

## Example Code

Here is an example of a simple HTML and CSS snippet used for creating a basic web layout:

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<title>About Dilkhush Yadav</title>

	<style>
		body{
			font-family: sans-serif;
		}
		h1{
			margin-bottom: 5px;
		}
		p{
			font-size: 18px;
			margin-bottom: 20px;
		}
		h1{
			font-size: 40px;
		}
			table{
				border: solid 1px #000;
				border-radius: 4px;
			}
			table thead{
				background-color: #cfcfcf;
			}
			table td{
				border: solid 1px #000;
				padding: 5px;
			}
			footer{
				margin-top: 40px;
			}
		</style>
</head>
	<body>
		<section>
			<div>
				<h1>About Dilkhush Yadav</h1>
				<p><a href="#myCourses">Click here to check my courses</a></p><br><br>

				<img src="assets/dilkhush-image.jpg" height="250" alt="dilkhush">

				<p>
					My name is Dilkhush Yadav. I belong to India. I did my schooling and bachelor's from India. After my bachelor, I joined an IT company in India. I was working there as a <strong>Full Stack Web Developer</strong>.<br><br>
					After some few years of working period, I decided to enhance my development skills so I took a post-graduate course in <a href="https://www.humber.ca/" target="_blank"><strong>Humber</strong></a>.<br>
					<em>I did deep research in finding a better college for my post graduation and finally, I found <strong><a href="https://www.humber.ca/" target="_blank">Humber</a></strong> is one of the best colleges for my skill enhancement.</em><br><br>
				</p>

				<h2 id="myCourses">My Courses-</h2>
				<span>My course details are as following:</span>

				<table>
					<thead>
						<tr>
							<th>Course Code</th>
							<th>Instructor(s)</th>
							<th>Brief Description</th>
						</tr>
					</thead>
					<tbody>
						<tr>
							<td>HTTP 5125, RNA</td>
							<td>Christine Bittle</td>
							<td>
								<ul>
								  <li>Server-side web development</li>
								  <li>C# Programming</li>
								</ul>
							</td>
						</tr>
						<tr>
							<td>HTTP 5126, 0NB</td>
							<td>Matthew Bebis</td>
							<td>
								<ul>
								  <li>SQL</li>
								  <li>MySQL</li>
								</ul>
							</td>
						</tr>
						<tr>
							<td>HTTP 5122, 0NA</td>
							<td>Sean Doyle</td>
							<td>
								<ul>
								  <li>Fundamentals or programming</li>
								  <li>JavaScript</li>
								</ul>
							</td>
						</tr>
						<tr>
							<td>IXD 5106, 0NA</td>
							<td>Momna Sheikh</td>
							<td>
								<ul>
								  <li>Design tools</li>
								  <li>Processes</li>
								</ul>
							</td>
						</tr>
						<tr>
							<td>HTTP 5110, 0NB</td>
							<td>Bernard Monette</td>
							<td>
								<ul>
								  <li>Roles and responsibilities of a Web Developer</li>
								</ul>
							</td>
						</tr>
						<tr>
							<td>IXD 5206, 0ND</td>
							<td>David Neumann</td>
							<td>
								<ul>
								  <li>Techniques required to manage projects</li>
								</ul>
							</td>
						</tr>
						<tr>
							<td>HTTP 5113, 0NA</td>
							<td>Bernard Monette</td>
							<td>
								<ul>
								  <li>Interactive design community</li>
								</ul>
							</td>
						</tr>
						<tr>
							<td>HTTP 5121, 0NA</td>
							<td>Joanna Kommala</td>
							<td>
								<ul>
								  <li>HTML</li>
								  <li>CSS</li>
								</ul>
							</td>
						</tr>
						<tr>
							<td>HTTP 5114, 0NA</td>
							<td>Adam Thomas</td>
							<td>
								<ul>
								  <li>Additional support for content delivered</li>
								</ul>
							</td>
						</tr>
					</tbody>
				</table>

			</div>
		</section>

		<footer>
			<p>© Copyright 2024 | About Dilkhush Yadav. All Rights Reserved.</p>
		</footer>
	</body>
</html>
