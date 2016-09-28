# Intro

Jordan Sassy is a well known television chef. Off air he runs his own Italian Restaurant. He recently invested in smart, internet connected, menu boards. Because he **LOVES** being the most tech savvy chef in town. 

![](https://67.media.tumblr.com/9824deb84f897ca7e52c13e66f0adba5/tumblr_ne9jfcyNho1qhub34o1_500.gif)

However to his dismay, after failing to read the product description on chefBay; he discovered he had no way to tell the boards what to display! He then hired you to design a React dashboard for them, and needs the MVP from you ASAP. (We wouldn't want him to look bad right?!)

------

###Instructions:

Don't worry about creating and deleting items, for the **MVP** we only need to show him some hard-coded menu items. 

- Go ahead and create a new react project with `create-react-app` like we did in class.  

- And of course attach it to a git repository now, just to be safe! 

-  Now outline what react components you need to make in order to display a menu of various entrees with prices. You can put that in your Readme, or in a comment on `App.jsx`. 

-  Your menu is going to need a bit of elbow grease to get it working. You need to pass the following array as a **prop** of Menu from the state in `App.jsx`. 

```javascript
[
    {
    name:"Pasta Surprise!",
    price: 35
    }
]
```
*Add a few more very Italian items to the menu too!*

-  Now in your menu component take your time to display each item and their price in an unordered list. You don't need to use .map(), you can just access by the array index.  each menu item should be encaspulated in a react component, like `<Item name="Pasta Surprise!" price={35} />`.

-  Rework your code in `Menu.jsx` to utilize the .map() function. This is probably the best thing to learn when it comes to dealing with arrays of objects in your code for dynamic data.

###Bonus!

- Jordan wants a section of the app to show the kitchen what to make as orders come in. Think about what you just made and how that code can be adapted to the new requirement. 

- You'll need to have some way to pass whatever item is clicked to the new Orders list. You wouldn't need to modify the original list. And orders are allowed to have multiples of each item in there. (App is the **brains** of the operation!)
