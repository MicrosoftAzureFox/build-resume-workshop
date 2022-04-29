# Adding style using CSS

CSS, or Cascading Stylesheets, is used to provide style - it's the 'skin' of your web page.

✅ How 'aesthetically pleasing' does your resume need to be?

## Step 1: Adding a style sheet

1. Hover over the name of your repository, **resume**, in the Explorer pane on the left-hand side of your screen, then select the **File with +** icon. Name the file **style.css**.
1. Inside **style.css**, add the following CSS to choose the font and size

    ```css
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        font-size: 12px;
        max-width: 960px;
        margin: auto;
    }
    ```

## Step 2: Typography

Let's set the size for our three different header elements. 

1. At the bottom of **style.css**, add the following...

    ```css
    h1 {
        font-size: 3em;
        letter-spacing: .6em;
        padding-top: 1em;
        padding-bottom: 1em;
    }

    h2 {
        font-size: 1.5em;
        padding-bottom: 1em;
    }

    h3 {
        font-size: 1em;
        padding-bottom: 1em;
    }

    
    ```

## Step 3: Creating a grid

CSS grid allow you to place elements on a page using grids to create columns and rows for your data.

We want to create two columns, one for each article grouping.

    ```css
        main { 
            display: grid;
            grid-template-columns: 40% 60%;
            margin-top: 3em;
        }
    ```

This will split the `main` element into two columns. The first top-level element under `main` which is an `article` will be the first column and will take up 40% of the available space. The second top-level element under `main` (also an `article`) will take up the remaining 60%.

## Step 4: Controlling spacing

Add some padding around the elements on your page:

    ```css
    header {
        text-align: center;
        margin: auto 2em;
    }

    section {
        margin: auto 1em 4em 2em;
    }

    i {
        margin-right: .5em;
    }

    p {
        margin: .2em auto
    }

    hr {
        border: none;
        background-color: lightgray;
        height: 1px;
    }

    h1, h2, h3 {
        font-weight: 100;
        margin-bottom: 0;
    }
    ```

## Step 5: Selecting an element by ID

Add a border to just the left column by adding this final rule to your stylesheet:

    ```css
    #mainLeft {
        border-right: 1px solid lightgray;
    }
    ```

Your resume should look much better now. However, you're still missing some icons in the CONTACT section. For that, we'll need to add an icon font.

## Step 6: Add an icon font

An icon font is a font that contains symbols and glyphs instead of letters and numbers. 

1. In the **index.html** file, add the following line to the `head` element...

    ```html
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    ```

## Next steps

You have successfully added style to your resume using CSS. 
To complete your resume, you'll [learn how to host it on a website](./4-creating-website.md).
