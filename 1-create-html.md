# Create an HTML page

You will begin to build your resume by creating an HTML (HyperText Markup Language) file and adding the code. HTML is the 'skeleton' of your webpage.

## Step 1: Create an HTML file with CodeSwing

1. Open the **Command Palette** by selecting the three parallel lines icon in the left-hand side Activity Bar, then navigating to **View > Command Palette**.
1. Type **CodeSwing**, then select **CodeSwing: Initialize Workspace as Swing**.
1. Choose the option for **Basic: HTML-Only** and your new swing will appear, with your HTML file on the left and a browser window on the right.
1. This will create an **index.html** file in your root directory.

> **IMPORTANT** If you accidentally close the wrong windows, you can re-open CodeSwing by navigating to your repository in github.dev, opening the Command Palette with **Control+Shift+P** (or **Command+Shift+P** on a Mac), typing **CodeSwing**, selecting **CodeSwing: Open Swing...**, and selecting the directory with your files.

You now have the HTML file created for your resume site!

## Step 2: Create the HTML structure

Let's start adding the HTML for our page. Every HTML page includes three main tags - `html` which contains all the HTML, `head` which includes information about the page, and `body` which contains the contents to display on the page. Tags can also contain **attributes**, which allow us to change how a tag behaves. Attributes are key/value pairs such as `rel="stylesheet"`.

1. Inside the **index.html** window, add the following code to create the initial structure of your page, replacing **Your Name** in the `<title>` tag with your name:

```html
<html>
	<head>
		<link href="style.css" rel="stylesheet">
		<title>Your Name resume</title>
	</head>

	<body>
		<header id="header">
		<!-- resume header with your name and title -->
		<h1>YOUR NAME</h1>
			<hr>
				YOUR TITLE (EX: SOFTWARE ENGINEERING STUDENT)
			<hr>
		</header>
		<main>
			<article id="mainLeft">
				<section>
					<h2>CONTACT</h2>
					<!-- contact info including social media -->
				</section>
				<section>
					<h2>SKILLS</h2>
					<!-- your skills -->
				</section>
				<section>
					<h2>EDUCATION</h2>
					<!-- your education -->
				</section>            
			</article>
			<article id="mainRight">
				<section>
					<h2>WORK EXPERIENCE</h2>
					<!-- your work experience -->
				</section>
			</article>
		</main>
	</body>
</html>
```

✅ Contact, Skills, Education and Experience. Are these the most important things to add to your resume?

## Next Steps

You've now created your first HTML page! Next, [add additional content](./2-add-content.md) such as your email address and sections for your professional experience.
