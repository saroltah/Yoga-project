# Relief Yoga & Meditation

[Published github website](https://saroltah.github.io/yoga-project/)

## Idea

An online library of meditation and yoga classes that focus on stress and anxiety relief.

_Goal of this website:_ give information about an application that helps people be more wholesome.

_Users need:_ more available online platforms that help to relax and relieve everyday stress.

_Importance:_ to be able to live healthy and fulfilled lives with healthy minds.

This website presents a starting business, tells what the library would be about, and gives an opportunity to sign up. The log-in details would be sent by email - after log-in we would be able to see the videos.

_Specific stand-out:_

- All the videos would be made by, certified and professional yoga masters.

- People can use the app anywhere anytime.

**How they can get access to the information:** short paragraphs, only relevant information, with a menu that helps them to find what they are looking for.

## Structure

I. Logo & menu - on the top - for easy navigation.

II. The name and short description of what the page is about.

III. Giving reasons for using the website - users concider why they need the app, and what can it help with.

IV. Specifying why to choose this app over others, and what are the advantages.

V. Sign up form, where the users can register to be a member.

VI. Contact details - for the users who have questions and social media links to find out more information about the business.

_Summary:_ The users see what the website is about, then think about if they need it, see the advantages, why this website is a good option over other platforms, get the option to sign up and try it out, and then also the option to read more or get in contact.

## My work Process

### First part - HTML

- Adding basic files and folders.
- Adding meta tags - keywords, description and CSS link - make the background-color red to test it.
- Deploying my site, to see if everything works.
- Taking notes and print screens.
- Considering UX principles planning the main sections with text.
- Writing text first in a text document - to check the text for correct spelling, grammar and semantics.
- Writing the HTML document with background color, to see if the structure is fine and also it is easier to visualize the design how big space the paragraphs take.

_Starting to write HTML:_

![HTML text with background colors](</assets/images/readme-images/html text with colorful background.png>)

- Design layout on wireframe

  The bigger the screen the more columns can have.

_Wireframe for mobile:_

![Wireframe mobile](</assets/images/readme-images/wireframe mobile-2.png>)

_Wireframe for tablet:_

![Wireframe tablet](</assets/images/readme-images/wireframe tablet-1.png>)

_Wireframe for desktop:_

![Wireframe desktop](</assets/images/readme-images/wireframe desktop-1.png>)

For bigger screens I changed the layout during coding, so it looks and functions better.

- Completing HTML text with links, form details, sign up button, icons and classes to be able to apply the layout and design.

- Creating toggle menu.

- Finding background images, color palette and font family that fits to the project.

  **Image:** related to the topic, so when the users look at it, they instantly know what the page is about.

**Color palette:** I chose calming colors from the main photo with a color picker.

_Choosing the main color with color picker:_

![chosing the main color with color picker](</assets/images/readme-images/color picker.png>)

**Font family:** I chose two types, one is pretty for the titles and logos, the other is simple and easy to read.

### Second part: CSS

I was working on sections one by one, making them also responsive:

- Changing the layout of _Menu_ (checkbox toggle is not working) and making header responsive.
- Adding pseudo classes.
- Making background image responsive and adding aria labels to that. Adding color under the image in case it doesn't load.
- Positioning h1 and h2 - check in developer tools.
- Styling _About_ section, making it responsive.
- Styling _Sign up_ section and making it responsive.
- Styling footer, making it responsive.

### Optimization, last touches

- Changing images to smaller format for faster loading.
- CSS validator - mistake: font-style: bold - corrected to font-weight: bold.
- HTML validator - a meta element was missing the closing tag - corrected.
- Lighthouse check - laptop 100%, mobile 75% - compressed image one more time.
- Optimizing font-size as a general CSS rule.

  If the users use the menu instead of scrolling, they should be able to see the _Sign up_ section in one piece.

## Workflow

- Working with the live server - to see immediately the changes.
- Using prettier for an easier, more smooth coding process and to note mistakes easier.
- Testing continuously and paying attention of problems on the terminal.
- Using keyboard shortcuts and Emmet for the faster process.
- Continuously checking and trying out things in developer tools.
- Commiting and pushing all changes.

## Technology

_Programs:_

- [VS Code](https://code.visualstudio.com/)
- [Github](https://github.com/)

_Planning:_

- [Balsamiq wireframes](https://balsamiq.com/wireframes/desktop/)

_Font family:_

- [Google fonts](https://fonts.google.com/)

_Images and icons:_

- [Compress JPG](https://compressjpeg.com/)
- [Tiny PNG](https://tinypng.com/)
- [Convert io](https://convertio.co/jpg-webp/)

_Color palette:_

- [Chrome color picker](https://chrome.google.com/webstore/detail/color-picker-for-chrome/clldacgmdnnanihiibdgemajcfkmfhia)

_Validating:_

- [Am I responsive?](https://ui.dev/amiresponsive)
- [W3C CSS validator](https://jigsaw.w3.org/css-validator/)
- [W3C HTML validator](https://validator.w3.org/)

## Bugs and solutions

1.  Checkbox toggle was not working on the one-page website, because the menu jumps back only when the page is refreshed.

    -> Removed toggling, made the menu smaller on the top of the page. I divided the logo and the menu links to two rows, so there is enough space for them, they are readable and easy to click/tap on.

2.  Header covered the sections when they were open from the menu links.

    -> Added padding top - at least the size of the header.

3.  There was a LOCK file in the repository so I couldn't commit.

    -> Deleted it manually.

4.  Menu covered the logo.

    -> Added z-index.

5.  Prettier ruins the consistency of HTML format.

    -> Changed it in the end.

## Deployment

1. Log in to my GitHub account
2. Go to _Your repositories_ in my menu, and select _Yoga-project_
3. Choose _Settings_ from the project's menu
4. On the left side under _Code and automation_ select _Pages_
5. Under _Source_ select _Deploy from a branch_
6. Under _Branch_ select _Main_, _/(root)_ and click on _Save_
7. Go back to _Code_ in the project's menu on the top
8. On the right side in _Deployments_ section click on _Github-pages_
9. On the left side under _Deployments_ click on _Enviroments_
10. Under _Active deployments_ and _Github-pages_ I can click on the project's deployed link and open it

### Run the project locally

1. Open the Github repository
   https://github.com/saroltah/yoga-project

2. Select the green _Code_ dropdown, under _Clone_ copy the HTTPS link

3. Open your IDE, and your chosen directory in it

4. Open your terminal and type _git clone_ and paste the link

5. Now the clone is ready to be used.

## Testing

Tried on mobile, tablet, laptop and desktop screen view.

| What to do                                                                        | How to do                                                                                                         | Expected outcome                                                                                   | Actual Outcome                                                                                                                                |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Header, menu and logo always visible                                              | Scrolling the page, clicking on menu links                                                                        | Header, menu and logo always visible                                                               | Header, menu and logo always visible                                                                                                          |
| _Home_ link leads back to _Home_ section                                          | Click on _Home_ link                                                                                              | Goes back to homepage, where h1 and h2 is visible                                                  | Goes back to homepage, where h1 and h2 is visible                                                                                             |
| _About_ leads to _About_ section                                                  | Click on _About_ link                                                                                             | Goes to _About_ section, the _Who are we?_ paragraph is visible                                    | Goes to _About_ section, the _Who are we?_ paragraph is visible                                                                               |
| _Sign up_ leads to _Sign-up_ section                                              | Click on _Sign up_ link                                                                                           | Goes to _Sign-up_ section, where the sign up form is visible, with all questions and button        | Goes to _Sign-up_ section, where the sign up form is visible, with all questions and button                                                   |
| _Contact_ leads to _Contact_ section                                              | Click on _Contact_ link                                                                                           | Goes down to the bottom of the page so the whole _Contact_ section is visible                      | Goes down to the bottom of the page so the whole _Contact_ section is visible                                                                 |
| The menu links change color when clicking on them                                 | Click on the links one by one                                                                                     | They all change color (from black to brown until clicking somewhere else)                          | They all change color (from black to brown until clicking somewhere else)                                                                     |
| The header layout is different for laptop (or bigger) screens                     | Resize the page in developer tools                                                                                | Logo and menu is in the same line                                                                  | Logo and menu is in the same line                                                                                                             |
| The _About_ section image has background on tablet size and bigger                | Resize the page in developer tools                                                                                | The _About_ section image has two rectangles behind it                                             | The _About_ section image has two rectangles behind it line                                                                                   |
| The text and email type of input fields change color when clicking on them        | Pointing the cursor on them, then click on them one by one                                                        | They all change color - from brown to light blue when pointing, then black when clicking           | They all change color - from brown to light blue when pointing, then black when clicking                                                      |
| The submit input changes color when pointing on it                                | Pointing the cursor on it, then click on it                                                                       | It gets a light blue box shadow instead of brown, and the border disappears.                       | It gets a light blue box shadow instead of brown, and the border disappears                                                                   |
| The text input fields are required                                                | Trying to submit them empty one by one                                                                            | It doesn't let submit, it writes out that the field needs to be filled                             | It doesn't let submit, it writes out that the field needs to be filled                                                                        |
| The email input field is required                                                 | Trying to submit it empty, then without the @, then without anything in front of @, then without anything after @ | It doesn't let submit, it writes out that the field needs to be filled with the right email format | It doesn't let submit, it writes out that the field needs to be filled with the right email format                                            |
| The submit button is working, and the form attributes are correct                 | Click on _Sign up_ button                                                                                         | It shows the written data on Code Institute's form-dump page                                       | It shows the written data on Code Institute's form-dump page                                                                                  |
| The input name and value is added correctly                                       | Submit the data (click on _Sign up_ button)                                                                       | On Code Institute's form-dump page the _Input name_ and _Value_ table is correct                   | On Code Institute's form-dump page the _Input name_ and _Value_ table is correct                                                              |
| The Footer has different layout on tablet size or bigger                          | Resize the page in developer tools                                                                                | The contact icons have no longer border, and the logo icon appears on both side                    | The contact icons have no longer border, and the logo icon appears on both side                                                               |
| The contact icons change color, and cursor turns to pointer when hovering on them | Hover on a contact icon                                                                                           | They change color to brown from black, the cursor turns to pointer                                 | They change color to brown from black, the cursor turns to pointer                                                                            |
| The Facebook icon / link is correct and opens in a new tab                        | Click on Facebook icon                                                                                            | It opens Facebook page in a new tab                                                                | It opens Facebook page in a new tab                                                                                                           |
| The Instagram icon / link is correct and opens in a new tab                       | Click on Instagram icon                                                                                           | It opens Instagram page in a new tab                                                               | It opens Instagram page in a new tab                                                                                                          |
| The Twitter icon / link is correct and opens in a new tab                         | Click on Twitter icon                                                                                             | It opens Twitter page in a new tab                                                                 | It opens Twitter page in a new tab                                                                                                            |
| The Email icon / link is correct and opens in a new tab                           | Click on Email icon                                                                                               | It opens my email server with the receiver's email address:*info@relief.com* in a new tab          | It opens my email server with the receiver's email address:*info@relief.com* in a new tab                                                     |
| Responsive on all screen sizes                                                    | Open developer tools and check, use _Am I responsive?_ website                                                    | It looks good and all the functions are working properly in all sizes                              | It looks good and all the functions are working properly in all sizes.                                                                        |
| Correct CSS file                                                                  | Copy the code to _W3C CSS validator_ website.                                                                     | There are no errors                                                                                | There are no errors.                                                                                                                          |
| Correct HTML file                                                                 | Copy the code to The _W3C HTML validator_ website.                                                                | There are no errors                                                                                | There are no errors. It only mentions that the slash is not necessary for self-closing tags. Prettier corrects the code and put the slash in. |

_Checking email input:_

![input email](</assets/images/readme-images/input email check.png>)

_Checking submit button and form details:_

![Code institute formdump](</assets/images/readme-images/checking submit button.png>)

_Checking twitter icon:_

![Twitter icon gets gold color hovering](</assets/images/readme-images/twitter icon.png>)

_Am I responsive?_

![am i responsive image](</assets/images/readme-images/Am i responsive.png>)

_HTML validator:_

![HTML validator result](</assets/images/readme-images/html validator.png>)

_CSS validator:_

![CSS validator result](</assets/images/readme-images/css validator.png>)

**Lighthouse check for desktop devices:**

**Desktop:**

- Performance: 100%
- Accessibility: 100%
- Best Practices: 100%
- SEO: 100%

![Lighthouse desktop](</assets/images/readme-images/lighthouse desktop-1.png>)

**Mobile:**

- Performance: 96%
- Accessibility: 100%
- Best Practices: 100%
- SEO: 100%

![Lighthouse mobile](</assets/images/readme-images/lighthouse mobile-2.png>)

## Credits

_Font family:_

- Inspired by my own [Bob Ross project](https://bob-ross-fan-page-by-sarolta-h.netlify.app/)

_Images and icons:_

- Font awesome icons: [Spa](https://fontawesome.com/icons/spa?f=classic&s=solid), [Facebook](https://fontawesome.com/icons/facebook?f=brands&s=solid), [Instagram](https://fontawesome.com/icons/instagram?f=brands&s=solid), [Twitter](https://fontawesome.com/icons/twitter?f=brands&s=solid), [Envelope](https://fontawesome.com/icons/envelope?f=classic&s=solid)

- [Unspalsh Image by Akemi Mory](https://unsplash.com/photos/LaKVSiT4rR8)
- [Pexels Image by Karolina Grabowska](https://www.pexels.com/photo/flexible-sportswoman-doing-yoga-exercise-at-home-4498158/)

Special thanks to [Code Institute](https://codeinstitute.net/se/full-stack-software-development-diploma/?utm_term=code%20institute&utm_campaign=CI+-+SWE+-+Search+-+Brand&utm_source=adwords&utm_medium=ppc&hsa_acc=8983321581&hsa_cam=14660337051&hsa_grp=134087657984&hsa_ad=635849372549&hsa_src=g&hsa_tgt=aud-594467886660:kwd-319867646331&hsa_kw=code%20institute&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gad=1&gclid=CjwKCAjw4P6oBhBsEiwAKYVkqzzIpIRAmKF-tC7OHL0D0ijr9ic8Bv2gLino_uOt3SWXrRzbR7NoNhoCisIQAvD_BwE) and my mentor **Ronan McClelland** for reviewing, helping and answering all my questions.
