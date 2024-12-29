#### CREATE AND ACTIVATE A VENV !!!!
### Inside your .venv make sure these are accessible: 

#nodejs
#npm
#npx

#can you --version to check if already installed on your system

#npx create-next-app@latest sfront --typescript

## This creates a next.js app using Typescript inside your venv (this is like an extra layer to React)

#cd sfront
#npm run dev

##### PYTHON #####
flask
flask-cors

### Once installed you simply need to split terminals and run both at the same time! 
## Or you can run both in a seperate threads in a single script 

# Default port run :3000 
# Default port flask: 5000

# Flask-cors allows for communication between the two

### The idea is that you can build front-end and middleware components using NextJS which is convenient and incredible at rendering/routing and even server-sided.
## Practical with tailwind and integrated theming (dark/light)

# You can use javascript workers for more power: rendering, computation, communication... 
# Then pass large computational features to back-end servers with Python. Here your imagination is the limit. Also python supports SQLite natively. 

### Performance wise you can do a lot of things because of this set up and the python back-end responds on sub 40ms average for simple tasks

### For example you could make a live video feed of image recognition using YOLO and then stream it to your front-end in less than 120 lines of code.
## Or do anything for that matter. With a laptop I got 18 fps !
