# Intent and Intent Filters app

* You can think of an intent like an envelope which is used to transfer an intention of your app that is what's called intent and transfer that to a different android component (for eg Activity, Services etc)
* There are 2 type of intent 
  * Explicit Intent
    * Here we specify which component of which application will satisfy the intent, by specifying a full ComponentName.
    * You will typically use an explicit intent to start a component in your own app or if you know the exact package name that you want to start.
    * Like in this repo we did.
    * Checkout this branch [explicit-intent-examples](https://github.com/ratneshnavlakhe/IntentAndIntentFilters/tree/explicit-intent-examples)
  * Implicit Intent
    * Here we do not name the specific component, but instead declare a general action to perform, which allows a component from another app to handle it.
    * For example, in this repo we did check the first commit of branch [implicit-intent-examples](https://github.com/ratneshnavlakhe/IntentAndIntentFilters/commit/0d599ab872a83b91141c58f4a64c89222b317dfc)
    * Here we tried to send an email intent to another app like gmail app.

# How do other app receive and intent
* There might be a usecase were we want our app to receive an intent.
* We can do so by registering our app in AndroidManifest.xml check line no. 26
* For this example check this branch [implicit-intent-examples](https://github.com/ratneshnavlakhe/IntentAndIntentFilters/commit/6465896b576748774fb423d1f449335d11b699e7)

# Videos

https://github.com/ratneshnavlakhe/IntentAndIntentFilters/assets/4018792/6d3d6e95-7041-411b-97fe-1c1114bc1c2b

