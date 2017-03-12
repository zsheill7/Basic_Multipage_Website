## Welcome to GitHub Pages

<p>Prerequisites:</p>
<p>To complete this tutorial, you will need a text editor.  If you don't have one, feel free to download one below.  Brackets is entirely free and great for creating websites.</p>

<a href="http://brackets.io/">Brackets</a>
<a href="https://www.sublimetext.com/">https://www.sublimetext.com/</a>



<p>Now you know how to set up a basic one-page website, but how on earth do you set up a website with multiple pages?  In this tutorial, we're going to learn how to set up a basic multipage website using lists and list items. </p>

<p>First, you want to create a new folder in your Documents directory (or any other directory, for that matter). Open Brackets or another text editor and create a new file.  Name it "index.html"   </p>
<img src="README images/initial folder.png" alt="tutorial image">

<p>Next, open up your text editor and enter the following code.  As we learned in the first tutorial (<a href="https://zsheill7.github.io/Github-Setup-Tutorial/">Github Setup Tutorial</a>), this code sets up the basic structure for a webpage. </p>

<img src="README images/basic html.png" alt="tutorial image">
<p>Next, right click your "index.html" file and select "duplicate" to create the other pages of your app. Feel free to name them anything you want, but make sure they still end with the extension ".html"</p>

<img src="README images/finder screenshot2.png" alt="tutorial image">
<p>Next, create a new folder in your root directory (the folder containing your files) and name it "images." Find several pictures you want to include in the separate pages of your website and place them in this folder.  </p>


<img src="README images/finder screenshot.png" alt="tutorial image">
<p></p>

<img src="README images/list w/o.png" alt="tutorial image">
<p>Right-click your index.html file and click "Open in..."  Select your web browser.  You should have your simple multipage website in front of you!</p>


<img src="README images/basic multipage.png" alt="tutorial image">
<p></p>
<img src="README images/cupcake.png" alt="tutorial image">


<p>If I click on the first link, it takes me to a page with an awesome dab emoji.  Success!</p>

<img src="README images/dab.png" alt="tutorial image">
<p></p>


```markdown
<!DOCTYPE html>
<html>
<head>
	<title>Multipage Website</title>
</head>
<body>

</body>
</html>
```

```markdown
<!DOCTYPE html>
<html>
<head>
	<title>Multipage Website</title>
</head>
<body>
	<nav>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
      </ul>
    </nav>
</body>
</html>
```

```markdown
<!DOCTYPE html>
<html>
<head>
	<title>Multipage Website</title>
</head>
<body>
	<nav>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
              <li><a href="page2.html">Page 2</a></li>
              <li><a href="page3.html">Page 3</a></li>
              <li><a href="page4.html">Page 4</a></li>
              <li><a href="page5.html">Page 5</a></li>
      </ul>
    </nav>
</body>
</html>
```

```markdown
<!DOCTYPE html>
<html>
<head>
	<title>Multipage Website</title>
</head>
<body>
	<nav>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
              <li><a href="page2.html">Page 2</a></li>
              <li><a href="page3.html">Page 3</a></li>
              <li><a href="page4.html">Page 4</a></li>
              <li><a href="page5.html">Page 5</a></li>
      </ul>
    </nav>
    <img width="300" src="images/cupcake.jpg" alt="emoji">
</body>
</html>
```


You can use the [editor on GitHub](https://github.com/zsheill7/Basic_Multipage_Website/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/zsheill7/Basic_Multipage_Website/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
