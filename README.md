# bizdevsunday


#Bizdevsunday - Getting to know CosmicJS

I created this page to play with react and a relatively new cms platform called CosmicJS


![alt tag](./preview/bizdevsunday.com-web.png)
![alt tag](./preview/bizdevsunday.com-(iPhone 6 Plus).png)
![alt tag](./preview/cosmicjs-dashboard.png)
![alt tag](./preview/cosmicjs-usage.png)

#Cross-Platform Blog
![alt tag](https://cosmicjs.com/uploads/21e23d30-8076-11e6-a994-973764f7d6d1-cross-platform-blog.jpg)
This repo is an example of how to build cross-platform apps with content powered by [Cosmic JS](https://cosmicjs.com). The iOS and Android apps in this repo are built using React Native and the web app runs on a light Node.js web server, all with content served from the [Cosmic JS CMS API](https://cosmicjs.com).  Create your content once, deliver everywhere.
###Features
1. Native iOS and Android apps share the same React Native codebase.  Learn once, write anywhere<sup>TM</sup>.
2. Web is fully responsive down to mobile w/ [Bootstrap](http://getbootstrap.com) frontend.<br />
3. Images are easily manipulated for different device / browser requirements via the Cosmic JS provided [Imgix](https://www.imgix.com/) integration.

Sign up for [Cosmic JS](https://cosmicjs.com) to install the app, add / edit content and deploy the web app.

** Before trying to run any of the examples, make sure you are connecting to the example bucket `cross-platform-blog` or have imported the bucket.json in the root of this repo to your own bucket in Cosmic JS.
##Web
[View the web demo here](https://cosmicjs.com/apps/cross-platform-blog/demo)
###Get started with web
```
git clone https://github.com/cosmicjs/cross-platform-blog
cd cross-platform-blog/web
npm install
```
###Run web in development
```
npm run development
```
Go to [http://localhost:5000](http://localhost:5000).
###Run web in production
```
COSMIC_BUCKET=your-bucket-slug npm start
```
Go to [http://localhost:3000](http://localhost:3000).
##Native
If you are new to React Native, make sure you check out the [React Native docs](https://facebook.github.io/react-native/) to make sure you have everything set up properly.
###Get started with native
```
cd cross-platform-blog/native
npm install
```
###Config
Edit native/config.js to point to your bucket slug on Cosmic JS.
```
export default {
  COSMIC_BUCKET: 'your-bucket-slug'
}
```
###Run iOS
Run the iOS command inside the native folder:
```
react-native run-ios
```
###Run Android
Run the Android command inside the native folder:
```
react-native run-android
```
##Questions
For any questions, feel free to reach out to us on the [Cosmic JS website](https://cosmicjs.com/) through the Intercom chat bubble on the bottom right side of the page.  Or join the [Cosmic JS Community on Slack](https://cosmicjs.com/community).
