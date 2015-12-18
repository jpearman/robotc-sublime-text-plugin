<h1>RobotC Sublime Text 3 plugin package</h1>

A plug-in package for Sublime Text 3 (http://www.sublimetext.com/) for writing RoboMatter RobotC (http://www.robotc.net/) code for Vex EDR and other RobotC platforms. Allows you to write RobotC code on Mac OS X, Linux and Windows in a very clean and fast text editor. Does not compile or debug, you need the IDE for that.

<h2>Functionality</h2>
The plug-in provides the following functionality:
<ol>
<li>C syntax color formatting via the Command Palette.</li>
<li>Basic C code snippets via the completions list.</li>
<li>RobotC functions and variables completions via the completions list.</li>
<li>Search for relevant RobotC functions and variables by category via the completions list.</li>
</ol>
All RobotC platforms are covered but completions are specific to the VEX Cortex.

<h2>Installation:</h2>
<ol>
<li>Copy RobotC_v*-*.sublime-package to ~/Library/Application Support/Sublime Text 3/Installed Packages on Mac OS X. There are Linux and Windows installation instructions at http://docs.sublimetext.info/en/latest/extensibility/packages.html</li>
<li>Start Sublime Text and the package should auto-install.</li>
</ol>
There are a few ways to check this, the easiest is to open the Command Palette and type 'syntax' and look for 'RobotC' in the list.
Once the code is a bit better I will get it registered to install with the excellent Package Control (http://wbond.net/sublime_packages/package_control) 

<h2>Usage</h2>
Once RobotC syntax selected. The main RobotC functionality is in the functions and variables completion list.
<ol>
<li>To auto-complete a function or variable, start typing a function name, variable name or code snippet name using lower case and access the completions list with CTRL+spacebar. Each value within a function can be jumped between with the TAB key.</li>
<li>To search for all the functions and variables within a RobotC category, start typing a category name in UPPER case e.g. 'MOTORS' will list all the commands related to motors.</li>
<li>To access code snippets start typing their name in the completions list e.g. 'main' or 'for'. Have a look in the RobotC package directory for current snippets.
</ol>

<h2>Versions:</h2>
<ul>
<li>0.1 - getting something working.</li>
<li>0.2 - full functions and variables completion with TAB between values. Search via category and platform. Descriptions improved.</li>
<li>0.3 - full Update to make VEX specific, add competiotn template snippet, change file extension to robotc so as not to clash with normal C files</li>
</ul>

<h2>Attribution:</h2>
<ol>
<li>Original author 'mike >-at-< mikemcfarlane >-dot-< co >-dot-< uk'</li>
<li>RobotC.sublime-completions is built around 'BuiltInVariables.txt' provided with the RobotC IDE installation.</li>
<li>RobotC.tmLanguage is currently a lightly edited copy of the file 'C.tmLanguage' included with Sublime Text.</li>
<li>2015 updates by jpearman.
</ol>

<h2>License:</h2>
MIT
