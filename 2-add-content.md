# Adding content to an HTML page

## Step 1: Update the header

1. Inside **index.html**, change the text "YOUR NAME" to be your name. Change "YOUR TITLE" to your general title - or the title you might like to have - for example, "SOFTWARE ENGINEER".

## Step 2: Creating contact and social media links

✅ What caveats should we consider when adding contact information and social media links to a resume?

1. Inside **index.html**, replace **your-email@example.com** with your email address.
```html
<p>
    <a href="mailto:your-email@example.com">your-email@example.com</a>
</p>
```
1. Repeat this for any social media that you want to add.

## Step 3: Adding Education and Skills

✅ How should you approach adding your skills and education?

Let's fill in the final sections of the resume with your skills, in order of expertise

```html
<p>HTML, CSS, GitHub, VS Code...</p>
```

1. Update the appropriate text to represent your education, with most recent degrees first:

```html
<h3>YOUR MAJOR</h3>
	<p>
	    Your university or school
	</p>
	<p>
		2018-2022
	</p>
```
## Step 3: Your Experience

✅ What should a new developer or a career changer consider when building their professional experience section?

Add as work experience entries, modifying the text as appropriate. 

```html
<h3>JOB TITLE</h3>
    <p>
		Company Name | 2008 - 2010
    </p>
    <p>
		Describe what you did in this position with one summary sentence and no more than 3 bullet points with specific highlights
    </p>
    <ul>
		<li>Cool accomplishment</li>
		<li>Cool accomplishment</li>
		<li>Cool accomplishment</li>
    </ul>
```
## Next steps

You've now added the information for your resume! Now it's time to make it look nice by using [CSS to style the page](./3-add-style.md).
