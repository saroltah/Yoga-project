# Relief Yoga & Meditation

## Idea

An online library of meditation and yoga classes which are focusing on stress and anxiety relief.

Goal of this website: give information about an application which helps people being more wholesome

User needs: more available online platforms which help to relax and relieve everyday stress

Importance: to be able to live healthy and fulfilled lives with healthy minds

This website presenting a starting business, tells what the library would be about, and gives opportunity to sign up. The log-in details would be sent by email - after log-in would be able to see the videos.

- Spcific stand-out: all the videos would be made by, certified and professionalyoga masters

- People can use the app anywhere anytime

How they can get access to the information: short paragraphs, only relevant information, with a menu that helps them to find what they are looking for.

## Build-up

I. Logo & menu - on the top - for easy navigation

II. The name and short describtion what is the page about.

III. Giving reasons of using the website - user conciders why they need the app, what can it help with.

IV. Specifying why to choose this app over others, what are the adventages.

V. Sign up form, where the user can registrate to be member.

VI. Contact details - for the users who have questions and social media links to find out more information about the business.

Shortly: The user sees what the website is about, then think about if they need it, see adventages why this website is a good option over other platforms, get the option to sign up and try it out, and the also the option to read more or get in contact.

## My work Process

### First part - HTML

- Adding basic files and folders
- Adding meta tags - keywords, describtion and css link - make the background red to test
- Deploying my site, to see if everything works
- Taking notes and printscreens
- Concidering ux principles i plan the main sections with text of my project
- Writing text first in a text document - to check text for correct spelling, grammar and semantics
- Wiritng the HTML document with background color, to see if the structure is fine and also it is easier to visualize the design how big space they take
- Design layout on wireframe

  The bigger the screen the more columns can have

- Completing html text with links, form details, sign up button, icons and classes to be able to apply the layout & design

- Creating the toggle menu

- Finding background photos, colorpalette and fontfamily to that fits to the project

### Second part: CSS

I am working form up to down styling the sections one by one, making them also responsive:

- Changing the layout of menu (checkbox toggle is not working) and make menu responsive
- Adding pseudo classes
- Making background photo responsive & adding aria label to that. Adding color under the image in case it doesn't load.
- Positioning h1&h2 - check in devtools.
- Styling about section
- Styling signup section & make it responsive
- Styling footer

### Optimization, last touches

- Changing images to smaller format for faster loading
- CSS validator - mistake: font sytle: bold - corrected to font weight.
- HTML validator - a meta element was missing closing tag.
- Lighthouse check - laptop 100%, mobile 75 - still slow
- Optimizing font-size as general CSS rule

  Concidering font size: if user uses the menu instead of scrolling, they can see the section in one piece. (most important for sign up section)

## Workflow

- Working with live server - to see immediately the changes.
- Using prettier for easier more smooth coding process and to note mistakes easier.
- Testing continuosly and paying attention of _promlems_ on the terminal.
- Using keybord shortcuts and Emmet for the faster process.
- Continuosly checking and trying out things in developer tools.

## Bugs and solutions

1.  Checkbox toggle was not working in the one-page website, because the menu only goes back to hamburger icon when the page is refreshed.

    Removed toggling, made menu smaller on the top of the page. I put the logo and the menu links in 2 lines, so there is space between them, they are readable and easy to click/tap on.

2.  Header covered the sections when they were opened from menu links.

    Added padding top - at least size as the header

3.  There was a LOCK file in the repository so couldn't commit.

    Deleted it manually.

4.  Menu was covering logo.

    Added z-index

5.  Prettier ruins the consistence of HTML format - changed it in the end.

## Testing

Tried on mobile, tablet and laptop screen view.

| What to do                                                                 | How to do                                                  | Expected outcome                                                                          | Outcome                                                                                   |
| -------------------------------------------------------------------------- | ---------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Header, menu and logo always visible                                       | Scrolling the page, clicking on menu links                 | Header, menu and logo always visible                                                      | Header, menu and logo always visible                                                      |
| Home link leads back to Home section                                       | Click on Home link                                         | Goes back to homepage, where h1, h2 is visible                                            | Goes back to homepage, where h1, h2 is visible                                            |
| About leads to About section                                               | Click on About link                                        | Goes to About section, where the Who are we? paragaraph is visible                        | Goes to About section, where the Who are we? paragaraph is visible                        |
| Sign up leads to Sign-up section                                           | Click on Sign up link                                      | Goes to Sign-up section, where the sign up form is visible, with all questions and button | Goes to Sign-up section, where the sign up form is visible, with all questions and button |
| Contact leads to contact section                                           | Click on Contact link                                      | Goes down to the button of the page so the whole Contact section is visible.              | Goes down to the button of the page so the whole Contact section is visible.              |
| The menu links change color when clicking on them                          | Click on the links one by one                              | They all change color (from black to brown until i click somewhere else)                  | They all change color (from black to brown until i click somewhere else)                  |
| The text and email type of input fields change color when clicking on them | Pointing the curzor on them, then click on them one by one | They all change color - from brown to light blue when pointing, then black when clicking. | They all change color - from brown to light blue when pointing, then black when clicking. |
| The submit input changes color when pointing on it                         | Pointing the curzor on it, then click on it                | It gets a light blue boxshadow instead of brown, and the border disappeares.              | It gets a light blue boxshadow instead of brown, and the border disappeares.              |
| The text input fields are required                                         | Trying to submit them empty one by one                     | It does'nt let submit, it writes out note that the you have to fill the                   | It gets a light blue boxshadow instead of brown, and the border disappeares.              |

## Credits

Programs:

- VS Code
- Github

Planning:

- Balsamiq wireframes

Font family:

- Google fonts

Images and icons:

- Font awesome
- Unspalsh
- Pexels
- https://compressjpeg.com/
- https://tinypng.com/
- https://convertio.co/jpg-webp/

Color palette:

- Chrome color picker

Special thanks to Code Institue and my mentor Ronan McClelland for reviewing, helping and answering to all my questions.
