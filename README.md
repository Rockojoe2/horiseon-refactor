# <horiseon-refactor>

## Description

We were given an index.html and style.css file which was the webpage for a company called Horiseon. 

<img src="./assets/images/Read-Me-Images/Horiseon-1.jpg"/>

The code that was given to us using non-semantic coding with everything using "div". We want to use semantic coding for this website because a company wants to rank highly on the Google search engine, which semantic coding helps with greatly.

The motivation behind this project was to practice with semantic coding, and giving a shot at cleaning up someone else's code. There are many different ways to get what you want to show up, but some ways are more efficient than others.

This project solves Horiseon's problem of not being able to rank highly in search engines because of poor SEO. Their content was not appearing highly in the google search engine because there was no keywords to match due to the fact that "div" has no meaning in the google search engine at all. With semantic coding, you can give keywords like "this is the title", "this is the body", etc. "Div has no special meaning and doesn't lead the search engine anywhere.

With this project, I learned how to be more efficient with my coding and how to read other people's code. In this project, I went through two iterations that both worked. The first iteration however was not as efficient and took up more lines of code. Example being

First Iteration

html file

<header class="header">
</>

style.css file

.header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

Here, I used the semantic header, and then called the class header in the css file. However, I could be a bit more efficient and get the same results if I did the following

Second Iteration

html file
<header>
</>

style.css file

header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

Instead of calling the class file, I just made it an element and had it whenever the element was called upon, the following format and color would be called upon. 

Although it's not that many lines saved, in a big project if you could be efficient with your code, you can save tons of time and memory.

## Installation

N/A

## Usage

Horiseon's website educates users on how to run a company by managing their online website. SEO, Online Reputation Management, and Social Media Marketing are all important in any company's growth. 

## Credits

N/A

## License

N/A

---

