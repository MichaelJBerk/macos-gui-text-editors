# GUI Text Editors for macOS

I've compiled a list of general-purpose<sup>[1](#1)</sup> GUI text editors/IDEs for macOS. I've spent some amount of time playing around with each of these<sup>[2](#1)</sup> to get an idea for what they offer.
If you have an other ideas/suggestions, please open a PR and suggest them.

- [Sublime Text 3](https://www.sublimetext.com)
    - Free, but nags you every now and again if you don't pay $80
    - Cross-Platform (Windows, macOS, Linux)
    - Lots of packages available
    - IMO, Default color palette practically screams at you, making it very easy to read
- [Visual Studio Code](https://code.visualstudio.com)
    - Free
    - Fits somewhere between a proper IDE and a text editor
    - Cross Platform (Windows, macOS, Linux)
    - [Open Source](https://github.com/microsoft/vscode)
    - Easy to install browse and extensions for different languages
    - Non-native UI can get quite sluggish at times
        - Under-the-hood, it's technically just a browser in disguise.
- [TextMate](https://macromates.com)
    - Free
    - Extensible using TextMate Bundles
    - Autocomplete is more limited 
        - If you typed a word previously in a file, it'll appear in autocomplete
        - Otherwise, there's keyboard shortcuts for common statements
            - i.e. in java, typing `p` and pressing tab will write 
        `System.out.println();`
- [CotEditor](https://coteditor.com)
    - [Free](https://itunes.apple.com/app/coteditor/id1024640650?ls=1)
    - [Open Source](https://github.com/coteditor/CotEditor)
    - Similar to TextMate, autocomplete is limited
- [CodeRunner3](coderunnerapp.com)
    - $14.99, either through [coderunnerapp.com](coderunnerapp.com) or [Mac App Store](https://apps.apple.com/us/app/coderunner-3/id955297617?ls=1&mt=12)
        - 14-day free trial
        - Also available through [Setapp](https://go.setapp.com/stp56?refAppID=122&stc=website&utm_medium=available_on_setapp_button&utm_source=122&utm_campaign=https://coderunnerapp.com/)
    - *Very* robust autocomplete and documentation 
    - Great for beginners
        - Very easy to run code within the app without having to go to the command line
    - Not very extensible
    - Does not offer a CLI extension
- [BBEdit](https://www.barebones.com/products/bbedit/)
    - Offers a subset of features for free, with a 14-day trial for the full version
    - $50 for the latest major release from [Barebones.com](barebones.com), or as a subscription from the App Store
        - Access to the major version without paying extra to upgrade
        - $40 a year, or $4 a month
    - Been around since approximately the dawn of time (more or less)
    - Best at conforming to MacOS' look and feel (IMO)
    - Can be extended through scripts, etc.
    - Lots of features relating to text manipulation, regex, etc.
    
Other text editors of note that I haven't tried:
- [Atom](https://atom.io)
    - Free
    - Developed by GitHub
    - Like VSCode, it's based off of Electron, so it's a browser in disguise 
- [Brackets](http://brackets.io)
    - Free
    - Developed by Adobe

<a name="1">[1]</a>: Read: not designed for one language or another. This excludes apps like Xcode or IntelliJ, which aren't too useful outside of developing for Apple platforms or Java, respectively

<a name="2">[2]</a>: I have either downloaded and used the app (if free) or tested the free trial (if paid)
