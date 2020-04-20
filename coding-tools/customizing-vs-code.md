# Configuring VS Code
Visual Studio Code (the “Code” is significant, do not confuse this with Visual Studio) is a feature-laden text editor that will allow you to write code on your own computer in a manner reminiscent of the center panel in your three-panel learning environment on Codecademy.com.

If you’ve done lessons with Codecademy before, you’ve likely already done some initial configuration of your VS Code workspace. In this article, we’ll go through some core settings and extensions for VS Code, as well as a number of fancier ones, beyond that initial setup. You likely won’t end up using all of these, as some are better suited for certain languages and personal preferences than others, but you can always refer back to this list in the future. 

As you can see in [this post by the VS Code team](https://code.visualstudio.com/docs/getstarted/tips-and-tricks) and [this video](https://www.youtube.com/watch?v=t9kSTiqhUfg), using effective shortcuts and increasing productivity is almost always what developers mean when they talk about “using VS Code like a pro.” Which makes sense! Who doesn’t want to get through their work more quickly and efficiently? Here, we’ll review the settings, themes, and extensions that will help you maximize your productivity in VS Code. 

## VS Code settings and themes  

### Settings
If you haven’t yet already, our team suggests adjusting a few of the default VS Code settings to maximize your comfort and productivity. A quick reminder - when you change User Settings, it affects all of your projects. If you want to make changes to a specific project, you can use Workspace Settings. You can find all of the settings, plus VS Code’s very powerful search function, in the menu on the left side of the screen. 

![key VS Code settings](https://i.imgur.com/DesEy3j.png "key user settings in VS Code") 



This screenshot is from [this Codecademy webinar](https://www.youtube.com/watch?v=obhLwg4V95g), the highlights of which are encapsulated in this piece. We’ll include timestamps to this video throughout this post, so you can refer back to that video for visual details if you like. 

Here are a few settings that will make your coding life a lot easier: 

*Word Wrapping:* When you’re writing very long code, you ideally don’t want to have to continually scroll all the way to the right to keep working or editing. Being able to see everything you’ve written without scrolling is far more efficient. Word wrapping automatically drops the text to the next line without compromising the code. Turn this one on. 

*Font Size:* Eyestrain is real, folks. We recommend increasing the font size to make your code more readable and to save your eyes during the many, many hours you’ll be in VS Code. How much larger you make it is up to you, but don’t forget about this setting. 

*Cursor Style:* In a similar vein, changing your cursor style can boost your productivity in VS Code. The default cursor setting is the standard blinking line. One of our Codecademy instructors really recommends using the block cursor, as it’s much easier to find as you’re moving around. Try it out for yourself! 

*Whitespace Indicator:* As you probably guessed from the name, the whitespace indicator shows you where there is white space in your code. Not everyone uses a whitespace indicator, but our instructors like them. You’ll see an alternative to this whitespace indicator in the extensions section below. 

### Themes
Themes are highly personal, and a number of prominent developers have created their own. In selecting a theme, you should think about what works best for you in terms of your own visual and organizational style. Some prefer high contrast themes, so that the code stands out, and some don’t. 

To install a theme, go to the Marketplace, search for “themes,” and take a look at the most popular ones. Fortunately, most of the themes have previews, so you can test drive one before you install it. Select the theme you like and hit “reload,” - you can install the theme while still in the program.
If you’re not sure where to start with themes, you can always use [the Codecademy theme](https://marketplace.visualstudio.com/items?itemName=codecademy.codecademy-syntax-theme), and branch out later. 

You can also change the default syntax highlighting, if you prefer a different color scheme. Good color themes can also help save your eyesight by rendering all those lines of code easier to read. To do this, select Color Theme from the Welcome page when you first open Visual Studio Code, or click on Code in the menu bar at the top of your desktop window, then click on Preferences, followed by Color Theme. You can also search for color themes to install using the Extensions menu.

 
## VS Code Extensions
There are a jillion* extensions available in VS Code (*jillion is our estimate, not a real number). You can find all jillion in the Marketplace. Developers use a combination of extensions to make their code easier to write, easier to understand, more accurate, and/or to get through writing large blocks of code more quickly. 

We’ll start off here by listing the extensions we think are most helpful to Codecademy learners, regardless of which coding language you are learning… beyond the official [Codecademy theme](https://marketplace.visualstudio.com/items?itemName=codecademy.codecademy-syntax-theme) that is.

### The Must-Haves
To find each of these extensions, type the name of the extension into the search bar. We’ve listed each one with its searchable name. (For reference, this section starts [at 22:30](https://youtu.be/obhLwg4V95g?t=1410) in the Codecademy webinar referenced above).

**The extensions that will keep you organized**

1. [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag): this extension helps you avoid typos or accidentally lose your place. If you change a div name, Auto Rename Tag will automatically change the other end (meaning, if you change the opening, it will automatically change the closing, or vice versa). 

2. [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag): as you might guess, it closes your brackets for you. If you’re using Emmet (more on that below) you may not need Auto Close Tag, but if you aren’t, it’s a must. 

3. [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer): this extension is most helpful for Javascript, but can be used with other languages. Bracket Pair Colorizer color-matches code and parentheses, and maintains a line between the opening and closing brackets to better keep track of where the code is and to ensure that you never get lost in bracket hell. It’s really helpful in finding missing brackets. 

4. [Indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow): if you’re not a fan of the whitespace indicator setting mentioned above, this is the extension for you. It creates color-coded rainbow bars to help you line up your code and stay organized. This may be hard to visualize - you’ll find it at 25:16 in the Codecademy webinar.

5. [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks): speaking of staying organized, this is an extremely handy extension that places small blue bookmarks in the margins of your file and adds a small panel right below your file browser which lists all active bookmarks in the current project. You can then easily switch between places in the file and/or leave reminders for yourself to go back to certain snippets of code. Super useful!

**The extensions that will make it easier for others to read your code**

1. [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): as the name implies, it makes your code look prettier by formatting it properly.  Prettier code is more readable by others. *This is very important.* When you’re learning, you’re often focused on making sure the code works. In the outside world, you’re usually writing code for others, so having prettier code can give you a real edge in a job interview or in a work presentation, or when you’re collaborating with your team. During the learning process, pay close attention to what Prettier does with your code. You can learn a lot about proper formatting by following along with Prettier instead of just letting it do the work for you.  

2. [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify):  Since Prettier does not work for all coding languages (the biggest one being HTML), Beautify is another good plugin to have. [This guide](https://css-tricks.com/prettier-beautify/) will show you how to install it and adjust your settings so that Beautify doesn’t interfere with your Prettier settings. 
 
3. ESLint: A linter is a program that analyzes your code for potential programmatic and stylistic errors. It is a static analysis tool that can spot errors before you debug, and can ensure that your code adheres to a specific style guide, which is especially important when multiple people are working on code together. Linting your code will help you ensure that you’re following the formatting requirements of your project or your employer. Think of it as a kind of spelling and grammar check for your source code. It’s especially useful to lint code in interpreted programming languages, such as Javascript, Python, HTML, and CSS. There are linters for each of those languages. We highly recommend installing a linter, and suggest starting with [ESLint (Javascript)](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint). A quick search for programming language + lint will yield a linter for other programming languages (CSSLint, etc.).   

For a visual walk through of the configuration of these extensions, check out [this Wes Bos video on Prettier + ESLint in VS Code.](https://www.youtube.com/watch?v=YIvjKId9m2c)

## Emmet and Intellisense 
[Emmet](https://code.visualstudio.com/docs/editor/emmet) and [Intellisense](https://vscode.readthedocs.io/en/latest/editor/intellisense/) are not extensions, per se, as they are both baked into VS Code. (Please review the links to each program for the VS Code user guides). We’re highlighting them here because both can be enormously helpful if you understand the key features of each one. 

### Emmet
Emmet abbreviations and shortcuts speed up your code writing process. It kind of looks like autocomplete for code in that it expands snippets for you. Emmet abbreviation and snippet expansions are enabled by default in `html`, `haml`, `jade`, `slim`, `jsx`, `xml`, `xsl`, `css`, `scss`, `sass`, `less` and `stylus` files, as well as any language that inherits from any of the above like `handlebars` and `php`. We highly recommend reviewing [the VS Code section of this site](https://vscode.readthedocs.io/en/latest/editor/emmet/#emmet-in-visual-studio-code) for more info on and visuals of configuring Emmet. 

For example, Emmet is especially helpful when you’re doing front end work, and can save you a lot of time with its shortcuts to boilerplate language. The screenshot below has an example of Emmet’s shortcut to boilerplate on HTML websites. (P.S. you can also use [this HTML Boilerplate](https://marketplace.visualstudio.com/items?itemName=sidthesloth.html5-boilerplate) extension).

![demonstration of Emmet](https://i.imgur.com/DesEy3j.png "Emmet in action") 

As you can see from the screenshot, the Emmet section of the Codecademy webinar starts [around 28:10](https://youtu.be/obhLwg4V95g?t=1690). Since this may be easier to understand if you can see it, we do suggest checking out this part of the webinar (especially the bit about multicursor functions at the end).  

For a little more on Emmet for HTML and CSS, check out [this quick run through.](https://efficientuser.com/2017/11/12/emmet-in-vs-code/) If you find yourself in need of a cheat sheet to Emmet documentation, you can find one [here](https://docs.emmet.io/cheat-sheet/). 

### Intellisense
Intellisense is a code completion tool. It automatically supports JavaScript, TypeScript, JSON, HTML, CSS, Less, and Sass. When you start typing a code item, VS Code will offer suggestions that you can use. Intellisense covers a few languages out of the box(Javascript, Typescript, HTML, JSON, CSS, Lisp, and SAS) but if you are using one that isn’t covered (like Python) you can search for “Python” in the extension marketplace and find the extension for Python that helps with Intellisense. Intellisense can show you what may be coming next in your code, and can autocomplete variables you make on the same page. See the screenshot below, from the [35:00 mark](https://youtu.be/obhLwg4V95g?t=2100) in the webinar:

![demonstration of intellisense](https://i.imgur.com/CasYqWZ.png "Intellisense in action")

As with Prettier, above, use Intellisense wisely. Pay attention to what it suggests and why, and how often you select certain options. It’s a great tool, but don’t overly rely on it at the expense of your learning!


## Language-specific resources and some odds and ends
Many extensions are language-specific. The good news is that most of them have counterparts in other programming languages, which a quick search can unearth fairly easily. Usually, you’ll end up typing the extension and the language in the search bar (as we demonstrated above with CSSLint) and you’ll be all set. You can also ask questions about and learn more about different VS Code setups in the Codecademy or [reddit](https://www.reddit.com/r/vscode/) communities.  

As you can likely tell from how long this post is, there are a vast multitude of options for extensions and customizations in VS Code. You can always see which are the most popular (and likely the most effective) in the Marketplace, as they are ranked. Here are a few more extensions we really like and recommend, just for fun. Review the list, and if the descriptions don’t apply to the work you’re doing right now, feel free to circle back when they do! 

[Firebase](https://marketplace.visualstudio.com/items?itemName=toba.vsfire): Syntax highlighting, code completions and hover help for new Firestore security rules and index definitions.

[Chrome Debugger](https://code.visualstudio.com/blogs/2016/02/23/introducing-chrome-debugger-for-vs-code): allows front-end developers to debug their client-side JavaScript code running inside Google Chrome directly from Visual Studio Code.

[Gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore): as you’d imagine, it’s language support for .gitignore files. 

[Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare): collaboratively edit and debug with others in real time, regardless what programming languages you're using or app types you're building.
