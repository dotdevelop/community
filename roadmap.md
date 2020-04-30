# Roadmap

## Get to compile

First task is to get it to compile again without closed-source dependencies, as eveything is cluttered with Cocoa/MacOS code.

## Provide substitution for [Visual Studio Editor API](https://github.com/microsoft/vs-editor-api)

As `vs-editor-api` is deeply integrated in the code, provide an implementation based on Xwt/Gtk.

- In the first step, this is not intended to be a working `vs-editor-api`. It's just here to get MD compiling.
- In a second step, there should be a discussion what concrete GUI framework will be choosen as base for `vs-editor-api`.
