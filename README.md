# Project Description

TextMate Bundle for writing YARD style documentation for ruby scripts

## Snippets

  * ##      - Starts documentation
  * option  - @option
  * param   - @param
  * since   - @since
  * version - @version
  * author  - @author
  * see     - @see
  * raise   - @raise
  * yparam  - @yieldparam
  * yield   - @yield
  * return  - @return
  * depr    - @deprecated
  
Installation
============

To install via Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git@github.com:Bodacious/yard-tmbundle.git "Yard.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

Source can be viewed or forked via GitHub: [https://github.com/Bodacious/yard-tmbundle](https://github.com/Bodacious/yard-tmbundle)

### TODO

  * A tmLanguage
  * A tmCommand for regenerating the documentation and opening it in the browser
  