# Bookcreator-Starter

**Clone and run for a quick way to see [app.bookcreator.com](http://app.bookcreator.com) in action. Without installing Chrome.**

This is a minimal Electron application based on the [Quick Start Guide](https://electronjs.org/docs/tutorial/quick-start) within the Electron documentation.

## Why is there a unofficial app for bookcreator.com?

Bookcreator is a great tool for students to create digital books in class, but there is one problem: it requires to use the Chrome browser. Why is that a problem? In some schools there is no Chrome Browser installed on the school computer and neither students nor teachers have the permission to install it afterwards. By copying this app to these computers, students will be able to directly access app.bookcreator.com and use this application.

## Which thinks are used?

- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [electron-packager](https://github.com/electron/electron-packager) - a simple way to pack the app into a exe
- mainWindow.maximize() - to maximize the app after startup
- mainWindow.setMenu(null) - to remove default menu
- mainWindow.loadURL('https://app.bookcreator.com') - to start the bookcreator website

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
