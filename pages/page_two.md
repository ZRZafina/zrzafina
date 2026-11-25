<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HTML and CSS</title>
    <link rel="stylesheet" href="./assets/style.css" />
    <script src="./assets/marked.js" defer></script>
    <script src="./assets/content_load.js" defer></script>
    <script src="./assets/script.js" defer></script>
  </head>
  <body>
    <header>
      <div id="navBar" class="flex defaultPageMargin">
        <a class="blueText" href="./index.html">Index</a>
        <p id="totalCount" class="lightText"></p>
        <nav>
          <ul class="flex">
            <!-- to add a page: create pages/my_page.md and add a link with ?page=my_page -->
            <li><a class="navLink" href="./pages/page_four">First Assignment</a></li>
            <li><a class="navLink" href="./pages/page_one">Positive</a></li>
            <li><a class="navLink" href="./pages/page_two">Negative</a></li>
            <li><a class="navLink" href="./pages/page_tree">For School</a></li>
            <li><a class="navLink" href="./pages/Page_zero">Last Assignment</a></li>
          </ul>
        </nav>
      </div>
      <div id="pageHero">
        <div id="bannerShadow" class="flex"><h1>Loading...</h1></div>
      </div>
    </header>
  <main class="defaultPageMargin">
# What are the disadvantages of open-source software?
Some of the disadvantages are 
-	Professional vs volunteers
-	Hidden cost
-	Security Risks

## Professional vs volunteers
Free software means there might not be a professional support team to ask for help.
If you ask someone in the community for help, you get help from volunteers. You do not know when or if someone is able to help you within a time limit.

## Hidden Cost
Even free software can have hidden expensive;
-	Time to learn to use the software
-	Customizing
-	Maintenance
It all takes time to learn and figure out what you need. Time is money in a business. There is a possibility you need to pay someone to help do it for you.

##Security Risks
Open-Source transparency means everyone can see and change the codes, which can make the software vulnerable, and users can exploit this weakness.


## References
https://www.freecodecamp.org/news/what-is-open-source-software-explained-in-plain-english/ 
    </main>
    <footer>
      <div id="footerBody" class="defaultPageMargin flex">
        <p class="blueText">Digital Technologies in the Humanities, fall 2026</p>
      </div>
    </footer>
  </body>
</html>
