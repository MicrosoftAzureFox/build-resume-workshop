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
    h1 {
        font-size: 3em;
        letter-spacing: .6em;
        padding-top: 1em;
    }

    h2 {
        font-size: 1.5em;
    }

    h3 {
        font-size: 1em;
    }

```

## Step 2: Creating a grid and spacing

CSS grid allow you to place elements on a page using grids to create columns and rows for your data.

We want to create two columns, one for each article grouping.

```css
    main { 
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
        grid-gap: 1em;
        margin-top: 3em;
    }
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
        padding-bottom: 1em;
    }

    @media (min-width: 1000px){
        #mainLeft {
            border-right: 1px solid lightgray;
        }
    }
```

This will split the `main` element into two columns. The first top-level element under `main` which is an `article` will be the first column and will take up 40% of the available space. The second top-level element under `main` (also an `article`) will take up the remaining 60%. It will also add a border to the mainLeft section for larger screen sizes.

## Next steps

You have successfully added style to your resume using CSS. 

To complete your resume, you'll [learn how to host it on a website](./4-creating-website.md).
