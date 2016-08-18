# virtualkeyboard-demo
### Repackaging of Qt 5.7 basic virtualkeyboard example
#### To use this as a template for snapping your Qt 5.7 app, please follow steps below
* Compile your code with Qt 5.7 to get a binary.
* Put all the required Qt 5.7 libraries in "lib" folder
* Put all the required Qt 5.7 plugins in "plugins" folder
* Put all the required Qt 5.7 qml modules in "qml" folder
* Custom plugin "qt57" script is located in "parts/plugins/x-qt57.py"
* Put above 1-5 together so your working directory will look like this:
<br />VirtualKeyboard-demo
<br />├── basic             <-- Binary
<br />├── lib               <-- lib directory
<br />├── parts 
<br />│   └── plugins
<br />│       └── x-qt57.py <-- custom plugin qt57
<br />├── plugins           <-- Qt5.7 plugins directory
<br />├── qml               <-- Qt5.7 QML modules directory
<br />└── snapcraft.yaml    
<br /> 
* Snap it: "snapcraft snap" creates "virtualkeyboard-demo_0.1_amd64.snap"
* Install it: "sudo snap install virtualkeyboard-demo_0.1_amd64.snap"
* Run it: "virtualkeyboard-demo.basic"

