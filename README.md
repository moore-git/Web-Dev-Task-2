# Web Developer Exercise 2

As part of Boston Seeds' ongoing efforts to keep its web pages current and user-friendly, there are some design changes required to the product listing page on the Farmseeds.co.uk website. 

Please review the `millet.html` file and make some style changes to improve the overall usability and appearance of the page. In order to achieve this, a new CSS file has been created and linked to from the HTML document - `exercise.css`. Please add all new styles and overrides to this stylesheet.

The following websites contain elements that the Boston Seeds staff have highlighted as being more user-friendly than the current implementation on the Farmseeds page:

- https://www.cotswoldseeds.com/
- http://shop.oliver-seeds.co.uk/

Caveats and notes:

- You are free to modify the markup as required
- External stylesheets may be added if required (i.e. icon and font libs, etc)
- There is no requirement to add responsive design, as this is not currently a feature of the Farmseeds website.

**Time allowance: 30 minutes**

Please fork or clone the repository to carry out the exercise. Please do not spend longer than the time allowance above, and make all code available on Github. Also, please modify this readme to indicate what changes have been made. 

## Changes

- Navigation is now sticky allowing the cart and relevant navigation to always be accessible
- About/FAQ/Contact links have been moved, this evens out the dead space in the top right and stops them from drawing focus from the account and basket links
- Home button removed as it's now standard practice to just have the company logo fulfil this purpose
- Standard hover state styling (underline) added to About/FAQ/Contact links to aid usability
- Account and cart links reordered to place the cart on the far right side to aid in usability as this is the standard location 
- Fixed the type attribute for the linked exercise stylesheet