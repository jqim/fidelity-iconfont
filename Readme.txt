# Fidelity Icons
## Version 1.8 30 May 2016

### How to add a new Icon

01. Add icon to this file in one of the empty slots
02. Ensure it fits on the pixel grid
03. Use only 1px thick lines
04. Leave a minimum of 1px white space between fills
05. Expand all lines to fills and unite all shapes to one <Compund Path> (cmd + 8)
06. Only use 1 colour, 262626(Tip: it’s a swatch)
07. Give the icon a CSS class name. Use lowercase and a “-” to separate name parts
08. Name the artboard with the CSS class (not the icon bit though) 
09. Update the date above to todays date
10. Make sure all layers apart from “Icons” is set to a template in Layer Options (double click layer)
11. Export artboards as SVG’s 
12. When exporting use the file name ‘.svg’ (the icon prefix gets added in ico.mo)
13. Use SVGOMG ( https://jakearchibald.github.io/svgomg/ ) to optimise the svg code
14. Upload new svg’s to the Fidelity Icon Font on icomoon.io
15. Generate and download font
16. Open a Jira ticket to implement the updated front and describe the new icon and its intended use