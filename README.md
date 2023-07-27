# SEO Code Refactor Project

## Reformating code to make it more recognized by SEO and accebility apps. Also streamlining the code when needed. 

Wanted to creat a HTML that was SEO and accessibility friendly. In addition to that it needed to be optimized to meet users of different needs.

By doing this project I was able to achieve all of the above. 

I learned that making sure that code is writen effeciently is just a important as writing code helps maximize SEO. It is also important to keep accessibility standards in mind.

## Action taken

After reviewing  the HTML and the CSS I found the following areas that needed to be improved upon. 

### HTML Refactor

* Updated the website title in head
* Changed the div in the header to nav
* Changed the div around class="hero" to a section
* Changed the div class="content" to main
* added a missing id for "search-engine-optimization"
* Changed all the remaining div into sections
* Added alt text to all the image elements in the main section and the benefit areas
* In the third benefit image there was excessive code with a closing tag. Removed that and added / before the last bracket
* changed the div footer to just footer

### CSS Refactor

* Changed all the .header elements to header
* Removed div from header and added nav in all header div instances
* Changed .content to main
* Combined .benefit-lead, .benefit-brand, and .benefit-cost into .benefit
* combined .benefit-lead h3, .benefit-brand h3, and .benefit-cost h3 into .benefit
* combined .benefit-lead img, .benefit-brand img, and .benefit-cost img into .benefit
* changing .search-engine-optimization, .online-reputation-management, and .social-media-marketing to .products to remove repeating rules in the first rule, then img and h2
* updated footer div to footer