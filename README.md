# WebAssemblyHelloWorld
A simple "Hello World" program using C and WebAssembly

# Compile steps

```
emcc hello.c -o hello.html --emrun
emrun --no_browser --port 8080 .
```