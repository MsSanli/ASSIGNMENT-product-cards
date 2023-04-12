# Product Cards

Issue tickets have been created so that you can track your progress. As you complete a ticket, close it out.

## Study Group Requirements

- You should be using flexbox. 
- You may use Bootstrap for Card Components
- Decide as a team how many branches you will need and what will happen on each branch (remember one feature per branch).

## Setup
* While in `~/workspace/foundations/exercises`, clone this repo
* Create a setup branch and push up the usual stuff

## Requirements

Your task is to build a grid of cards for a company's products. Here are the requirements for the basic structure of the cards.

1. Cards should be 3 per row.
1. Each product should contain a `header` element that, itself, contains an `h2` element where the product's title will be written.
1. The first section should contain three child block elements.
    1. The first element contains the product image.
    1. The second element contains the product description.
    1. The third element contains the product availability (e.g. "Available" or "Not Available")
1. The second section contains product specifications.
    1. This section should have a header containing the word "Specifications"
    1. This section should contain two block elements
    1. The first block element specifies the size.
    1. The second block element specifies the weight.
    1. This section should contain a footer.
    1. The footer contains text stating when the product specifications become invalid.
1. The third section contains the product pricing.
    1. This section should contain a header.
    1. This section should contain three block elements.
    1. Each block element contains information about the price for different quantities.

### Additional style requirements

1. The card title has a solid 1px border that is `lightblue`.
1. The title and product image are centered.
1. Notice that the text for the description in the image is justified.
1. The text for the product specification details and pricing details is bold.
1. The availability element extends the full width of the card, with a dark grey background and yellow text.

### Visual example

Here's an image that shows how the cards should appear. This visual example is a wireframe, which means it is only an example of layout. Style your cards based on the requirements and then use your own judgment after doing so. All the data needs to be on the cards. 

![Static Web Product Cards Example](https://github.com/nss-nightclass-projects/exercise-vault/blob/master/images/SW_HTML_CSS_exercise.png)


### Challenges

#### Challenge 1: Switch up the font!
1. Pick font(s) from [Google Font](https://fonts.google.com/) and include them in your project. You can use them wherever you want, but uh, don't make it too ugly. 

#### Challenge 2: Sold out.
1. For items that are no longer available, place [this image](https://raw.githubusercontent.com/morecallan/css102-e6/master/images/soldOut.png) over top of the product card. **Note this is complex positioning, it is going to challenge you.**. What I mean by "over the product card" is ![Sold Out](https://raw.githubusercontent.com/morecallan/css102-e6/master/images/CSS102-Mockup.png)

#### Challenge 3: Display responsively on any size screen!
1. Use CSS to conditionally apply styles depending on the width of the screen! (or the size of the browser window) You can do this using a fancy thing called [media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries). You can find a good example of how to do that [here](https://css-tricks.com/designing-a-product-page-layout-with-flexbox/#article-header-id-4).
