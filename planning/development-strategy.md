# HYF-Rebuild

Building a website for free training programs for diverse backgrounds to foster
innovation and growth.

## Setup

- Assign a group leader to create a repo on _GitHub_ named hyf-rebuild
- Add collaborators and give them write _access_
- Protect the _main_ branch; turn on _discussions_; copy the _link_ from _GitHub
  pages_ and paste it in the repo description for _live demo_;
- Clone the _repo_ locally and open it with _VS Code_ Create a new _branch_ and
  run _npm checks_

## User-Stories

- Website Title

As a user, I want to see the website title

- Menu-bar

  As a user, I want to see vividly the menubar

- Website's home picture

  As a user I want to see the website's home picture

- Website Mission

  As a user, I want to discover the website objectives, mission and history

  - HTML:

    - Add a _div_ parent and it three _div_ children;

    - Add an _img_ element to house an image in every child _div_;

    - Add a _div_ to control the _title_ and _paragraph_;

    - Add a _h3_ element to add a _title_;

    - Add a _p_ element to add a _paragraph_;

  - CSS:

    - Add a CSS rule for the container: set to display: flex; flex-direction:
      row;

    - Add a CSS rule for each child _div_ to be set to: box-sizing: border-box

    - Add a CSS rule to set the image’s width and height, and its object-fix to
      cover

    - Add a CSS rule to set the title and paragraph to center

- Project Sponsors

  As a user, I want to learn about the main sponsors

- Alumni Testimonials

  As a user, I want to check some alumni testimonials

  - HTML:

    - Add a _div_ parent with its three children _div_;

    - Add an _h2_ for the title of the section;

    - Add a _div_ for each alumnus;

    - Add an _img_ element;

    - Add a _h4_ title as name of the alumnus;

    - Add a _p_ for the alumnus’s definition;

  - CSS:

    - Add a CSS rule _display_ and set it to _flex_

    - Set the _flex-direction_ to column

    - Add a CSS rule to style _img_ to each alumnus

    - Set the CSS rule border-radius to round

- Newsletter

  As a user, I want to subscribe to the newsletters

  - HTML

    - Add a _form_ element to house three children;

    - Add a _div_ for every child;

    - Add a _label_ to name each _form_;

    - Add an _input_ with values: text, name and placeholder

  - CSS:

    - Add a CSS rule to set the _container_ and _label_ to _display: block_;

    - Add a CSS rule to input set to _border bottom_ to _4px solid blue_;

    - Add a CSS to style the sign up _button_;

    - Add a CSS rule to create the _hover_ effect;

- Contact us

  As a user, I want to contact the people in charge

- Headquarter

  As a user, I want to see a map of the headquarter

- Support, partnership and volunteer

  As a user, I want to find support, volunteer and partnership sections

- Social Media links

  As a user, I want to see social media links in the footer

- Partners

  As a user I have to see the list of partners

  HTML

  - Create a section with class partners. In this section tag:

    - Add a heading tag 'h1' SOME OF OUR PARTNERS

    - Save image of the partners in the folder img

    - Use div container elements with img-row class to group the images into 3
      rows

    - Use image tag, source of the images and alternative name for each image

  CSS

  - Style the elements of partners section by writing css in #partners.css
    linked to @import url("./something.css")

  - For the partners container use display:flex, align-items:center

  - Use center alignment for items in the containers display: flex,
    align-items:center

  - For the h1 assign text-align:center, color:blue, font-size: 100px

  - For img-row class use display:flex, align-items:center, flex-wrap:wrap,
    justify-content:space-around

  - For the img element use max-width:100px, margin:10px, height:auto
