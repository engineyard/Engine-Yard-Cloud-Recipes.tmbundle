# TextMate bundle for Engine Yard Cloud Recipes

This TextMate bundle make it very easy to write recipes for EY Cloud's Recipe system, which is based off Chef.

## Usage

First, create the scaffold of your EY Cloud Recipe using the [ey-recipes](https://github.com/engineyard/engineyard-recipes) tool.

Within a recipe file (such as `default.rb`), change from the Ruby language to "EY Cloud Recipes"

<img src="https://img.skitch.com/20111116-r11u5gfgmjf75us7aj2m53fx8s.png" alt="Change grammar" />

There are many snippets available and a couple of nice drag & drop features. Press 
`Ctrl+Cmd+T` to see the available list and the corresponding tab completion.

<img src="https://img.skitch.com/20111116-dj5jun2uw3s9ca6ugrg18hhhbw.png" alt="Select Bundle Item" />

Or get more information from the Bundle Editor.

<img src="https://img.skitch.com/20111116-xdn9n1u7hihfp1k17jq7hq75aa.png" alt="Bundle Editor" />


## Installation

To install via Git:

		mkdir -p ~/Library/Application\ Support/TextMate/Bundles
		cd ~/Library/Application\ Support/TextMate/Bundles
		git clone git@github.com:engineyard/Engine-Yard-Cloud-Recipes.tmbundle.git "Engine Yard Cloud Recipes.tmbundle"
		osascript -e 'tell app "TextMate" to reload bundles'

Source can be viewed or forked via GitHub: [http://github.com/engineyard/Engine-Yard-Cloud-Recipes.tmbundle.tmbundle](http://github.com/engineyard/Engine-Yard-Cloud-Recipes.tmbundle.tmbundle)

## License

(The MIT License)

Copyright (c) 2011 Engine Yard, LLC

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.