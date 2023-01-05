---
title: "Exercise: HTML Intro"
slug: "/html-intro-exercise"
---

[Exercise Repo](https://github.com/Bryantellius/HTML_Exercise)

## Objective

Practice using HTML tags to structure a content on web pages.

## Exercise 1

Steps are to be completed under the div with `id="exercise1"`

1. Create a **heading 1** element that contains your name between opening and closing tags
<h1>DeAdrien Hill</h1>
2. Create a **paragraph** element that contains a bio about yourself

<p>Now this is a story all about how
my life got flipped turned upside down
and I'd like to take a minute, just sit right there
I'll tell you how I became the prince of a town called Bel-Air. 
In West Philadelphia born and raised
on the playground is where I spent most of my days.
Chillin' out, maxin', relaxin' all cool
and all shootin' some b-ball outside of the school.
When a couple of guys who were up to no good
started makin' trouble in my neighborhood
I got in one little fight and my mom got scared
and said "You're movin' with your auntie and uncle in Bel-Air."</p>


## Exercise 2

Steps are to be completed under the div with `id="exercise2"`

1. Create an **unordered list** element
<ul>
   <li>Milk</li>
   <li>Eggs</li>
   <li>Cheese</li>
   </ul>

2. Create three **list item** elements nested inside of the **unordered list** that your just created
<ul>
   <li>Grocery List</li>
   </ul>
   <li>Milk</li>
   <li>Eggs</li>
   <li>Cheese</li>
   </ul>

3. Create an **anchor** element inside of _each_ **list item** that you just created in your **unordered list**
<ul>
   <li>Career Sites</li>
   </ul>
   <li><a>LinkedIn</a></li>
   <li><a>TrueCoders</a></li>
   <li><a>Most Visited</a></li>
   </ul>


4. Each **anchor** element should link to the following:

   - The first **anchor** element should link to your _LinkedIn profile_
   - The second **anchor** element should link to the _TrueCoders homepage_
   - The third **anchor** element should link to your _most visited website_
   
   <ul>
   <li>Career Sites</li>
   </ul>
   <li><a href="https://www.linkedin.com/feed">LinkedIn</a></li>
   <li><a href= "https://truecoders.io">TrueCoders</a></li>
   <li><a href= "https://www.w3schools.com/cs/index.php">Most Visited Website W3Schools</a></li>
   </ul>


## Exercise 3

Steps are to be completed under the div with `id="exercise3"`
<img src="https://www.imdb.com/title/tt0098800/mediaviewer/rm2588701696/?ref_=tt_ov_i" alt= "Fresh Prince of Bel Air">
1. Create an **image** element
2. Add an **src** attribute with a _relative path_ value that points to the `./images/example.png` file
3. Add an **alt** attribute with a _text description_ value of the image

## Exercise 4

Steps are to be completed under the div with `id="exercise4"`

1. Edit the **paragraph** element's text content so that:
   - the word "Bredon" is enclosed in a span element
   - any word "play" is enclosed in an underline element
   - any word "beautiful" is enclosed in an emphasis element
   - any word "point" is enclosed in an strong element
 
 
 <p><span name = "Bredon" >A man</span>
 <u>"play"</u>
 <em>"beautifyl"</em>
 <strong>"point"</strong>
 </p>




## Exercise 5

Steps are to be completed under the div with `id="exercise5"`

1. Edit the blog post so that more _semantically meaningful_ elements are used instead of generic **division** containers.
   - You will need to use
     - **one main element**
     - **three section elements**
     - **one article element**
     - **one header element**
     - **two nav element**
     - **two unordered list element**
     - **five list item elements**
     - **five anchor elements**
     - **one footer element**

     <h3>Header</h3>
     
     <section>
     <h2>Companys</h2>
     <p>Walmart and Target</p>
     <section>
     <h2>Departments</h2>
     <p>Electronis and Automotive</p>
     <section>
     <h2>Employees</h2>
     <p>100 Employees at Walmart and Target</p>
     <article>
     <h2>Walmart</h2>
     <p>Walmart was founded July 2, 1962 in Rogers, Ar</p>
     <nav>
     <a href="https://www.w3schools.com/tags/tag_nav.asp">Go learn</a>
     </nav>
     <nav>
     <a href="https://www.w3schools.com/tags/tag_nav.asp">Go learn some more</a>
     </nav>
     
   <ul>
   <li>Grocery List</li>
   </ul>
   <li><a href="https://en.wikipedia.org/wiki/Milk#/media/File:Glass_of_Milk_(33657535532).jpg">Milk</a></li>
   <li><a href="https://imgprd19.hobbylobby.com/c/cf/fd/ccffd3b5db6ae1e00e7d52e5ce4ac472e999cc4e/350Wx350H-636225-0220-px.jpg">Eggs</a></li>
   <li><a href="https://www.grocery.com/store/image/cache/catalog/igourmet/igourmet-B00B5PVV9I-600x600.jpg">Cheese</a></li>
   <li><a href="https://www.gopuff.com/cdn-cgi/image/format=auto%2cfit=scale-down%2cquality=70%2cwidth=250%2cheight=250/https://catalog-images.azureedge.net/image/upload/s--iINdom8k--/c_limit%2ccs_srgb%2ch_800%2cw_800/m0stjlsecav6vzj40ar9.png">Orange Juice</a></li>
   <li><a href="https://yellowchilis.com/wp-content/uploads/2022/05/grape-juice-recipe.jpg">Grape Juice</a></li>
   </ul>

   <ul>
   <li>Grocery List</li>
   </ul>
   <li>Bread</li>
   <li>Water</li>
   <li>Juice</li>
   <li>Coconut Oil</li>
   <li>Brown Rice</li>
   </ul>
<footer>
<p>Copyright 2022 Hill.Co</p>
</footer>



   - To be completed, you should have no more than **three division elements** and **zero span elements** (not including the div with `id="exercise5"`)
