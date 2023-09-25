# 2-Breed fwt-6 CSS

## Hosted Link
You can view the project live at [View Live Project](https://saifulislam05.github.io/fwt-6-css/)

## Project Description
The "Website Name" is a web page project that showcases various features and content. It includes sections for about information, latest events, member login, and additional links. The project has a visually appealing design with a focus on user-friendly navigation.

## HTML Structure

### Top Content Section:
- `<div class="top-content-wrapper">`: Wrapper for the top content section.
  - `<div class="top-content">`: Container for top content elements.
    - `<div class="logo">`: Logo or branding element.
    - `<div class="about-panel">`: About information panel.
    - `<div class="event-panel">`: Latest events panel.
    - `<div class="right-panel">`: Right-side panel containing menus and links.

### About Panel:
- `<div class="about-panel">`: About information panel.
  - `<div class="top-heading">`: Link to the main page.
  - `<div class="panel-content">`: Content of the about panel.
    - `<h2>Who We Are</h2>`: Title.
    - `<h3>Subtitle</h3>`: Subtitle.
    - `<p>Paragraph text with <a href="#">links</a>.</p>`: Detailed information.
    - `<a href="#" class="read-more-btn">Read more</a>`: Read more button.

### Latest Events Panel:
- `<div class="event-panel">`: Latest events panel.
  - `<div class="top-heading event-top-heading">`: Link to about us.
  - `<div class="panel-content">`: Content of the events panel.
    - `<h2>Latest Events</h2>`: Title.
    - `<ul>`: List of events.
      - `<li><h2>Event Date</h2></li>`: Event date.
    - `<p>Event description with <a href="#">links</a>.</p>`: Description of the event.
    - `<a href="#" class="read-more-btn">Read more</a>`: Read more button.

### Right-side Panel:
- `<div class="right-panel">`: Right-side panel containing menus, links, and additional information.
  - `<div class="menu-ad-block">`: Container for menus and ad block.
    - `<div class="menu">`: Menu section.
      - `<ul>`: List of menu items.
        - `<li><a href="#">Menu Item</a></li>`: Menu item with links.
    - `<div class="ad-block">`: Advertisement block.
  - `<h2>Section Title</h2>`: Title.
  - `<div class="additional-links">`: Additional links section.
    - `<ul>`: List of additional links.
      - `<li><a href="#">Additional Link</a></li>`: Additional links.
  - `<div class="icon-links">`: Icon links section.
    - `<a href="#" class="ideas"></a>`: Icon link.
    - `<a href="#" class="signup"></a>`: Icon link.
    - `<a href="#" class="blog"></a>`: Icon link.
  - `<div class="news-letter">`: Newsletter signup section.
    - `<h3>Newsletter Signup</h3>`: Title.
    - `<input type="text" value="- Enter Your Email ID -">`: Email input field.
    - `<a href="#" class="btn-submit">Submit</a>`: Submit button.

### Middle Content Section:
- `<div class="middle-content-wrapper">`: Wrapper for the middle content section.
  - `<div class="container">`: Container for middle content elements.
    - `<div class="features-wrapper">`: Features section.
      - `<h2>Features</h2>`: Title.
      - `<p><span>Feature 1</span> Description.</p>`: Feature description.
      - `<p><span>Feature 2</span> Description.</p>`: Feature description.
      - `<a href="#" class="read-more-btn">Read more</a>`: Read more button.
    - `<div class="login-wrapper">`: Member login section.
      - `<h2>Member Login</h2>`: Title.
      - `<div class="form">`: Login form.
        - `<label>- Enter Your Name -</label>`: Label for name input.
        - `<input name="name" type="text">`: Name input field.
        - `<label>- Enter Your Password -</label>`: Label for password input.
        - `<input type="text">`: Password input field.
        - `<div class="btns">`: Buttons section.
          - `<a href="#" class="forgot-btn">Forgot Password?</a>`: Forgot password button.
          - `<a href="#" class="login-btn">Login</a>`: Login button.

### Footer Section:
- `<footer>`: Footer section.
  - `<div class="footer-container">`: Container for footer elements.
    - `<div class="footer-logo">`: Footer logo or branding element.
    - `<div class="footer-links">`: Footer links section.
      - `<ul>`: List of footer links.
        - `<li><a href="#">Footer Link</a></li>`: Footer links.
    - `<div class="footer-text">`: Footer text or copyright information.
      - `<p>&copy; 2023 Your Website Name. All rights reserved.</p>`: Copyright notice.

# CSS Styles Explanation


## Global Styles (`*`)
- `margin: 0;`: Resets margin for all elements.
- `padding: 0;`: Resets padding for all elements.

## Body (`body`)
- `background: #414141;`: Sets the background color for the entire page.
- `font-family: Arial, Helvetica, sans-serif;`: Specifies the font family for text content.

## Top Content Wrapper (`.top-content-wrapper`)
- `.top-content-wrapper`:
  - `width: 100%;`: Makes the container span the entire width.
  - `background: #f9f7db url(/images/bodyBg.jpg) repeat-x;`: Sets the background color and a repeating image for the top content wrapper.

### Top Content (`.top-content`)
- `.top-content`:
  - `width: 928px;`: Sets the width of the content container.
  - `margin: 0 auto;`: Centers the container horizontally on the page.
  - `display: flex;`: Uses the Flexbox layout for child elements.

#### Logo
- `.logo`:
  - `width: 75px;`: Sets the width of the logo element.
  - `height: 740px;`: Sets the height of the logo element.
  - `background: url(/images/globalpic.jpg);`: Sets a background image for the logo.
  - `background-repeat: no-repeat;`: Prevents the background image from repeating.

#### About Panel (`.about-panel`)
- `.about-panel`:
  - `width: 216px;`: Sets the width of the about panel.
  - `height: 715px;`: Sets the height of the about panel.
  - `background: #cd4007 url(images/globalpic.jpg) no-repeat -77px -494px;`: Sets the background color and image for the about panel.
  
##### Top Heading (`.top-heading`)
- `.top-heading`:
  - `width: 47px;`: Sets the width of the top heading.
  - `height: 110px;`: Sets the height of the top heading.
  - `margin-left: 169px;`: Adds left margin to the top heading.

  - `.top-heading a`:
    - `width: 47px;`: Sets the width of the top heading link.
    - `height: 36px;`: Sets the height of the top heading link.
    - `margin: 0px;`: Resets margins.
    - `display: block;`: Makes the link a block-level element.
    - `padding: 56px 0 0 0;`: Sets padding for the link.
    - `font-family: Arial;`: Specifies the font family.
    - `font-size: 12px;`: Sets the font size.
    - `font-weight: bold;`: Sets the font weight.
    - `color: #646464;`: Sets the text color.
    - `line-height: 13px;`: Sets the line height.
    - `text-align: center;`: Centers text horizontally.
    - `text-decoration: none;`: Removes text decoration.
    - `background: url(images/homeBg.gif) no-repeat;`: Sets a background image for the link.

  - Top Heading Link (Hover) (`.top-heading a:hover`)
    - `.top-heading a:hover`:
    - `height: 36px;`: Adjusts the height on hover.
    - `padding: 74px 0 0 0;`: Adjusts the padding on hover.
    - `background: url(images/homeBg.gif) no-repeat -48px 0;`: Changes the background image position on hover.

##### Panel Content (`.panel-content`)
- `.panel-content`:
  - `width: 170px;`: Sets the width of the panel content.
  - `margin: 0 auto;`: Centers the content horizontally.
  - `margin-top: 199px;`: Adds top margin.
  - `color: #ffe996;`: Sets the text color.

  - Panel Content Heading 2 (`.panel-content h2`)
  - `.panel-content h2`:
    - `color: white;`: Sets the text color to white.
    - `font-size: 26px;`: Defines the font size for heading 2.
    - `font-weight: normal;`: Sets the font weight to normal.

 - Panel Content Heading 3 (`.panel-content h3`)
 - `.panel-content h3`:
    - `font-size: 12px;`: Sets the font size for heading 3.
    - `font-weight: bold;`: Sets the font weight to bold.
    - `margin-top: 8px;`: Adds top margin to the heading.

 - Panel Content Paragraphs (`.panel-content p`)
 - `.panel-content p`:
    - `font-size: 12px;`: Sets the font size for paragraphs.
    - `margin-top: 20px;`: Adds top margin to paragraphs.

### Panel Content Links (`.panel-content p a`)
- `.panel-content p a`:
  - `color: #f8d85e;`: Sets the text color for links within paragraphs.
  - `background:#9f3105 ;`: Sets the background color for links within paragraphs.
  - `text-decoration: none;`: Removes text decoration for links within paragraphs.

#### Panel Content Links (Hover) (`.panel-content p a:hover`)
- `.panel-content p a:hover`:
  - `background: #812a08;`: Changes the background color of links on hover.

##### Read More Button (`.panel-content .read-more-btn`)
- `.panel-content .read-more-btn`:
  - `padding: 4px 7px;`: Sets padding for the read more button.
  - `margin-left: 100px;`: Adds left margin to the button.
  - `text-decoration: none;`: Removes text decoration for the button.
  - `font-size: 11px;`: Sets the font size for the button.
  - `color:#d9d9d9 ;`: Defines the text color for the button.
  - `background: url(/images/buttons.jpg);`: Sets a background image for the button.
  - `background-repeat: no-repeat;`: Prevents the background image from repeating.

##### Read More Button (Hover) (`.panel-content .read-more-btn:hover`)
- `.panel-content .read-more-btn:hover`:
  - `color: #cd4007;`: Changes the text color of the button on hover.

### Event Panel (`event-panel`)
- `.event-panel`:
  - `width: 216px;`: Sets the width of the event panel.
  - `height: 715px;`: Sets the height of the event panel.
  - `border-left:1px solid #f3f1d2;`: Adds a left border to the event panel.
  - `background: #9fb31a url(images/globalpic.jpg) no-repeat -294px -494px;`: Sets the background color and image for the event panel.

#### Event Top Heading (`event-top-heading`)
- `.event-top-heading a`:
  - `background: url(images/about.gif) no-repeat;`: Sets a background image for the event top heading link.
- `.event-top-heading a:hover`:
  - `background: url(/images/about.gif) no-repeat -48px 0;`: Changes the background image position on hover.

#### Event Panel Unordered List (`event-panel ul`)
- `.event-panel ul`:
  - `margin-top: 8px;`: Adds top margin to the unordered list.
  - `list-style: none;`: Removes the default list style.

#### Event Panel List Items (`event-panel ul li`)
- `.event-panel ul li h2`:
  - `font-size: 12px;`: Sets the font size for heading 2 within list items.
  - `color: #ffffff;`: Sets the text color to white.
  - `font-weight: bold;`: Sets the font weight to bold.

#### Event Panel Read More Button (`.event-panel .read-more-btn`)
- `.event-panel .read-more-btn`:
  - `display: inline-block;`: Makes the button an inline-block element.
  - `margin-top: 14px;`: Adds top margin to the button.
  - `margin-bottom: 14px;`: Adds bottom margin to the button.
  - `color: #9fb31a;`: Sets the text color for the button.
  - `background: url(/images/buttons.jpg);`: Sets a background image for the button.
  - `background-repeat: no-repeat;`: Prevents the background image from repeating.

#### Event Panel Read More Button (Hover) (`.event-panel .read-more-btn:hover`)
- `.event-panel .read-more-btn:hover`:
  - `color: #9fb31a;`: Changes the text color of the button on hover.

#### Event Panel Links (`event-panel .panel-content p a`)
- `.event-panel .panel-content p a`:
  - `background: #75850e;`: Sets the background color for links within the event panel.
  - `color: #f2ff9a;`: Sets the text color for links within the event panel.

##### Event Panel Links (Hover) (`.event-panel .panel-content p a:hover`)
- `.event-panel .panel-content p a:hover`:
  - `background: #525d08;`: Changes the background color of links on hover.
  - `color: #f2ff9a;`: Changes the text color of links on hover.
...

### Right Panel (`right-panel`)
- `.right-panel`:
  - `width: 400px;`: Sets the width of the right panel.
  - `padding-left: 20px;`: Adds left padding to the right panel.
  - `padding-top: 22px;`: Adds top padding to the right panel.

#### Menu and Ad Block (`menu-ad-block`)
- `.menu-ad-block`:
  - `width: 100%;`: Sets the width to 100% for the menu and ad block.
  - `display: flex;`: Uses a flex layout for its children.

#### Menu (`menu`)
- `.menu`:
  - `width: 191px;`: Sets the width of the menu.
  - `margin-right: 34px;`: Adds right margin to the menu.
- `.menu ul`:
  - `list-style: none;`: Removes the default list style for menu items.
- `.menu ul li a`:
  - `width: 100%;`: Makes menu item links span the full width.
  - `height: 24px;`: Sets the height of menu item links.
  - `margin: 0px;`: Resets margins.
  - `padding: 0 0 0 15px;`: Adds left padding to menu item links.
  - `float: left;`: Makes menu item links float to the left.
  - `font-family: Arial;`: Specifies the font family.
  - `font-size: 12px;`: Sets the font size.
  - `color: #636038;`: Sets the text color.
  - `line-height: 22px;`: Sets the line height.
  - `font-weight: bold;`: Sets the font weight to bold.
  - `text-decoration: none;`: Removes text decoration.
  - `border-bottom: #b1ae7e dotted 1px;`: Adds a dotted bottom border.
  - `background: url(images/liststyle.jpg) no-repeat 0 7px;`: Sets a background image for menu item links.

#### Menu Links (Hover) (`.menu ul li a:hover`)
- `.menu ul li a:hover`:
  - `color: #75850e;`: Changes the text color of menu item links on hover.

#### Ad Block (`.ad-block`)
- `.ad-block`:
  - `width: 171px;`: Sets the width of the ad block.
  - `height: 195px;`: Sets the height of the ad block.
  - `background: url(/images/globalpic.jpg) no-repeat -337px -110px;`: Sets the background image for the ad block.

#### Right Panel Heading (`right-panel h2`)
- `.right-panel h2`:
  - `margin-top: 29px;`: Adds top margin to the right panel heading.
  - `padding: 0 0 0 57px;`: Adds padding to the right panel heading.
  - `font-size: 34px;`: Sets the font size.
  - `line-height: 40px;`: Sets the line height.
  - `color: #cb3e07;`: Sets the text color.
  - `font-weight: normal;`: Sets the font weight to normal.
  - `background: url(images/globalpic.jpg) no-repeat -467px -308px;`: Sets a background image for the right panel heading.

#### Right Panel Additional Links (`.right-panel .additional-links`)
- `.right-panel .additional-links`:
  - `margin-top: 12px;`: Adds top margin to the additional links section.

#### Right Panel Additional Links List (`right-panel .additional-links ul`)
- `.right-panel .additional-links ul`:
  - `list-style: none;`: Removes the default list style for additional links.
  - `width: 400px;`: Sets the width of the additional links list.
  - `height: 180px;`: Sets the height of the additional links list.

#### Right Panel Additional Links List Items (`right-panel .additional-links ul li a`)
- `.right-panel .additional-links ul li a`:
  - `height: 27px;`: Sets the height of each additional link item.
  - `width: 100%;`: Makes each additional link item span the full width.
  - `box-sizing: border-box;`: Includes padding and border in the total width calculation.
  - `margin: 3px 0 0 0;`: Sets margins for the additional link items.
  - `padding: 0 0 0 27px;`: Adds left padding to the additional link items.
  - `float: left;`: Makes the additional link items float to the left.
  - `font-family: Arial;`: Specifies the font family.
  - `font-size: 12px;`: Sets the font size.
  - `color: #3b3a2b;`: Sets the text color.
  - `line-height: 25px;`: Sets the line height.
  - `text-decoration: none;`: Removes text decoration.
  - `background: url(images/globalpic.jpg) no-repeat -75px -83px;`: Sets a background image for the additional link items.

#### Right Panel Additional Links List Items (Hover) (`.right-panel .additional-links ul li a:hover`)
- `.right-panel .additional-links ul li a:hover`:
  - `color: #9fb31a;`: Changes the text color of additional link items on hover.

#### Icon Links (`icon-links`)
- `.icon-links`:
  - `width: 100%;`: Sets the width of the icon links section.
  - `display: flex;`: Uses a flex layout for the icon links.

#### Icon Links (Individual) (`.icon-links a`)
- `.icon-links a`:
  - `width: 127px;`: Sets the width of each individual icon link.
  - `height: 101px;`: Sets the height of each individual icon link.

#### Icon Links (Ideas) (`.icon-links .ideas`)
- `.icon-links .ideas`:
  - `background: url(images/globalpic.jpg) no-repeat -77px -392px;`: Sets the background image for the "Ideas" icon link.

#### Icon Links (Signup) (`.icon-links .signup`)
- `.icon-links .signup`:
  - `background: url(images/globalpic.jpg) no-repeat -204px -392px;`: Sets the background image for the "Signup" icon link.

#### Icon Links (Blog) (`.icon-links .blog`)
- `.icon-links .blog`:
  - `background: url(images/globalpic.jpg) no-repeat -331px -392px;`: Sets the background image for the "Blog" icon link.
...

#### Newsletter Section (`.news-letter`)
- `.news-letter`:
  - `width: 400px;`: Sets the width of the newsletter section.
  - `height: 76px;`: Sets the height of the newsletter section.
  - `margin-top: 25px;`: Adds top margin to the newsletter section.
  - `padding: 10px 0 0 114px;`: Specifies padding for the newsletter section.
  - `box-sizing: border-box;`: Includes padding in the total width calculation.
  - `background: url(images/globalpic.jpg) no-repeat -75px 0;`: Sets a background image for the newsletter section.

#### Newsletter Section Heading (`news-letter h3`)
- `news-letter h3`:
  - `font-size: 18px;`: Sets the font size for the newsletter section heading.

#### Newsletter Section Input Field (`news-letter input`)
- `news-letter input`:
  - `width: 206px;`: Sets the width of the input field.
  - `height: 18px;`: Sets the height of the input field.
  - `margin-top: 5px;`: Adds top margin to the input field.
  - `margin-right: 7px;`: Adds right margin to the input field.
  - `padding-top: 3px;`: Specifies top padding for the input field.
  - `font-size: 10px;`: Sets the font size for the input field.
  - `color: #212121;`: Defines the text color.

#### Newsletter Section Submit Button (`news-letter .btn-submit`)
- `news-letter .btn-submit`:
  - `color: white;`: Sets the text color of the submit button to white.
  - `background: url(images/globalpic.jpg) no-repeat -75px -226px;`: Sets a background image for the submit button.
  - `text-align: center;`: Centers the text within the button.
  - `text-decoration: none;`: Removes text decoration.
  - `font-size: 11px;`: Sets the font size for the button text.
  - `padding: 4px 2px;`: Adds padding to the button.
  - `border-radius: 4px;`: Applies a rounded border to the button.

## Middle Content Wrapper (`.middle-content-wrapper`)
- `.middle-content-wrapper`:
  - `width: 100%;`: Sets the width of the middle content wrapper.
  - `background: #e9e6c3 url(images/middleBg.jpg) repeat-x;`: Sets the background color and image for the middle content wrapper.

### Container for Middle Content (`.container`)
- `.container`:
  - `width: 928px;`: Sets the width of the container for middle content.
  - `margin: 0 auto;`: Centers the container horizontally on the page.
  - `padding-top: 24px;`: Adds top padding to the container.
  - `display: flex;`: Uses a flex layout for its child elements.
...

### Features Wrapper (`.features-wrapper`)
- `.features-wrapper`:
  - `width: 473px;`: Sets the width of the features section wrapper.
  - `padding: 0 31px 34px 26px;`: Specifies padding for the features section wrapper.

### Features Section Heading (`features-wrapper h2`)
- `features-wrapper h2`:
  - `font-size: 34px;`: Sets the font size for the features section heading.
  - `color: #1d1d1d;`: Defines the text color.
  - `padding-left: 50px;`: Adds left padding to the heading.
  - `font-weight: normal;`: Sets the font weight to normal.

#### Features Section Paragraphs (`features-wrapper p`)
- `features-wrapper p`:
  - `margin-top: 9px;`: Adds top margin to the paragraphs.
  - `font-size: 12px;`: Sets the font size for the paragraphs.
  - `color: #575433;`: Defines the text color.
  - `line-height: 19px;`: Sets the line height for the paragraphs.

##### Read More Button (`features-wrapper .read-more-btn`)
- `features-wrapper .read-more-btn`, `.login-btn`:
  - `padding: 5px;`: Adds padding to the button.
  - `text-decoration: none;`: Removes text decoration.
  - `font-size: 11px;`: Sets the font size for the button text.
  - `float: right;`: Floats the button to the right.
  - `color: white;`: Sets the text color to white.
  - `background: url(images/globalpic.jpg) no-repeat -117px -226px;`: Sets a background image for the button.
  - `border-radius: 4px;`: Applies a rounded border to the button.

#### Member Login Wrapper (`.login-wrapper`)
- `.login-wrapper`:
  - `width: 180px;`: Sets the width of the member login wrapper.
  - `height: 184px;`: Sets the height of the wrapper.
  - `border: 1px solid #d7d3aa;`: Adds a border to the wrapper.
  - `background: #f1eed0;`: Sets the background color.

##### Member Login Heading (`login-wrapper h2`)
- `login-wrapper h2`:
  - `padding-left: 33px;`: Adds left padding to the heading.
  - `font-size: 18px;`: Sets the font size for the heading.
  - `color: #212121;`: Defines the text color.
  - `font-weight: normal;`: Sets the font weight to normal.
  - `line-height: 30px;`: Sets the line height for the heading.
  - `background: #ffffff url(images/globalpic.jpg) no-repeat -483px -399px;`: Sets a background image for the heading.

##### Member Login Form (`login-wrapper .form`)
- `login-wrapper .form`:
  - `padding: 8px 0 0 17px;`: Specifies padding for the form.

###### Member Login Labels (`login-wrapper .form label`)
- `login-wrapper .form label`:
  - `font-size: 10px;`: Sets the font size for the labels.
  - `color: #1d1d1d;`: Defines the text color.

- Member Login Input Fields (`login-wrapper .form input`)
- `login-wrapper .form input`:
  - `padding: 3px;`: Adds padding to the input fields.
  - `width: 90%;`: Sets the width of the input fields.
...

#### Contact Section (`.contact`)
- `.contact`:
  - `width: 210px;`: Sets the width of the contact section.
  - `height: 107px;`: Sets the height of the contact section.
  - `margin: 21px 0 0 19px;`: Specifies margin for positioning.
  - `background: url(images/globalpic.jpg) no-repeat -75px -111px;`: Sets a background image for the contact section.

##### Contact Paragraph (`contact p`)
- `contact p`:
  - `font-size: 26px;`: Sets the font size for the paragraph.
  - `color: #252525;`: Defines the text color.
  - `margin-top: 10px;`: Adds top margin.
  - `line-height: 30px;`: Sets the line height for the paragraph.
  - `padding-left: 28px;`: Adds left padding.

### Footer Section (`footer`)
- `footer`:
  - `width: 100%;`: Sets the width of the footer section.
  - `padding-bottom: 23px;`: Adds padding to the bottom.
  - `background: url(images/footbg.jpg) repeat-x;`: Sets a repeating background image.

#### Footer Container (`.container`)
- `.container`:
  - `display: flex;`: Uses a flexbox layout for the container.

##### Footer Navigation (`footer .footer-nav`)
- `footer .footer-nav`:
  - `width: 655px;`: Sets the width of the footer navigation.
  - `margin: 0 auto;`: Centers the navigation horizontally.
  - `display: flex;`: Uses a flexbox layout for navigation items.
  - `justify-content: space-between;`: Distributes items evenly along the horizontal axis.
  - `list-style: none;`: Removes list-style (bullets) from the list items.

###### Footer Navigation Links (`footer .footer-nav li a`)
- `footer .footer-nav li a`:
  - `font-size: 11px;`: Sets the font size for the links.
  - `color: #d5d5d5;`: Defines the text color.
  - `text-decoration: none;`: Removes text decoration.
  - `border-right: 1px solid #d5d5d5;`: Adds a right border to separate links.
  - `padding-right: 8px;`: Adds padding to the right.

#### Copyright Notice (`.copyright`)
- `.copyright`:
  - `text-align: center;`: Centers the text horizontally.
  - `color: #9fb31a;`: Defines the text color.
  - `font-size: 10px;`: Sets the font size for the copyright notice.
  - `margin-top: 6px;`: Adds top margin.

#### Footer Paragraph (`.para`)
- `.para`:
  - `color: #e9e6c3;`: Defines the text color.
  - `font-size: 12px;`: Sets the font size for the paragraph.
  - `text-align: center;`: Centers the text horizontally.
  - `font-weight: bold;`: Sets the font weight to bold.
  - `margin-top: 9px;`: Adds top margin.

#### Footer Links (`footer .para a`)
- `footer .para a`:
  - `color: white;`: Sets the text color.
  - `text-decoration: none;`: Removes text decoration.

#### Footer Buttons (`.footer-btns a`)
- `.footer-btns a`:
  - `color: white;`: Sets the text color.
  - `font-size: 11px;`: Sets the font size for the buttons.
  - `text-align: center;`: Centers the text horizontally.
  - `text-decoration: none;`: Removes text decoration.
  - `padding: 4px;`: Adds padding to the buttons.
  - `border-radius: 4px;`: Applies a rounded border to the buttons.



