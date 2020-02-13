# How To Minify CSS Files

### 1. Use 'clean-css-online' Service.
 - Click [here](http://adam.id.au/clean-css-online/) to use 'clean-css-online'.


### 2. Install and Use 'JS CSS Minifier' inside of Bracket.
![bracket_minifier](../image/bracket_minifier.png)


### 3. Install and Use 'clean-css-cli' in Mac Terminal.
 - Install clean-css and clean-css-cli with npm.
 
`sudo npm install -g clean-css`

`sudo npm install -g clean-css-cli`

 - Use command 'cleancss' to minify css files.

`cleancss -o original_file.min.css original_file.css`

 - Use command 'cat' to see the content of minified files.

`cat original_file.min.css`

