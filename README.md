# Image Effects App
This app was built using JS and Rust which was transpiled to WebAssembly modules to provide high performance and efficient code execution. It allows you to upload an image and apply a grayscale effect to it.

## Getting Started
To use the app:
``` 
1 - run  npm install to install the node modules  
2 - run  npm run serve  to run the webpack script
3 - open localhost:8080 on the browser of your choice  
4 - simply upload an image and the grayscale effect will be applied to it. 
The new image will be displayed on the page.
```

## How Rust and WebAssembly Make This App Efficient
Rust is a programming language that is designed to provide fast and efficient code execution, making it a great choice for building web applications that require high performance. By using Rust to build the app, we are able to take advantage of its memory safety features and compile the code to WebAssembly modules.

WebAssembly is a low-level virtual machine that provides a portable, efficient, and secure way to execute code in web browsers. By compiling Rust code to WebAssembly modules, we can take advantage of the performance benefits of Rust while still being able to run the app in any modern web browser.

Overall, the combination of Rust and WebAssembly allows us to build high-performance web applications that can handle complex computations, such as image processing, with ease.
