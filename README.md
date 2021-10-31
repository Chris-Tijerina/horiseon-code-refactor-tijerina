# Code Refactor Starter Code

Weekly Challenge #1 - Code Refactor

This weeks task is was take an existing source code of a website for a social solutions company called Hoseon and refactor is to meet accesibility standards. 

The standards were as follows and my steps to resolve them are described below: 
WHEN I view the source code
THEN I find semantic HTML elements

    Solution: Perusal of the code showed that although good, there were places where things could be fixed and corrected. I changed the format of the list to be more evident of it's intent. Corrected an issue where the search engine optimization <div> was not actually labeled as an id, which lead to the navigation bar taking you nowhere when "search enging optimization" was clicked. I also corrected an <img> tag that did not self close. 

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the image elements
THEN I find accessible alt attributes

WHEN I view the heading attributes
THEN they fall in sequential order

WHEN I view the title element
THEN I find a concise, descriptive title

    Changed the title element from a generic title to the name of the company, in keeping with common convention. I decided to go for more than just the name of the company because a little bit of research showed that it could help the site to be found if someone was looking for "social solutions" and didn't actually type the name of the company. It would make the site more discoverable. 