# Code-Interpreter-LibreChat
This is a simple plug-in for LibreChat which allows to mimic some functions of the ChatGPT Code Interpreter Plugin. 

# How does it work?
- The plug-in will send the python code to a local Python Server.
- The code is executed and any file generated is copied over to the public directory which can be given to the user. 

# Features
- Supports all ChatGPT versions (3.5, 4)
- Can generate graphs etc using Matplotlib.
- Async Code execution.

# 🚀 Installation
- Clone the repo
- Copy the files according to the folder structure. 
    - Add an icon to assets folder named code.png. (not included) 
- Now rebuild the project
```
npm run frontend 
```
- Run the Python Server
```
python3 server.py 
```

# Security
⚠️ This allows to arbitary code execution in your server. 

# Demo

<img src="https://i.ibb.co/8s4vFWS/first.png)" width="500" height="480" />

# To-Do
- [ ] Run the python server in a sandboxed env.
- [ ] Add file upload option.
    





