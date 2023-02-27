# Docker&React 101 tutorial steps

## list of steps

### Step 1

Setup static „hello world” html page running inside Docker container on your local environment under  <http://local.hello.world>.

### Step 2

Make it run parallel to <http://local.paramountplus.com> (for example use port 81 so our page will be available under <http://local.hello.world:81/>

### Step 3

Set up git repo in your paramount GitHub account for this project. Name: Docker-React-exercises

### Step 4

Create structure for future react app

### Step 5

Move static "hello world" site into "public" folder - we need one root html folder for nginx server
So I chosen to have static page in subfolder of react public.

After completing this step and rebuilding docker one should have:
![react-screenshot][react-screenshot]
![static-site-screenshot][static-site-screenshot]

### step 6

For starting docker app I will use this tutorial:

<https://reactjs.org/docs/create-a-new-react-app.html#create-react-app>

npx create-react-app my-app
than move files form my-app to our project folder.
![react-builded][react-builded]


<!-- MARKDOWN LINKS & IMAGES -->
[react-screenshot]: images/react-index.png
[static-site-screenshot]: images/static-hello-world.png
[react-builded]: images/react-builded.png