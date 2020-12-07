# ucaas-poly-babel
Universal Compiler as a Service (or Web Page)

# TODO
 - Use ANTLR4 with JavaScript Target.
 - Generate parser in JS for each grammar.
 - Create JS project (npm init)
  - Install ANTLR4 npm package.
  - Setup webpack
 - Generate generic transformation adding log statements for each grammar.
 - Run code, save output from log statements.
 - Now we have inputs and outputs for each node: use this to generate interpreter in JS.
 - Product: Universal JS Interpreter for any language.
 - Generate transformation rules based on node inputs and outputs for each language.
 - Product: Language translator from any to any language.
 
# UI
 - Present user a number of choices from 1 to 9 ("tab completion").
 - Base choices on current code in editor, cursor position and grammar.
 - New symbol, new for loop etc.
 - Append new or correct old text.
 - Multiple editing modes with affirmative visual indication of mode.
 - Navigation based on AST.
 - Optional fancy graphics like space shooter to select a choice.
 - Cute 3D animals as animated symbols in your code.
 - Can all local variables be graphical symbols? Or have a toggle.
 - Time travelling debugger, watches, inspection, step debugging.
 - Graph usage: show branches, next change, parent, deltas.
 - Code visualization: Architecture diagrams. Program edit history (literal programming, read it is a book).
 - Mapping onto 3D landscape for memorization. Themes for different areas: biomes, reflected also in theme for code edit window and variable symbols.
 - Treemap based on code size?
 
# Resources
 - https://github.com/denvash/codingame-puzzles-solutions/tree/master/1-Easy
 - https://github.com/replit/polygott
 - https://github.com/replit/polygott/tree/master/languages
 - https://hub.docker.com/r/replco/polygott
 - https://www.antlr.org/
 - https://github.com/antlr/antlr4/blob/master/doc/javascript-target.md
 - https://github.com/antlr/antlr4/blob/master/doc/targets.md
 - https://medium.com/dailyjs/compiler-in-javascript-using-antlr-9ec53fd2780f
 - https://tomassetti.me/antlr-mega-tutorial/#csharp-setup
 - https://github.com/uwol/proleap-vb6-parser/blob/master/src/main/antlr4/io/proleap/vb6/VisualBasic6.g4
 - https://github.com/antlr/grammars-v4
 - https://github.com/antlr/antlr4
 - https://github.com/cefsharp/CefSharp/wiki/Quick-Start
 - https://plasma-umass.org/doppio-demo/
 - https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor
