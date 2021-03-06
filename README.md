# Horiseon - Code Refactor

## This week's task was to take an existing source code of a website for a social solutions company called Horiseon and refactor is to meet accesibility standards. 

Website Link: https://chris-tijerina.github.io/horiseon-code-refactor-tijerina/#social-media-marketing

The standards set forth by the user were as follows and my steps to resolve them are described below: 

>WHEN I view the source code  
>THEN I find semantic HTML elements

Perusal of the code showed that although good, there were places where things could be fixed and corrected. I changed the format of the list to be more evident of its intent. Corrected an issue where the search engine optimization `<div>` was not actually labeled as an id, which lead to the navigation bar taking you nowhere when "search enging optimization" was clicked. I also corrected an <img> tag that did not self close. 


>WHEN I view the structure of the HTML elements  
>THEN I find that the elements follow a logical structure independent of styling and positioning

There was not a lot of issues with the overall structure of the html elements, but some divs were changed to sections in order to better meet accessability standards. I also added id's to the content of the benefits now that they share a class to allow for better CSS selection for individual portions of the section. 

>WHEN I view the image elements  
>THEN I find accessible alt attributes

I added the proper descriptive alt text to the first three images that cover the different sections of the site. I left the alt text empty for the the three png icons because they would be deemed redundant to the information provided with them. I went back and forth on this issue before settling on leaving them empty. 

>WHEN I view the heading attributes  
>THEN they fall in sequential order

The heading attributes already had a good order to the major elements of the page. I feel the benefits items do fall below the services provided which warrants an `<h3>`. I noticed that the footer was listed as an `<h2>` which didn't seem to be appropriate as it's the least important element on the page and would cause issues with a screen reader if it was left as an `<h2>`, so I changed it to an `<h4>`.

>WHEN I view the title element  
>THEN I find a concise, descriptive title

Changed the title element from a generic title to the name of the company, in keeping with common convention. I decided to go for more than just the name of the company because a little bit of research showed that it could help the site to be found if someone was looking for "social solutions" and didn't actually type the name of the company. It would make the site more discoverable. 
