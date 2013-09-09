<h1>RobotC Sublime Text 2 plugin package</h1>

A plug-in package for Sublime Text 2 (http://www.sublimetext.com/) for writing RoboMatter RobotC (http://www.robotc.net/) code for Lego Mindstorms NXT and other RobotC platforms. Allows you to write RobotC code on Mac OS X, Linux and Windows in a very clean and fast text editor. Does not compile or debug, you need the IDE for that.

<h2>Functionality</h2>
The plug-in provides the following functionality:
<ol>
<li>C syntax color formatting via the Command Palette.</li>
<li>Basic C code snippets via the completions list.</li>
<li>RobotC functions and variables completions via the completions list.</li>
<li>Search for relevant RobotC functions and variables by category via the completions list.</li>
</ol>
All RobotC platforms are covered including Lego Mindstorms NXT, VEX, Cortex, PIC, Tetrix and Arduino, although there may be emphasis towards Mindstorms NXT as that is my primary platform.

<h2>Installation:</h2>
<ol>
<li>Copy RobotC_v*-*.sublime-package to ~/Library/Application Support/Sublime Text 2/Installed Packages on Mac OS X. There are Linux and Windows installation instructions at http://docs.sublimetext.info/en/latest/extensibility/packages.html</li>
<li>Start Sublime Text and the package should auto-install.</li>
</ol>
There are a few ways to check this, the easiest is to open the Command Palette and type 'syntax' and look for 'RobotC' in the list.
Once the code is a bit better I will get it registered to install with the excellent Package Control (http://wbond.net/sublime_packages/package_control) 

<h2>Usage</h2>
Once RobotC syntax selected. The main RobotC functionality is in the functions and variables completion list.
<ol>
<li>To auto-complete a function or variable, start typing a function name, variable name or code snippet name using lower case and access the completions list with CTRL+spacebar. Each value within a function can be jumped between with the TAB key.</li>
<li>To search for all the functions and variables within a RobotC category, start typing a category name in UPPER case e.g. 'BLUETOOTH' will list all the commands related to bluetooth. (See the file 'BuiltInVariables.txt' included with the RobotC IDE installation, or look at the API titles.)</li>
<li>You can also search in similar way via platform name shortcuts (see the file 'BuiltInVariables.txt' included with the RobotC IDE installation) e.g. 'NT' for Mindstorms NXT.</li>
<li>To access code snippets start typing their name in the completions list e.g. 'main' or 'for'. Have a look in the RobotC package directory for current snippets.
</ol>

<h2>Versions:</h2>
<ul>
<li>0.1 - getting something working.</li>
<li>0.2 - full functions and variables completion with TAB between values. Search via category and platform. Descriptions improved.</li>
</ul>

<h2>To do:</h2>
<ol>
<li>Create a RobotC specific version of the .tmLanguage file?</li>
<li>More code snippets e.g. while loops.</li>
<li>Code snippets often come up twice as the scope of RobotC is the same as C ie .c files. Fix this so snippets only come up once. If this bothers you at the moment, delete the .sublime-snippet files in the RobotC package directory.</li>
<li>Figure out a quick way to get the code into the RobotC IDE.</li>
<li>Add support for RobotC Driver Suite from Xander Soldat.</li>
<li>Review changes from RobotC 3.55, and build in.</li>
<li>Test it:-))</li>
</ol>

<h2>Bugs:</h2>
This project is not actively maintained now.
Report to 'mike >-at-< mikemcfarlane >-dot-< co >-dot-< uk'


<h2>Attribution:</h2>
<ol>
<li>RobotC.sublime-completions is built around 'BuiltInVariables.txt' provided with the RobotC IDE installation.</li>
<li>RobotC.tmLanguage is currently a lightly edited copy of the file 'C.tmLanguage' included with Sublime Text.</li>
</ol>

<h2>License:</h2>
MIT
