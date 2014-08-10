#PlayNow.app

Are you tired of having to think of directories and names for your throwaway playground files? PlayNow is here solve all your problems!

<img src="https://raw.githubusercontent.com/apalancat/PlayNow/gh/icon_512x512.png" width="256" title="It has an icon!"/>

## Installation

Best way to install is using curl so it bypasses Gatekeeper (Thanks [mxcl](https://twitter.com/mxcl) for the [tip](https://coderwall.com/p/ki0jxw?i=2&p=1&q=author%3Amxcl&t[]=mxcl)!):

    cd /Applications && curl -L https://github.com/apalancat/PlayNow/releases/download/v0.2/PlayNow.tgz | tar x

You can also [download it](https://github.com/apalancat/PlayNow/releases/latest) and Control-click to have Gatekeeper give you the option to open it.

## Configuration

PlayNow creates an OS X playground by default.
If you prefer iOS playgrounds you can open the file `PlayNow.app/Contents/MacOS/PlayNow` with your favorite text editor and change `platform = "macosx"` to `platform = "iphonesimulator"` (non-favorite text editors could also work).

## How to use it?

1. Open the app with your favorite App Launcher (or manually)
2. It creates a new Playground in /tmp
3. The Playground opens automatically in Xcode
4. ??
5. Profit

![Dock](https://raw.githubusercontent.com/apalancat/PlayNow/gh/Dock.png "Looks great on your Dock!")

## What is it?

It's just a simple ruby script wrapped in an app that creates empty Swift playground files in your /tmp directory and opens them with Xcode. The script itself is [here](https://github.com/apalancat/PlayNow/blob/master/app/PlayNow.app/Contents/MacOS/PlayNow).
