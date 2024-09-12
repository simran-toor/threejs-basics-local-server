- To run JavaScript code as if it were an online website we need to run a local server 
- to do this use a 'build tool' or a 'bundler' 

BUILD TOOLS 
    - many build tools available:
        - Webpacl, Vite, Gulp, Parce; etc.
    - most popular is webpack:
        - widely used 
        - great community
        - able to do alot with it 
    - best to use is Vite:
        - faster to install 
        - faster to run 
        - less prone to bugs
        - better developer experience 

VITE
    - build tool 
    - once code written (HTML/CSS/JS), Vite will build final website 
    - does other things too like:
        - optimisations 
        - other language support
        - cache breaking
        - source mapping
        - running a local server
        - etc.
    - handles most basic things but can also add plugins for additional features:
        - e.g. more languages, special files 
    - created by Evan You, creator of Vue.js and is highly maintained

NODE.JS
    - enables running JavaScript on computer outside of a browser
    - great to run tools like Vite
    - been used for many years
    - widely used

VITE TEMPLATE 
    - Vite cnfiguration set in 'vite.config.js' file
        - can learn how to configure Vite in docs 
    - can put 'static files' in static/ folder
        - these files served as if they were available in root folder w/o having to write static/
    - can access local server from any other device on the same network by typing same url 
        - useful for debugging on mobile 
        - if not working check firewall 

GET THREE.JS SCENE BACK 
    1. add <canvas> to src/index.html file 
    2. import Three.js at top of /src/script.js
    3. add code from previous exercise into script.js to create box 

