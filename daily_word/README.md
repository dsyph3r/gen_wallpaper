# README

Generates a desktop background. 2 methods are currently available:

 * Random word + definition (using wordnet).
 * Urban Dictionary word of the day

## Prerequisites
Packages needed, these are the packages names on ubuntu different distros may differ:

 * wordnet
 * wordnet-base
 * wbritish
 * librmagick-ruby

Fedora specific:

 * wordnet-base is not required
 * "wbritish" package is replaced with "word" package
 
It also expects `Candice.ttf` in `resources/fonts/` unsure aboout the licence at the mo but you can download from <http://www.font-zone.com/download.php?fid=523>

## Usage
ruby daily_word.rb [wordnet|urban]

## Todo

 * Split into bin/lib
 * Added commandline options for:
   - Size
   - Colours
   - Output file location
  
## Example
![daily_word!](http://github.com/orangemug/gen_wallpaper/raw/master/daily_word/examples/unicorn_cropped.png)
