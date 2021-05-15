# prefix-dictionary

Boggle dictionary wrapper

Provides quick lookup of words based on Boggle/Scrabble dictionary

# usage

you must init dictionary by calling

  var dic = require('prefix-dictionary');
  dic.initDictionary();

you can also use your own dictionary file ( french for example)

  var dic = require('prefix-dictionary');
  dic.initDictionary(path.join( _ _ dirname, 'osd8.txt'););

### lower-case words only!
