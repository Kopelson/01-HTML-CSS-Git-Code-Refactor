# Horiseon - The Search Engine Optimization Project

## Description
Horiseon is an artificial marketing agency that wants their code base to follow accessibility standards so that their own site is optimized for search engines. This means adding semantic HTML elements, fixing the logical structure of the website independent of styling and positioning, adding accessible alt attributes to image elements, and adding a descriptive title to the title element.

## What was the motivation?
First, I wanted to build a solid understanding of semantic HTML practices and learn more about modern accessibility standards.
Second, I needed to practice using Git Hub and Git Bash to deploy a live project to the web.
Lastly, I am acquiring hands on experience refactoring code bases and leaving them better than I found them.

## Why did I build this project?
Mainly to display what good semantic HTML may do for a website, and how refactoring can make a website more efficient. Making a website more accessible is great for increasing a SEO (search engine optimization) score and to extend the reach to as many people as possible by having machine readable code. Having semantic HTML tags gives meaning to the structure of a website. This allows for machines to understand what is important in the HTML document. This benifits people with disabilities, people using mobile devices, or those with slow network connections. 

## How did I make the website more accessible?
1. By using semantic HTML tags such as:
`
  <header>
  <nav>
  <main>
  <section>
  <aside>
  <footer>
  <small>
 `

2. Adding image alt attributes to all <img> tags.

3. Changing the head <title> tag to be more descriptive.
  
4. Making a CSS image to have some semantic meaning by using a <span> tag with a role attribute that equals "img" and a aira-lable attribute the equals what the image is about. For example:
 ` 
  <span role="img" aroa-lable="Digital marketing meeting"></span>
 `
5. Refactored CSS to be more efficient by eliminating duplicate code.

## Credits

Thanks to Trilogy Education Services for providing this wonderful opportunity.







