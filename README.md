# opengl-cpp-template
Opengl c++ template for vscode IDE

Requirements for this template to work
1.  To run this template you should have g++ C++ compiler and the C/C++ extension for VS Code.
    To setup both, follow this https://code.visualstudio.com/docs/cpp/config-mingw#_prerequisites
2.  Replace libglfw3dll.a and glfw3.dll according to the compiler that you are using. Here I'm
    using the static-ucrt version of glfw3 precompiled binaries. As of the writing of this
    documentation you can get them here https://www.glfw.org/download 
3.  Change the necessary compiler paths to point to your compiler and debugger for the files
    inside the .vscode folder
4.  Run/Run Without Debugging or ctrl + F5
