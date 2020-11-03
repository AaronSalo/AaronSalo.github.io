# How to Host and Format a Resume using Markdown
This Readme will describe how to host and format a resume using _Markdown_ using the techniques described in Andrew Etters' book, _Modern Technical Writing_. The book outlines many important things to keep in mind when doing technical writing. For such a short read, I managed to get a lot out of it. You can get it [here](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS#:~:text=Written%20by%20the%20lead%20technical,and%20experienced%20technical%20writers%20alike.) on amazon.

>**Before Starting**

> Before actually starting anything, make sure to have;
> * Familiarity with Markdown
> * Your resume formatted in Markdown
> * A GitHub account


## Markdown
First things first; it's important to know how to use Markdown before actually writing anything using it. Don't worry, Markdown is extremely simple, and you can learn all the basics in 5-10 mins. I recommend using an online tutorial like [this one.](https://www.markdowntutorial.com/). 

Once you have the basics down, you can use any markdown editor to visualize your work (and make sure you're doing everything correctly). There are many editors out there, as well as extentions you can get for popular code editors such as Visual Studio Code, but [here's](https://stackedit.io/) a great one you can use right in your browser.

## Hosting our Resume
After learning how Markdown works, and writing a nice, clean resume using it, we can finally move into _hosting_ that resume using GitHub Pages. The process is rather simple, and looks very professional given the work taken to do it.


### Step 1: Create a New Repo
First, we need to create a new repository on GitHub, naming it `YourUserName/github.io`. 
gif here


### Step 2: Create an `index.md`
Next we can add an index.md to the repository, and give it a couple lines of test text. This is the default page for your GitHub webpage.
gif here


### Step 3: Choose a Theme!
Finally, we can add the \_config.yml (_yes it has to be named that_). This file can enable some simple themes for jekyll, making our simple static site, looks kinda... beautiful. All it needs to contain is some jekyll theme, and a title of your choosing. Mine has this inside;


### We're Done!
We're done! You can access the page at `yourUserName/github.io`, and it should show anything you put into your `index.md` formatted with the theme you chose. Now all you really have to do is paste your Markdown formatted resume in, or whatever else you want to host there. And... _Voila!_
