# Relief Yoga & Meditation

[Published github website](https://saroltah.github.io/yoga-project/)

## Idea

An online library of meditation and yoga classes that focus on stress and anxiety relief.

Goal of this website: give information about an application that helps people be more wholesome.

s need: more available online platforms that help to relax and relieve everyday stress.

Importance: to be able to live healthy and fulfilled lives with healthy minds.

This website presents a starting business, tells what the library would be about, and gives an opportunity to sign up. The log-in details would be sent by email - after log-in we would be able to see the videos.

- Specific stand-out: all the videos would be made by, certified and professional yoga masters.

- People can use the app anywhere anytime.

How they can get access to the information: short paragraphs, only relevant information, with a menu that helps them to find what they are looking for.

## Build-up

I. Logo & menu - on the top - for easy navigation.

II. The name and short description of what the page is about.

III. Giving reasons for using the website - s concider why they need the app, and what can it help with.

IV. Specifying why to choose this app over others, and what are the advantages.

V. Sign up form, where the s can register to be a member.

VI. Contact details - for the s who have questions and social media links to find out more information about the business.

Shortly: The s see what the website is about, then think about if they need it, see the advantages, why this website is a good option over other platforms, get the option to sign up and try it out, and then also the option to read more or get in contact.

## My work Process

### First part - HTML

- Adding basic files and folders.
- Adding meta tags - keywords, description and css link - make the background-color red to test it.
- Deploying my site, to see if everything works.
- Taking notes and print screens.
- Considering ux principles planning the main sections with text.
- Writing text first in a text document - to check the text for correct spelling, grammar and semantics.
- Writing the HTML document with background color, to see if the structure is fine and also it is easier to visualize the design how big space the paragraphs take.

Starting to write HTML:
![HTML text with background colors](<html texrt with colorful background.png>)

- Design layout on wireframe

  The bigger the screen the more columns can have.

  Wireframe for mobile:
  ![Wireframe mobile](<wireframe mobile-2.png>)
  Wireframe for tablet:
  ![Wireframe tablet](<wireframe tablet-1.png>)
  Wireframe for desktop:
  ![Wireframe desktop](<wireframe desktop-1.png>)
  For bigger screens I changed the layout during coding, so it looks and functions better.

- Completing HTML text with links, form details, sign up button, icons and classes to be able to apply the layout and design.

- Creating toggle menu.

- Finding background images, color palette and font family that fits to the project.

  Image: related to the topic, so when the s look at it, they instantly know what the page is about.

  Color palette: I chose calming colors from the main photo with a color picker.

Choosing the main color with color picker:

![chosing the main color with color picker](<color picker.png>)
Font family: I chose two types, one is pretty for the titles and logos, the other is simple and easy to read.

### Second part: CSS

I was working on sections one by one, making them also responsive:

- Changing the layout of Menu (checkbox toggle is not working) and making header responsive.
- Adding pseudo classes.
- Making background image responsive and adding aria labels to that. Adding color under the image in case it doesn't load.
- Positioning h1 and h2 - check in developer tools.
- Styling About section, making it responsive.
- Styling Sign up section and making it responsive.
- Styling footer, making it responsive.

### Optimization, last touches

- Changing images to smaller format for faster loading.
- CSS validator - mistake: font-style: bold - corrected to font-weight: bold.
- HTML validator - a meta element was missing the closing tag - corrected.
- Lighthouse check - laptop 100%, mobile 75% - compressed image one more time.
- Optimizing font-size as a general CSS rule.

  If the s use the menu instead of scrolling, they should be able to see the Sign up section in one piece.

## Workflow

- Working with the live server - to see immediately the changes.
- Using prettier for an easier, more smooth coding process and to note mistakes easier.
- Testing continuously and paying attention of problems on the terminal.
- Using keyboard shortcuts and Emmet for the faster process.
- Continuously checking and trying out things in developer tools.

## Bugs and solutions

1.  Checkbox toggle was not working on the one-page website, because the menu only jumps back when the page is refreshed.

    Removed toggling, made the menu smaller on the top of the page. I divided the logo and the menu links to two rows, so there is enough space for them, they are readable and easy to click/tap on.

2.  Header covered the sections when they were opened from the menu links.

    Added padding top - at least the size of the header.

3.  There was a LOCK file in the repository so I couldn't commit.

    Deleted it manually.

4.  Menu covered the logo.

    Added z-index.

5.  Prettier ruins the consistency of HTML format - changed it in the end.

## Testing

Tried on mobile, tablet, laptop and desktop screen view.

| What to do                                                                        | How to do                                                                                                      | Expected outcome                                                                                   | Actual Outcome                                                                                                                                |
| --------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Header, menu and logo always visible                                              | Scrolling the page, clicking on menu links                                                                     | Header, menu and logo always visible                                                               | Header, menu and logo always visible                                                                                                          |
| Home link leads back to Home section                                              | Click on Home link                                                                                             | Goes back to homepage, where h1 and h2 is visible                                                  | Goes back to homepage, where h1 and h2 is visible                                                                                             |
| About leads to About section                                                      | Click on About link                                                                                            | Goes to About section, the Who are we? paragraph is visible                                        | Goes to About section, the Who are we? paragraph is visible                                                                                   |
| Sign up leads to Sign-up section                                                  | Click on Sign up link                                                                                          | Goes to Sign-up section, where the sign up form is visible, with all questions and button          | Goes to Sign-up section, where the sign up form is visible, with all questions and button                                                     |
| Contact leads to Contact section                                                  | Click on Contact link                                                                                          | Goes down to the bottom of the page so the whole Contact section is visible                        | Goes down to the bottom of the page so the whole Contact section is visible                                                                   |
| The menu links change color when clicking on them                                 | Click on the links one by one                                                                                  | They all change color (from black to brown until clicking somewhere else)                          | They all change color (from black to brown until clicking somewhere else)                                                                     |
| The text and email type of input fields change color when clicking on them        | Pointing the cursor on them, then click on them one by one                                                     | They all change color - from brown to light blue when pointing, then black when clicking           | They all change color - from brown to light blue when pointing, then black when clicking                                                      |
| The submit input changes color when pointing on it                                | Pointing the cursor on it, then click on it                                                                    | It gets a light blue box shadow instead of brown, and the border disappears.                       | It gets a light blue box shadow instead of brown, and the border disappears                                                                   |
| The text input fields are required                                                | Trying to submit them empty one by one                                                                         | It doesn't let submit, it writes out that the field needs to be filled                             | It doesn't let submit, it writes out that the field needs to be filled                                                                        |
| The email input field is required                                                 | Trying to submit them empty, then without the @, then without anything before @, then without anything after @ | It doesn't let submit, it writes out that the field needs to be filled with the right email format | It doesn't let submit, it writes out that the field needs to be filled with the right email format                                            |
| The submit button is working, and the form attributes are correct                 | Click on Sign up button                                                                                        | It shows the written data on Code Institute's form-dump page                                       | It shows the written data on Code Institute's form-dump page                                                                                  |
| The input name and value is added correctly                                       | Submit my data (click on Sign up button)                                                                       | On Code Institute's form-dump page the Input name and Value table is correct                       | On Code Institute's form-dump page the Input name and Value table is correct                                                                  |
| The contact icons change color, and cursor turns to pointer when hovering on them | Hover on a contact icon                                                                                        | They change color to brown from black, the cursor turns to pointer                                 | They change color to brown from black, the cursor turns to pointer                                                                            |
| The Facebook icon / link is correct and opens in a new tab                        | Click on Facebook icon                                                                                         | It opens Facebook page in a new tab                                                                | It opens Facebook page in a new tab                                                                                                           |
| The Instagram icon / link is correct and opens in a new tab                       | Click on Instagram icon                                                                                        | It opens Instagram page in a new tab                                                               | It opens Instagram page in a new tab                                                                                                          |
| The Twitter icon / link is correct and opens in a new tab                         | Click on Twitter icon                                                                                          | It opens Twitter page in a new tab                                                                 | It opens Twitter page in a new tab                                                                                                            |
| The Email icon / link is correct and opens in a new tab                           | Click on Email icon                                                                                            | It opens my email server with the receiver's email address:info@relief.com in a new tab            | It opens my email server with the receiver's email address:info@relief.com in a new tab                                                       |
| Responsive on all screen sizes                                                    | Open developer tools and check, use Am I responsive? website                                                   | It looks good and all the functions are working properly in all sizes                              | It looks good and all the functions are working properly in all sizes.                                                                        |
| Correct CSS file                                                                  | Copy the code to W3C CSS validator website.                                                                    | There are no errors                                                                                | There are no errors.                                                                                                                          |
| Correct HTML file                                                                 | Copy the code to The W3C HTML validator website.                                                               | There are no errors                                                                                | There are no errors. It only mentions that the slash is not necessary for self-closing tags. Prettier corrects the code and put the slash in. |

Checking email input:
![Input email ](<input email check.png>)
Checking submit button:
![Code institute formdump](<checking submit button.png>)
Checking twitter icon:
![Twitter icon gets gold color hovering](<twitter icon.png>)
Am I responsive?
![am i responsive image](<Am i responsive.png>)

Lighthouse check for desktop devices:

Desktop:

- Performance: 98%
- Accessibility: 100%
- Best Practices: 100%
- SEO: 100%
  ![Lighthouse desktop](<lighthouse desktop-1.png>)
  Mobile:

- Performance: 96%
- Accessibility: 100%
- Best Practices: 100%
- SEO: 100%
  ![Lighthouse mobile](<lighthouse mobile-2.png>)

## Credits

Programs:

- VS Code
- Github

Planning:

- [Balsamiq wireframes](https://balsamiq.com/wireframes/desktop/)

Font family:

- [Google fonts](https://fonts.google.com/)
- Inspired by my own [Bob Ross project](https://bob-ross-fan-page-by-sarolta-h.netlify.app/)

Images and icons:

- [Font awesome](https://fontawesome.com/)
- [Unspalsh](https://unsplash.com/)
- [Pexels](https://www.pexels.com/sv-se/)
- [Compress JPG](https://compressjpeg.com/)
- [Tiny PNG](https://tinypng.com/)
- [Convert io](https://convertio.co/jpg-webp/)

Color palette:

- [Chrome color picker](https://chrome.google.com/webstore/detail/color-picker-for-chrome/clldacgmdnnanihiibdgemajcfkmfhia)

Validating:

- [Am I responsive?](https://ui.dev/amiresponsive)
- [W3C CSS validator](https://jigsaw.w3.org/css-validator/)
- [W3C HTML validator](https://validator.w3.org/)

Special thanks to [Code Institute](https://codeinstitute.net/se/full-stack-software-development-diploma/?utm_term=code%20institute&utm_campaign=CI+-+SWE+-+Search+-+Brand&utm_source=adwords&utm_medium=ppc&hsa_acc=8983321581&hsa_cam=14660337051&hsa_grp=134087657984&hsa_ad=635849372549&hsa_src=g&hsa_tgt=aud-594467886660:kwd-319867646331&hsa_kw=code%20institute&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gad=1&gclid=CjwKCAjw4P6oBhBsEiwAKYVkqzzIpIRAmKF-tC7OHL0D0ijr9ic8Bv2gLino_uOt3SWXrRzbR7NoNhoCisIQAvD_BwE) and my mentor Ronan McClelland for reviewing, helping and answering all my questions.
