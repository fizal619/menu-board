# Intro

Jordan Sassy is a well known television chef. Off air he runs his own Italian Restaurant. He recently invested in smart, internet connected, menu boards because he **LOVES** being the most tech savvy chef in town. 

![](https://67.media.tumblr.com/9824deb84f897ca7e52c13e66f0adba5/tumblr_ne9jfcyNho1qhub34o1_500.gif)

However to his dismay, after failing to read the product description on chefBay; he discovered he had no way, app nor web interface, to tell the boards what to display! He then hired you to design a React dashboard for them, and needs the MVP from you ASAP. (We wouldn't want him to look bad right?!)

------

###Instructions:

Don't worry about creating and deleting items, for the **MVP** we only need to show him some hard-coded menu items. 

1. Go ahead and create a new react project with `create-react-app` like we did in class.  

2. And of course attach it to a git repository now, just to be safe! 

3. Now create two files `Header.jsx` and `Menu.jsx`. Make sure to link them to `App.jsx` too. 

4. Now `Header.jsx` is pretty simple. All it should do is return a jsx element with the name of Jordan's restaurant, in a H1 tag. (You get to name it too, be creative!) But the trick is; the **name has to be passed in to Header from the state in `App.jsx`.**

5. `Menu.jsx` is going to need a bit more elbow grease to get it working. You need to pass the following array as a **prop** of Menu from `App.jsx`. 

```javascript
[
    {
    name:"Pasta Surprise!",
    price: 35
    }
]
```
*Add a few more very Italian items to the menu too!*

6. Now in `Menu.jsx` take your time to display each item and their price in an unordered list. You don't need to use .map(), you can just access by the array index.

###Bonus!

7. Rework your code in `Menu.jsx` to utilize the .map() function. This is probably the best thing to learn when it comes to dealing with arrays of objects in your code. 



