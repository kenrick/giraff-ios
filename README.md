# Giraff

## One Tap Curated Gifs

This is a product being built by the Assembly community. You can help push this idea forward by visiting [https://assembly.com/giraff](https://assembly.com/giraff).


### Getting started

Requires the current Xcode version.

To get started download Xcode from from [here](https://developer.apple.com/xcode/downloads/).

Before opening the project, run cocoapods.

Cocoapods can be installed from the command-line with:
```
gem install cocoapods
```

[More info on Cocoapods.](https://developer.apple.com/xcode/downloads/)

After installing CocoaPods, clone the source repository.
On the commandline CD into the directory containing the Podfile.
```
cd Giraff
```

Then run:
```
pod install
```

You should see a message indicating the fact that things were installed successfully and that you should use the workspace file.

Next up is setting up Parse. There are four things you need to do.

- Setup your own parse.com account.
- Create a new application.
- Copy the file ./bin/setEnv-example.sh to setEnv.sh and paste your Parse.com keys in there.
- Now CD to ./Giraff/parse/config and run ```./genGlobalJson.sh```

You should now have your parse.com configured.

Open the workspace file from the commandline with or open using the Finder.
```
open Giraff.xcworkspace
```

Build and run... Happy coding.

If you encounter a build error, try cleaning your project.

```
Xcode -> Window -> Organizer -> Projects, select your project, and press the "Delete..." button next to "Derived data".

If this doesn't work, try Product->Clean (Cmd+Shift+k).
```

### How Assembly Works

Assembly products are like open-source and made with contributions from the community. Assembly handles the boring stuff like hosting, support, financing, legal, etc. Once the product launches we collect the revenue and split the profits amongst the contributors.

Visit [https://assembly.com](https://assembly.com) to learn more.
