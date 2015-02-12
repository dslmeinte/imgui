# libimgui

 “The GUI as stdout”

 “Structure of the code == structure of the GUI”

`libimgui` is a simple, tiny library for programming immediate mode GUIs in the browser.
A `libimgui` app is a straight-line program that (conceptually) just “writes” out the GUI to the screen.
Ordinary functions can be used to build reusable component abstractions.
Components may have local (view) state which is automatically restored upon re-rendering. 


## Building

`libimgui` uses NPM and `browserify`.
Perform the following actions in your favourite shell:

```
[sudo] npm install -g browserify
git clone https://github.com/dslmeinte/imgui.git
cd imgui/libimgui
npm install
cd ../examples
browserify examples.js -o bundle.js
```

After this you should be able to "run" `examples/index.html`.

