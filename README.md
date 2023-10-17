# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)



 oc new-app https://github.com/rndudhe1808/reactjsapp.git --strategy docker
   48  oc get route
   49  oc get pods
   50  oc get pods -w
   51  oc get pods -w
   52  oc get route
   53  oc get pods -w
   54  oc get svc
   55  oc get pods -w
   56  oc expose pod reactjsapp-1-build --port=3000
   57  oc get svc
   58  oc expose svc reactjsapp-1-build
   59  oc get route
   60  oc get pods -w
   61  oc get deployment
   62  oc delete svc reactjsapp-1-build
   63  oc delete route reactjsapp-1-build
   64  oc expose deployment  reactjsapp
   65  oc expose deployment  reactjsapp --port=3000
   66  oc expose svc reactjsapp
   67  oc get route
   68  history

   vi Dockerfile
   14  docker build -t reactjs -f Dockerfile.
   15  docker build -t reactjs 
   16  docker build -t reactjs .
   17  docker images
   18  docekr run -p 3000:30000 -itd reactjs 
   19  docker run -p 3000:30000 -itd reactjs 
   20  docker ps
   21  docker run -p 3000:3000 -itd reactjs 
   22  docker ps 
   23  docker rm -f 93b2d9497669
   24  docker run -p 4000:3000 -itd reactjs 
   25  docekr ps
   26  docker ps
   27  ssh-keygen
   28  ls
   29  cd /.root/ssh
   30  cd /root/.ssh
   31  ls
   32  cat id_rsa.pub 
   33  git clone git@github.com:rndudhe1808/reactjsapp.git
   34  pwd
   35  cd /
   36  ls
   37  cd /home/
   38  ls
   39  cd ..
   40  ls
   41  cd ..
   42  ls
   43  cd /root
   44  ls
   45  cd node-v18.18.0-linux-x64/
   46  ls
   47  cd hello/
   48  ls
   49  cd ..
   50  ls
   51  cd /root/.ssh
   52  ls
   53  mv reactjsapp  /root
   54  cd /root
   55  ls
   56  cd node-v18.18.0-linux-x64/hello/
   57  ls
   58  cp -rvf * /root/reactjsapp/
   59  ls
   60  cd /root/reactjsapp/
   61  ls
   62  git add .
   63  git commit -m "test"
   64  git config --global user.email "you@example.com"
   65  git config --global user.name "Your Name"
   66  git commit -m "test"
   67  git push
