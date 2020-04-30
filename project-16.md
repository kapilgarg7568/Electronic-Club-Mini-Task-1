Kids Photo Album with Flashcard:-->
it is a simple iot based project that can auto download latest photos and at the same it will show some random flashcard which will help children to learn new things.
we will use NODE.js http server with sharp library which simply drag the new phototo photo folder, it auto resize and crop the image on the fly and then serve to the IoT device.
We have to write a code to setup photo server to meet this requirement and we can also set the ratio of photo to flashcards like after these many photos one flashcard will pop up on the screen.
The ESP32 module have 4 MB flash storage, around 3 MB space can be used to store the photos. For 320x240 JPEG files, it is around 100 - 200 pieces. It is good enough in most case.

ESP32 module:ESP32 is a low-cost system-on-chip (SoC) series created by Espressif Systems. It is an improvement on the popular ESP8266 that is widely used in IoT projects. The ESP32 has both Wi-Fi and Bluetooth capabilities, which make it an all-rounded chip for the development of IoT projects and embedded systems in general.

Node.js: it is an open source, cross-platform runtime environment for developing server-side and networking applications. Node.js applications are written in JavaScript, and can be run within the Node.js runtime on OS X, Microsoft Windows, and Linux. Node.js also provides a rich library of various JavaScript modules which simplifies the development of web applications using Node.js to a great extent.Node. js is primarily used for non-blocking, event-driven servers, due to its single-threaded nature.
Node.js has a built-in module called HTTP, which allows Node.js to transfer data over the Hyper Text Transfer Protocol (HTTP).
