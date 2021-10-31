# Code Refactor Starter Code

Weekly Challenge #1 - Code Refactor

This weeks task is was take an existing source code of a website for a social solutions company called Hoseon and refactor is to meet accesibility standards. 

The standards were as follows and my steps to resolve them are described below: 
WHEN I view the source code
THEN I find semantic HTML elements

    Solution: Perusal of the code showed that although good, there were places where things could be fixed and corrected. I changed the format of the list to be more evident of its intent. Corrected an issue where the search engine optimization <div> was not actually labeled as an id, which lead to the navigation bar taking you nowhere when "search enging optimization" was clicked. I also corrected an <img> tag that did not self close. 

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

    Solution: 

WHEN I view the image elements
THEN I find accessible alt attributes

    Solution: I added the proper descriptive alt text to the first three images that cover the different sections of the site. I left the alt text empty for the the three png icons because they would be deemed redundant to the information provided with them. I went back and forth on this issue before settling on leaving them empty. 

WHEN I view the heading attributes
THEN they fall in sequential order

    Solution: The heading attributes already had a good order to the major elements of the page. I feel the benefits items do fall below the services provided which warrants an <h3>. I noticed that the footer was listed as an <h2> which didn't seem to be appropriate as it's the least important element on the page and would cause issues with a screen reader if it was left as an <h2>, so I changed it to an <h4>.

WHEN I view the title element
THEN I find a concise, descriptive title

    Solution: Changed the title element from a generic title to the name of the company, in keeping with common convention. I decided to go for more than just the name of the company because a little bit of research showed that it could help the site to be found if someone was looking for "social solutions" and didn't actually type the name of the company. It would make the site more discoverable. 