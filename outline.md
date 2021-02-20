# Build Your First Website Workshop Outline

Purpose of this meetup is for beginners to start familiarizing with HTML and CSS. (No prior coding skills are needed for this workshop so be show to be slow and elaborate on tooling/location of keys/terminology on keyboard and general concepts.) General style of this workshop is to follow along with your instructions.
  
During the workshop they will learn:  
- Fundamentals of coding  
- Basics of HTML  
- Basics of CSS  
- Bootstrap and Mobile-Responsive Websites  
- Bring everything together and code your first website!  
  
Some requirements they'll be asked to have for the workshop:  
- A computer: Windows (8 - 10) or Mac  
- [Chrome Web Browser](https://www.google.com/chrome/)
- A stable internet connection  
- A code editor, we recommend VSCode: [https://code.visualstudio.com/](https://code.visualstudio.com/)

## Code of Conduct

Learn Academy's Code of Conduct is usually introduced by the event host. 
**However, highly encourage attendees to ask questions at any point. Ensure this is a safe environment for learning. "There are no stupid questions. If you have a question, there's high likelihood someone else also has the same question."**

## Brief intro to yourself
## Fundamentals of Coding

What is coding? Coding is using computer language to describe a set of instructions that computers can understand and can perform. Not all computers understand all programming languages. However, most modern computers allow you download and use web browsers like Chrome, Explorer, Firefox, or Safari which can process the three main languages used to build websites: HTML, CSS, and Javascript. For this workshop, we'll be covering HTML and CSS. (Javascript will be covered in Jumpstart if there is more interest in making your website more dynamic and have more user interaction.)

## HTML & CSS Overview

### What is HTML?

 - HyperText Markup Language
 - HTML is the structure of the website.
 - The HTML code we'll be writing is also about organizing the content on our website.
 - Computer languages have versions because its developers want to improve it. The current version of HTML we'll be using is HTML5.
 - One of the main benefits of HTML5 we'll be encountering today is its support for semantic markup.
 - What does semantic markup mean? It means we're using terms to more clearly indicate purpose and meaning of content on our website. Older versions of HTML isn't as human-friendly as HTML5. You'll see in a bit that HTML uses English terms to describe the content on the website.

### What is CSS?
- Cascading Style Sheets
- CSS is the presentation of data.
- The CSS code is for describing how content is presented (e.g. colors, fonts, font-sizing, shapes).
- The current version of CSS we'll be using is CSS3
- CSS3 improvements involve responsive-support or mobile-friendly support.

### HTML & CSS
- HTML & CSS work together to build a static (limited user interaction) website.

## Wireframe
- Common practice in web development usually involves a wireframe or an understanding of how we want our webpage to look and what content will be on it
- In most companies, there will be a User Interaction/User Experience Designer or team or Project Manager responsible for providing these wireframes/mock-ups to developers as a basis for developing.
- User Experience designers have studied how people use web applications and things that help with making applications easier to use. 
- Webpages typically have:
	- Header (something to grab the attention of the user)
	- Body (informational content)
	- Footer (copyright information or company information)
- Show a wireframe of their mini-portfolio [Example of the wireframe](https://github.com/LEARNAcademy/build-your-own-website/tree/build-your-first-website-mina/one-page-portfolio)
- Describe general elements of the web 
	- Title on Tab
	- Heading section
	- Paragraph section
	- Image content with description
	- Another Paragraph section with a subheader
	- Footer
- Main thing to recognized about the layout is that it consists of sections that are like rows stacked on top of each other.

## Creating a project
- A website requires multiple files that will work together.
- First, step is to create a directory. (Right/Double-finger click on desktop to see the menu for New Folder) 
- Name the directory **first-website** (Talk about naming convention for files: spaces is discouraged because computers and different programs tend to process spaces differently.)
- Open VS Code to open the directory we just created.
- You can open the folder using the Start menu option > Open Folder... or File > Open... > Select first-website folder > Click Open button
- In VS Code, we'll create a file using the New File icon.
- The first file we'll create is an HTML file. Let's name it `index.html`
- Press enter to create the file.
- `index` is a specific word that the browser understands to mean "the first page". We can use different words to create an html file, but for starters we'll stick with `index`.
- `.html` (dot html) is to signify the extension or type of file. Similar to how you might have worked with Word documents that end with `.doc`
- It's important to indicate the extension of a file because not all program can process all kinds of files. Your web browser though knows how to process an `html` file.

## Text Editor
- Before going further, let's taught about why we're using VS Code.
- Technically we can make an html document using Word but Word is a program that doesn't have tools to help you write code easily. So the benefit of using a text editor like VS Code is because as we're typing code, it can provide us suggestions related specifically to html.
-  VS Code was developed by developers who best understand the needs of developer and created features to support easy coding.

## HTML
- We should now see the html file nested within our first-website folder.
- We can now type `html` and already, we'll see VS Code making a suggestion! 
- Let's select `html:5` because that's the latest and greatest version. Press Enter.
- You'll see that code automatically populates in the file. 
- What we're looking at is called **boiler plate** code --the minimum amount of code needed to get a program running. This is what boiler plate code looks like for a webpage.
- Let's examine it.
- `<!DOCTYPE  html>` is something an html file needs to include in order to tell the web browser what kind of file it is. Technically, the browser doesn't need it but it's good practice to have it.
- You might notice there are a lot of greater-than and less-than characters. These are usually referred to as **angle brackets** or **carets**. This is essential to the syntax of html.
- `<html  lang="en">` This line indicates a section for where all of our html code will live. Notice that there is another line of code at the bottom of the file: `</html>` . `html` here is a **tag** that denotes the purpose of the element. 
- The general syntax involves **matching opening and closing tags**. Line 2 is an **opening tag** and Line 12 is a **closing tag**.
- `lang="en"` is denoting the language being used on this page. `en` for English.
- `<head>` is another tag. Any html provided within the opening and closing head tags are used to provide information to the browser and to the internet about our website. 
- `<meta charset="UTF-8">` some tags do not require a closing tag, `meta` is one of those **self-closing** tags. The reason for this is because the opening and closing tags is to indicate a grouping of tags whereas tags like meta is not expected to group tags rather it just a statement of some information. `meta` in English means "Making or showing awareness of reference to oneself". So here we have code that knows what kind of charset: character set is being used. UTF-8 is the most common.
- Next meta tag: something about compatibility because while IE is an old browser it's still widely used. We won't focus on it much because we don't have to change it. Same with the next meta tag.
- `<title>Document</title>` allows us to indicate the title of the page displayed in the browser tab.
- Before we do anything. At this point, let's look at what this code looks like in the browser.
- First, let's save the file by using a shortcut (cmd + s or ctrl + s). You'll be needing to do this a lot during development so having a quick say to do it will make things easier. The white dot next to the file name should go away after it's saved.
- Next, we need drag our file into the browser in the URL bar. Press Enter.
- Notice, nothing is displayed within the browser window but that the browser tab has a title of "Document".
- Let's change it to "My First Webpage" by going back to our html file and where the title tag is located change it from "Document". Save and go to the browser and refresh by using the Refresh button or using cmd + r or ctrl + r. Refreshing the browser will reload the latest version of your html file.
- So we've updated the title of the page.
- For all of the content that we want actually displayed on in the browser window, we'll need to provide some html within our body tags.
- The first thing we'll do is add a heading using an `h1` tag and the content like so `<h1>Welcome to my first website!</h1>`
- `h1` stands for "first heading"
- *It's also a good idea to maintain a clean indentation pattern by making sure matching opening and closing tags are aligned and nested tags are indented further.*
- *Also as a developer, it is not a good use of your time and mental energy to memorize all these tags. You may come to memorize them through repetition but most developers don't actively try to commit them to memory because HTML tags are documented and available to you on the internet. A simple Google search for "html tags" will yield many options for documentation.*
- `p` tag stands for "paragraph".
- Because I don't have text content ready I can used generated placeholder text that looks like paragraph text but doesn't really mean anything. It is usually referred to as **Lorem Ipsum**.
- There are many options on the internet so we can do a Google search for *funny lorem ipsum*
- So I'll go ahead and copy this paragraph using another shortcut (cmd +c or ctrl + c) and paste (cmd + p or ctrl + p) it in between the  paragraph tags.
- It will make it look like all the code is missing. That's because our text isn't automatically wrapping like it does in Word. You can scroll to the left and you'll see all your code. We'll also make our text-edit wrap text from now on by going to the View menu at the top and select "Toggle Word Wrap". You'll see that it wraps the text into view.
- Let's save. (cmd + s / ctrl + s) and go to the browser and refresh (cmd + r / ctrl + r). You should now to see the heading and paragraph.

## Linking CSS

- So at this point, it looks quite boring. This is where CSS comes into play. For that we'll need to create a CSS file.
- Again with using the New File icon, we'll name this `styles.css` with a css extension.
- To allow CSS and HTML we need to link the files by using a `link` tag within our `head` tag.
- `<link rel="stylesheet" href="styles.css">` above the `title` tag.
- Here, we're indicating a `rel` attribute which allows us to provide information that will modify or apply information to the element. The value we provide for the attribute must always be wrapped within double-quotes. The value of `stylesheet` indicates how the html document will interact with the file we're linking to. `href="styles.css"` allows us to provide a way for the browser to identify the location of the file.
- Let's save now since we're going to add something to our css file.

## CSS
- In CSS, we have to *target* the tag we have to style. There are many ways to do this, but one way of doing this is using the tag as a **selector**.
- So in our CSS file, let's *select* the `h1` tag and style it's font-size, font-style, and color.
- CSS syntax also include **curly braces/brackets** in between which we provide **CSS properties** and values followed with a semi-colon after each property-value pairing or what's common referred to as `key-value pairs`:
```css
  h1 {
    font-size: 24px;
    font-style: italic; 
    color: cornflowerblue; 
  }
```
- Save and Refresh.
- Let's put some spacing around the paragraph.
```css
  p {
    padding: 20px;
  }
```
- Save and Refresh.
- So the common workflow is that as we add tags to our HTML file, we target them in our CSS file and provide properties that change the presentation of that tag.
- With spacing in CSS, it's important to know about a fundamental concept called the **box model**.
- [Box Model](https://www.w3schools.com/Css/css_boxmodel.asp)
- I could have used `margin` instead of `padding` to provide spacing because I'm not providing a border but something to consider is whether I later on will always want space between the border and content should I add a visible border.
- Another way of targeting HTML elements is through a **class selector**.
- In our HTML file, I can provide a `class` HTML attribute and a class name (something we make up). So I'll just duplicate another paragraph and on the second one add `class="second-paragraph"`. Save.
- In the CSS file, to target an HTML with a class of `second-paragraph` I denote it with a `.` (e.g. `.second-paragraph`)
- Let's wrap these two paragraphs with a `section` tag to group them together. 
- Let's revisit our [wireframe](https://github.com/LEARNAcademy/build-your-own-website/tree/build-your-first-website-mina/one-page-portfolio)
- The header portion has this big display which is quite common for websites. So much so that the people of Twitter decided they were going to build a library of html and css code that solve common problems or simplify tasks in web development. Introducing Bootstrap.

## Bootstrap
- Twitter was generous enough to share their pre-written HTML and CSS to save developers a lot of headache. A lot of companies style their webpages and applications using Bootstrap. 
- Another common problem Bootstrap is solving with their library is the need to make websites *responsive* and *mobile-friendly* so we'll check for that later on.
### Using Bootstrap
- Visit [https://getbootstrap.com/](https://getbootstrap.com/) and usually you'd click the "Get Started" button but because they've recently released a beta version of their library (beta is more of an exploration version likely to include some buggy behavior that they're still sorting out) we'll use the latest stable version 4.6. So click **[v4.6.x docs](https://getbootstrap.com/docs/4.6/getting-started/introduction/)**
- **Note: version 5 deprecates the Jumbotron :(**
- Copy the html link tag provided under the CSS section:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css" integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l" crossorigin="anonymous">
```
- Paste this just above the `link` tag we added earlier.
- This link tag allows us to use Bootstrap's style sheets (in addition to our own).
- In the JS section, it says to use one of the following Bundle/Separate: we'll just use Bundle. Let's copy the `script` tag and place it write above the closing `body` tag.
```html
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-Piv4xVNRyMGpqkS2by6br4gNJ7DXjqk09RmUpJ8jgGtD7zP9yug3goQfGII0yAns" crossorigin="anonymous"></script>
```
- Let's save our HTML file and refresh to view changes.
- The font styling changes because Bootstrap stylings are already being applied but they can also be overwritten for customization.

### Bootstrap Jumbotron
- So for that big header, we'll use a Bootstrap Jumbotron. 
- Navigate: *Components > Jumbotron*
- Let's update the `h1` in the Jumbotron code and remove the old one. And remove a few other elements in here we're not using.
- At this point, we can check what this looks like with different window widths.
- And use the mobile simulator in **Chrome Developer Tools** to see the **responsiveness** that Bootstrap is affording us.
- Right/Double click **Inspect**. Click **Toggle device toolbar** and test out the different devices.
- Let's add a background image to the Jumbotron. 
- The main element has a class of `jumbotron` but this is Bootstrap's class and when working with a **third-party library**, or any software where we don't have control over, we want to provide some delineation between Bootstrap's css and our css, so we won't reuse that class. Instead, we'll just add another one: `my-background-image` 
- And add a `background-image: url();`
- [https://unsplash.com/](https://unsplash.com/) is a popular site for getting beautiful royalty-free images--meaning we don't have to pay or credit someone to use these images.
- Look for landscape images for jumbotron.
- It's important to Copy Image Address and not just the image or the URL display in the URL bar because the addresses is not always the same. 
- Add some styling for the background image:
```css
  .my-background-image {
    background-image: url(https://images.unsplash.com/photo-1546238232-20216dec9f72?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2507&q=80);
    background-size: cover;
    background-position: center;
    height: 400px;
    border-radius: 0; /* overriding Bootstrap */
  }
```
- This image makes the text not that easy to read so we can do some more CSS to make that text pop.
- For the `h1` and `p` instead the jumbotron class, we'll add a class of `white-dropshadow` the styling which will be applied to box elements. This is the benefit of using a class-selector instead of a tag-selector because you can apply styles to different and many tags.
```css
  .white-dropshadow {
    color: white;
    filter: drop-shadow(3px  6px  4px  black);
  }
```
- Filter is a fun CSS property and I highly recommend you play with it because offers many different options. [CSS Filter](https://www.w3schools.com/CSSref/css3_pr_filter.asp)
- Remove the `color: cornflowerblue;` from `h1` styles because it is no longer being applied to the end result.
- Let's revisit our [wireframe](https://github.com/LEARNAcademy/build-your-own-website/tree/build-your-first-website-mina/one-page-portfolio) again.
- Because we know we have a section for cards, let's use another `section` tag to group all of our cards.
### Bootstrap Card
- There are many options that Bootstrap provides for cards. A card is a term used to describe a specific component in web design that looks like a small section of text information with or without an image.
- Let's use the one with just an image and text (no button) because that looks more similar to our wireframe.
- Copy and paste it three times. Ensure the `div` tags are correctly aligned. Also this is a good time to check on your indentation.
- Add image to each card: using the `img` tag and the `src` attribute.
- Notice there's more spacing in our paragraph text in the card section than is displayed in the Bootstrap website. This is because our earlier styling for our `p` is being broadly applied to all `p` tags so we should apply our `p` styling more specifically using a class so that it does not conflict with styles that Bootstrap has provided.
```css
  .my-paragraph {
    padding: 20px;
    margin: 0; /* overriding bootstrap */
  }
``` 
- So CSS will automatically stack the cards on top of each other. We want to make it so they're displayed in a row. Luckily, CSS makes this easy for us to do. (This wasn't always the case.) 
- On the section containing the cards, we'll add a class of `my-cards-container` and apply the following styles:
```css
  .my-cards-container {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
  }
```
- `display: flex;` is a special and commonly used CSS property-value for styling nested HTML elements within an element. This is why we put the class style on the `section` tag and not on the cards.
- In desktop view this looks good, let's check out mobile views. Looks like they're still squished into a row. Let's make it stack again but only for mobile-view.
- One way to achieve this is through **CSS media queries** which allow us to create a rule that checks the dimensions of the screen size and applies different styling if that rule is met.
```css
  @media only screen and (max-device-width: 480px) {
    .my-cards-container {
      display: flex;
      flex-direction: column;
      margin: 20px;
    }
  }
```
- This rule is saying "based on the screen, when the screen width is less than 480px, apply the following styles".
- Notice that we're reusing the `.my-cards-container` selector.
- Let's add spacing around the cards within the media query as well:
```css
  .my-cards-container .card {
    margin-bottom: 20px;
  }
```
- The selector we're using here is a **descendant selector** which is actually the space between two classes. What's happening here is CSS will select all elements with a class of `card` that are a **child** or nested within an element with a `my-cards-container` class.
- Let's revisit our [wireframe](https://github.com/LEARNAcademy/build-your-own-website/tree/build-your-first-website-mina/one-page-portfolio) yet again.
## Third Section
- Let's add another `section` tag.
- Add a nested `h3` tag since we want this heading to be smaller.
- Borrow the paragraph from the above section to add a nested `p` tag 
- Add styling for the section:
```css
  .third-section {
    margin: 20px;
  }
```
## Footer
- Add a `footer` tag and some text.
- Add some styling:
```css
  footer {
    margin: 20px;
  }
```

## Next Steps
- Play around with CSS more and reference documentation online. YouTube is also a great resource.
- Mention next Jumpstart which includes Javascript and deploying a website build over the weekend so that it's accessible through the internet
