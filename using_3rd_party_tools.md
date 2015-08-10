## Scribus & 3rd Party Tools

Scribus can play nice with different FOSS tools. To learn how to use those tools is mentioned is out of the scope of this manual section (provide link to appropriate place). In this particular section we will find out: 
* what 3rd party tools work with Scribus 
* if said tools are installed properly 

### LaTeX
* Make sure pdflatex is installed and in your $PATH
* Linking ```pdflatex --interaction nonstopmode``` to Scribus > Preferences > External Tools > Render Frames

### Python

### Uniconverter
* Install via Homebrew ```brew install --HEAD uniconverter```
* Linking ```/usr/local/Cellar/uniconverter/HEAD/bin/uniconvertor``` to Scribus > Preferences > External Tools > Uniconverter

### GIMP
* Install via Gimp.org or Homebrew.
* Linking ```<path to GIMP.app>``` in Scribus > Preferences > External Tools > Image Processing Tool

### Scribus Generator 

### Postscript Interpreter

