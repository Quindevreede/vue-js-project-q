# vue-js-project-q

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
/* 
VUE.JS

💻 Code - Static: ✏️ Course developed by Gwen Faraday. Check out her channel: https://www.youtube.com/c/FaradayAcademy
⭐️ Course Contents ⭐️
01 - ⌨️ (0:00:00) Introduction
02 - ⌨️ (0:01:03) What is Vue.js?
03 - ⌨️ (0:05:40) Vue 3 Setup
04 - ⌨️ (0:12:17) Vue JS Directives
05 - ⌨️ (0:19:48) Events and Methods
06 - ⌨️ (1:29:20) Components
07 - ⌨️ (0:39:27) Component Props
08 - ⌨️ (1:06:09) Lifecycle Hooks
10 - ⌨️ (1:14:30) App Demo
11 - ⌨️ (1:26:45) Adding Items to Cart
12 - ⌨️ (2:15:54) Reuseable Components
13 - ⌨️ (2:26:20) Vue CLI
14 - ⌨️ (2:32:48) Vue Folder Structure
15 - ⌨️ (2:43:58) Top Nav
16 - ⌨️ (2:48:45) Styling with SASS
17 - ⌨️ (3:06:07) Sidebar
18 - ⌨️ (3:20:46) Adding Items to Cart

------------------------------------------------------------------------------------------

01 - ⌨️ (0:00:00) Introduction

Vue is a Javascript FRAMEWORK for building applications and websites.

02 - ⌨️ (0:01:03) What is Vue.js?

It provides tools out of the box to make your apps/sites faster and more dynamic and also gives you a set of standards for code organisation that
all coders can follow.

HOW VUE CAN HELP:
- Create Dynamic Applications
- Tools for Code Organization
- Speed of Development
- Developer Tools
- Helps with Scaling
  --- Features & Benefits ---
  • Virtual DOM Framework
  • Lightweight (10k gzip)
  • Progressive
  • Flexible (you can also use other tools in the code)
  • Incrementally adoptable

03 - ⌨️ (0:05:40) Vue 3 Setup
https://v HYPERLINK "https://v HYPERLINK "https://v HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v HYPERLINK "https://v3.vuejs.org/"3 HYPERLINK "https://v3.vuejs.org/".vuejs.org/" HYPERLINK "https://v3.vuejs.org/" HYPERLINK "https://v3.vuejs.org/".vuejs.org/
INSTALLATION GUIDE, WE JUST USE WEBSTORM

04 - ⌨️ (0:12:17) Vue JS Directives

01 - Use function with a return string
02 - Use a v-model on the {{greeting}} so you can type a new text to
replace the current greeting
03 - Use v-if to make an IF STATEMENT to show box on TRUE
04 - Use v-else-if, Use v-else
```<div id="tutorial-one" v-cloak>
  {{greeting}}
  <input v-model="greeting" />
  <hr />
  <div class="tutorial-box1" v-if="isVisible1"></div>
  <div class="tutorial-box2" v-else-if="isVisible2"></div>
  <div class="tutorial-box3" v-else></div>
  <hr>
</div>
<script>
export default {
  name: 'HelloWorld',
  data: function () {
    return {
      greeting: "Type Something",
      isVisible1: false,
      isVisible2: false,
    };
  },
  props: {
    msg: String
  }
}
</script>
.tutorial-box1 {
  background-color: mediumseagreen;
  height: 100px;
  width: 100px;
}
.tutorial-box2 {
  background-color: greenyellow;
  height: 100px;
  width: 100px;
}
.tutorial-box3 {
  background-color: darkslategray;
  height: 100px;
  width: 100px;
}
[v-cloak] {
  display: none;
}
</style> ```
```
05 - ⌨️ (0:19:48) Events and Methods
```<div id="tutorial-one" v-cloak>
  {{greeting}}
  <h4>TEXT PARROT</h4>
  <p>text input will be duplicated above</p>
  <input @keyup.enter="greet(greeting + '!!!')" v-model="greeting" placeholder="type something..."/>
  <hr />
  <button @click="toggleBox">Toggle Box</button>
  <div class="tutorial-box" v-if="isVisible"></div>
  <hr>
</div>
<script>
export default {
  name: 'HelloWorld',
  data: function () {
    return {
      greeting: "",
      isVisible: false,
    };
  },
  methods: {
    toggleBox() {
      this.isVisible = !this.isVisible
      // Met this. kun je bij de isVisible: false
    },
    greet(greeting) {
      console.log(greeting);
    }
  },
  props: {
    msg: String
  }
}
</script>
```

We made TWO METHODS here:
- one method for mouse-click event listener
- one method for keyboard-enter event listener

06 - ⌨️ (1:29:20) Components
07 - ⌨️ (0:39:27) Component Props


The red rectangles indicate the COMPONENTS that we are going to build.
So we'll make the following components:
- <login-form />
- <custom-input />
- <custom-input />

I got stuck here because I did everything in .vue files and had to translate them from html and eventually put everything in quin-first-project so check that project for codes and components.

08 - ⌨️ (1:06:09) Lifecycle Hooks
I tried to translate to .vue file but all i got was the created/mount/updated so didnt get the unmount.
But we already know this stuff from React so just watch the video and the code is in
C:\Documents Q\Programmeren 2022\FRONTEND\VUE JS\Git for Tutorial\Starterscourse Code\vue3-fcc-course-static-code-main
10 - ⌨️ (1:14:30) App Demo

Chapter 9 doesn't exist for some reason. We'll continue to set up a Basic App. I've decided to play ball and start this project in HTML, Eventually we'll go back to .vue files but we'll be workong with HTML files for now.

C:\Documents Q\Programmeren 2022\FRONTEND\VUE JS\basic-app-q
This is where the project is located and I will be adding through branches on GitHub. The moment we'll be using the .vue files I will make a new project : advanced-project-q but we'll get to that in a later chapter.

---

We've cloned the basic page with html and css already in place. What we'll be doing is add logic and functions/methods so the user can have interactivity with the site:

001 - ADD TO CART

We want to be able to add products to our cart, first we need to be able to use Vue so paste this line just above the </body></html> tags:
<script src="https://unpkg.com/vue@next"></script>
<script>
  let app = Vue.createApp( {
    data () {
      return {
        inventory : {
          carrots: 0,
          pineapples: 0,
          cherries: 0
        }
      }
    }
  });
  app.mount('#app');
</script>
So we are good to go I'll create an inventory.

    inventory: {
      carrots: 0,
      pineapples: 0,
      cherries: 0
    },
    cart: {
      carrots: 0,
      pineapples: 0,
      cherries: 0
    }
}
},
methods: {
addToCart(type) {
this.cart[type] += this.inventory[type]
console.log(this.cart)
}
}
And be sure to use v-model.number on carrots so you dont get a string:
<input type="number" v-model.number="inventory.carrots">
Now you can add Carrots and in the CONSOLE they will add up.

11 - ⌨️ (1:26:45) Adding Items to Cart

First we'll Paste the following in an app.component in our app.html:
<aside class="cart-container">
  <div class="cart">
    <h1 class="cart-title spread">
      <span>
        Cart
        <i class="icofont-cart-alt icofont-1x"></i>
      </span>
      <button class="cart-close">&times;</button>
    </h1>

    <div class="cart-body">
      <table class="cart-table">
        <thead>
          <tr>
            <th><span class="sr-only">Product Image</span></th>
            <th>Product</th>
            <th>Price</th>
            <th>Qty</th>
            <th>Total</th>
            <th><span class="sr-only">Actions</span></th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><i class="icofont-carrot icofont-3x"></i></td>
            <td>Carrot</td>
            <td>$1.00</td>
            <td class="center">1</td>
            <td>$1.00</td>
            <td class="center">
              <button class="btn btn-light cart-remove">
                &times;
              </button>
            </td>
          </tr>
        </tbody>
      </table>

      <p class="center"><em>No items in cart</em></p>
      <div class="spread">
        <span><strong>Total:</strong> $1.00</span>
        <button class="btn btn-light">Checkout</button>
      </div>
    </div>
  </div>
</aside>
In data() return:
showSidebar: false,

In Element area:
<sidebar
v-if="showSidebar"
:toggle="toggleSidebar"
:cart="cart"
/>
in Methods:

toggleSidebar() {
this.showSidebar = !this.showSidebar
}
In Element Area:
<a @click="toggleSidebar" class="top-bar-cart-link">
<i class="icofont-cart-alt icofont-1x"></i>
<span>Cart (0)</span>
</a>
In imported Element Component:

<button @click="toggle" class="cart-close">&times;</button>

You named it "toggle" for this area , but it will access toogleSidebar because next in <sidebar /> we'll  :toggle="toggleSidebar"
You dont have SCOPE to access it so pass it in <sidebar />:

<sidebar
v-if="showSidebar"
:toggle="toggleSidebar"
:cart="cart"
/>

Dont forget the ":" or it will look for a STRING
And add it as a PROP in app.component ('sidebar') :

app.component('sidebar', {
props: ['toggle', 'cart'],

So now you can toggle sidebar on/off
----

NOW we WANT OUR PRODUCT IN CART TO BE DYNAMIC
For now we just have carrots so we'll be working with those for now.

You've added the CART in your component:
<sidebar
v-if="showSidebar"
:toggle="toggleSidebar"
:cart="cart"
/>
Now also add it to your PROPS:
app.component('sidebar', {
props: ['toggle', 'cart'],
And now you can access this object and for now we'll go to the app.component of our Cart element and add just the carrots with {{  }}:
<tbody>
<tr>
  <td><i class="icofont-carrot icofont-3x"></i></td>
  <td>Carrot</td>
  <td>$4.82</td>
  <td class="center">{{ cart.carrots }}</td>
  <td>\${{ cart.carrots * 4.82 }}</td>
  <td class="center">
    <button class="btn btn-light cart-remove">
      &times;
    </button>
  </td>
</tr>
</tbody>
Turns out you can't throw around $ signs so use /$ so you won't error
ALSO fix the TOTAL price, we'll go to the app.component of our Cart :
<div class="spread">
  <span><strong>Total:</strong> \${{ cartTotal }}</span>
  <button class="btn btn-light">Checkout</button>
</div>
AND ADD A COMPUTED to the COMPONENT:
computed: {
  cartTotal() {
    return (this.cart.carrots * 4.82).toFixed(2)
  }
So for now(only carrots) we have a way to get the total price of carrots
(COMPUTED watches the changes in variables and updates the result)
.toFixed(2) will give it two decimals

----------------------------------------------------------------------------------
IMPORTANT NOTE:

We have switched programming a bit by using an app.js file where we have put all our methods, computed and props. There is also a template for the side-bar-cart because that component needs to be available all the time. You'll notice that this is less cluttered. Just remember that if you need JAVASCRIPT stuff or the side-bar-cart to go to the .js file.

----------------------------------------------------------------------------------
11.5 - ⌨️ (1:43:22) DYNAMIC CONTENT
We are going to get data from our food.json file with LIFE-CYCLE-HOOKS
async mounted() {
const res = await fetch('./food.json')
const data = await res.json()
this.inventory = data
}
- remember the async and await so this data won't be empty
- const res (short for response) gets the data that we put in a variable
  that we'll put in the inventory (you can delete the dummy data (carrots,
  ect.) and just put inventory: []

We will take out our carrots and make this dynamic content
- So you can delete stuff in app.html. the pineapples and the other one
  can be deleted so you just have the html elements for the carrots.
- Now you just have the html product element for the carrot
- Delete the carrot parts in these elements and make them dynamic
  so they can be used for all our products:
<div v-for="(product, i) in inventory.slice(0,3)" :key="product.id" class="card">
  <div class="card-title">
    {{ product.name }}
  </div>
  <div class="card-body">
    <i class="icofont-10x icofont-{{ product.icon }}"></i>
    <form>
      <div class="row">
        <div class="cell">
          <label>Type:</label>
        </div>
        <div class="cell">
          <em>{{ product.type }}</em>
        </div>
      </div>
      <div class="row">
        <div class="cell">
          <label>Price:</label>
        </div>
        <div class="cell">
          ${{ product.price.USD }}
        </div>
      </div>
      <div class="row">
        <div class="cell">
          <label>Quantity:</label>
        </div>
        <div class="cell">
          <input type="number" v-model.number="product.quantity">
        </div>
      </div>
    </form>
  </div>
  <div class="card-footer">
    <button @click="addToCart(product.name, i)" class="btn btn-light">
      Add to cart
    </button>
  </div>
</div>
We will loop through them and slice them so we'll only see 3 on the page
```<div v-for="(product, i) in inventory.slice(0,3)" :key="product.id" class="card"> </div>
```
We will access the id key and make sure we'll get the right content through id key
```<div v-for="(product, i) in inventory.slice(0,3)" :key="product.id" class="card"> </div>
```
We will also pass the index in inventory and add quantity 
<input type="number" v-model.number="product.quantity">

We will also make the addToCart dynamic:
<div class="card-footer">
  <button @click="addToCart(product.name, i)" class="btn btn-light">
    Add to cart
  </button>
</div>
--- 

We will set up the cart now and make it dynamic, REMEMBER THAT we put all our JAVASCRIPT in app.js:
let app = Vue.createApp({
data() {
return {
showSidebar: false,
inventory: [],
cart: {}
}
},
computed: {
totalQuantity() {
return Object.values(this.cart).reduce((acc, curr) => {
return acc + curr
}, 0)
}
},
methods: {
addToCart(name, index) {
if (!this.cart[name]) this.cart[name] = 0
this.cart[name] += this.inventory[index].quantity
this.inventory[index].quantity = 0
},
toggleSidebar() {
this.showSidebar = !this.showSidebar
},
removeItem(name) {
delete this.cart[name]
}
}
We will pass the index of the item in addToCart() method
methods: {
addToCart(name, index)
- IF there is not(!) a name in the cart, cart will be empty(0)
- IF there is a name in cart PUT the quantity that is passed on that name
  in the cart
- default value for the quantity is 0, so at the start your cart will be empty

We will be making the side-bar-cart dynamic as well and REMEMBER that we put that component in app.js:

First lets make sure the sidebarCart can receive the inventory of the .cart so we can get price, ect. in app.html:
<sidebar
v-if="showSidebar"
:toggle="toggleSidebar"
:cart="cart"
:inventory="inventory"
:remove="removeItem"
/>

then add this inventory as a prop in the component (thats in in app.js)
app.component('sidebar', {
props: ['toggle', 'cart', 'inventory', 'remove'],

We will be looping through each item in the cart:
<tbody>
  <tr v-for="(quantity, key, i) in cart" :key="i">
    <td><i class="icofont-carrot icofont-3x"></i></td>
    <td>{{ key }}</td> //Name
    <td>\${{ getPrice(key) }}</td> //Price
    <td class="center">{{ quantity }}</td> //Quantity
    <td>\${{ quantity * getPrice(key) }}</td> //TotalPrice
    <td class="center">
      <button @click="remove(key)" class="btn btn-light cart-remove">
        &times;
      </button>
    </td>
  </tr>
</tbody>
Also we will make methods for the sidebar cart to get/find the price:
app.component('sidebar', {
  props: ['toggle', 'cart', 'inventory', 'remove'],
  methods: {
    getPrice(name) {
      const product = this.inventory.find((p) => {
        return p.name === name
      })
      return product.price.USD
    },
So in the function getPrice() we give as prop NAME and we are looping through our inventory until we find the product with the name that we want this function for. When we do (p.name === name) RETURN the price of this product in USD (us dollars)
this.inventory.find((p) is called that way because we dont want to call it product again. (const product)

Now let's make a function for the TOTAL PRICE:
calculateTotal() {
const total = Object.entries(this.cart).reduce((acc, curr, index) => {
return acc + (curr[1] * this.getPrice(curr[0]))
}, 0)
return total.toFixed(2)
}
I will explain what is happening here:
We took a part of our old code that was in computed: and made a method out of it.
- Reduce The reduce method is great if you want to get one single value
  from multiple values in an array.
- Object.entries makes an easy array of the quantities in the cart.
- ACC is short for accumulator (so ADDING)
- CURR means CURRENT ENTRY
  so in the RETURN :
- We get CURR ([1}, because in an array it will get these props: key, value
  and we want value), so current items value(quantity) * the Price of the
  item ([0] because now we need the key to identify the item and it's
  price.
- The index prop is ,0 because we want ACC to start at 0
  SO THIS ALL ACTUALLY STATES:
> give me the OBJECTS that are in my CART.
> I use REDUCE because I want all the data that I pass and calculate to reach one total number.
> As PROPS I have ACC(accumulate), CURR(current item) and INDEX
> In our RETURN first get the VALUE of the current ITEM curr[1]
> And multiply THAT VALUE with the PRICE of the first item(by ID(key))
> ACC(accumulate) this for all the ITEMS in the CART ARRAY
> NOW all this is in const total
> return CONST TOTAL.toFixed(2) to get the total PRICE with 2 decimals

02:08:22
Now we are going to fix the OTHER TOTAL of the SIDE-BAR-CART:

<tbody>
  <tr v-for="(quantity, key, i) in cart" :key="i">
    <td><i class="icofont-carrot icofont-3x"></i></td>
    <td>{{ key }}</td>
    <td>\${{ getPrice(key) }}</td>
    <td class="center">{{ quantity }}</td>
    <td>\${{ quantity * getPrice(key) }}</td>
    <td class="center">
      <button @click="remove(key)" class="btn btn-light cart-remove">
        &times;
      </button>
    </td>
  </tr>
</tbody>
We also need to fix "no items in cart" to a dynamic variable:
<p class="center" v-if="!Object.keys(cart).length"><em>No items in cart</em></p>
So here we say IF there are NO object.keys (objects) in cart SHOW "no items in cart

We also need to fix the delete X button:
<button @click="remove(key)" class="btn btn-light cart-remove">
&times;
</button>
Now we have the BUTTON with the function, but we need to get this function out of the PARENT , because we cant delete items from this child component so first in the child component (app.component('sidebar') we will need to put this remove() function as a prop:
app.component('sidebar', {
props: ['toggle', 'cart', 'inventory', 'remove'],
Now go to the parent data() function and put it in the methods:
methods: {
addToCart(name, index) {
if (!this.cart[name]) this.cart[name] = 0
this.cart[name] += this.inventory[index].quantity
this.inventory[index].quantity = 0
},
toggleSidebar() {
this.showSidebar = !this.showSidebar
},
removeItem(name) {
delete this.cart[name]
}
},
Now get to the <sidebar /> and add it, note that the function in the child component is named REMOVE() and in the parent is named REMOVEITEM() because if it has the same name it will not work

We also need to the number from the page to clear so it is not stuck on 2 , when we deleted the item from our sidebar:
addToCart(name, index) {
if (!this.cart[name]) this.cart[name] = 0
this.cart[name] += this.inventory[index].quantity
this.inventory[index].quantity = 0
The onlhy other thing is that the cart right topside ALWAYS has (0), Lets fix that by:
computed: {
totalQuantity() {
return Object.values(this.cart).reduce((acc, curr) => {
return acc + curr
}, 0)
}
Here we keep adding(acc) the current(curr) added items
12 - ⌨️ (2:15:54) Reuseable Components
At the start of this chapter, the instructor is moving JAVASCRIPT code from the HTML files into a app.js file.

Also the difficulties with making a complex website are discussed:
- storage across different pages
- re-used code
- comlexities with components

The fix for these problems is to create ONE Front-End page and use
a ROUTER to go from page to page. This way we can work with components and keep the code clean and easy to read. We will set all that stuff up in the next chapter where we be working with VUE CLI.
13 - ⌨️ (2:26:20) Vue CLI

npm install -g @vue/cli

In Tutorial we are on version 4.5.1 (terminal: vue --version)  
In my Webstorm I'm on version 5.0.8

Create a new project:
vue create shop-app-project-q

On options choose Manually select Features (select on with spacebar):
- Vue version 3
- Babel
- Router
- Linter

>hit ENTER<

- choose version 3X
- Use History Mode for localhost:8080/users
  Use Hash Router for localhost:8080#users
- Choose ESLINT + Standard config
- Choose Lint on Save
- Yes on save in Package.json
- Save as a preset -> No

14 - ⌨️ (2:32:48) Vue Folder Structure

The features of VUE CLI are discussed

We have changed some code in main.js :
const app = createApp(App);
app.use(router);
app.mount('#app');

Now it's a bit easier to parse through when we add new packages

```<router-link> and <router-view>``` are vue ROUTER elements that we use 
to stay on the same Front-End and still can navigate to different pages.
---

Files are usually split up in view files(pages) and components(code pieces that we import in our pages.

15 - ⌨️ (2:43:58) Top Nav

Here we will begin moving our stuff over from the HTML and JAVASCRIPT files to our VUE CLI application:

We start with the NAV BAR:
- Copy it (<header>) from app.html and move them to App.vue.
- Put them on the previous NAV that was there
- Start to replace the <a> to other pages with ROUTER links
  <instead of <a> -> <router-link></router-link>
- Create the routes in router/index.js
- The router link needs to -> <router-link to:"/products">
- We can delete the about.html and make a Products.vue page in
  the view directory. Also add this:
```<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Products'
}
</script>
```
so we dont get that annoying components must be multi-word error

16A - ⌨️ (2:48:45) Styling with SASS

Our STYLES are in our assets directory>
You will notice that in every .vue file there is an element called <style>
By default the style tag globally affects the styling, this is generally not good practice because now you could spend hours looking for a particular style choice you made and it influences an whole other file. THo fix this we use <style scoped> so it affects the style just for that .vue file.

You can make a main.css and import that .css file in main.js so that could be your default style guide and then you can make specific style choices on the .vue files using <style scoped> on these.

We will also be useing SASS files. we can copy/paste this from the tutorial project and the MOST IMPORTANT file is style.scss, because that one IMPORTS all the .sass files. So now you need to import that style.scss to main.js:
first in terminal --> npm install -D sass-loader sass
import './assets/styles/style.scss
(in tutorial they use another version (Vue CLI 4, so webpack 4) and they install like this: npm install -D sass-loader@^10 sass
I checked the json and it looks like I am also using webpack 4 so i used:
npm install -D sass-loader@^10 sass

So in main.js:
// import './assets/styles/main.css'
import './assets/styles/style.scss'
and make sure you have the sass files in your src/assets

16B - ⌨️ (3:00:20) APPLICATION PAGES

Use the old code and from app.html copy so it looks like this:
```<template>
  <div class="home">
    <div class="splash-container">
      <div class="splash">
        <h1>Splendid Food</h1>
      </div>
    </div>

    <main class="wrapper">

      <h2>Recommended</h2>

      <div class="recommended">

        <div v-for="(product, i) in inventory.slice(0,3)" :key="product.id" class="card">
          <div class="card-title">
            {{ product.name }}
          </div>
          <div class="card-body">
            <i class="icofont-10x icofont-{{ product.icon }}"></i>
            <form>
              <div class="row">
                <div class="cell">
                  <label>Type:</label>
                </div>
                <div class="cell">
                  <em>{{ product.type }}</em>
                </div>
              </div>
              <div class="row">
                <div class="cell">
                  <label>Price:</label>
                </div>
                <div class="cell">
                  ${{ product.price.USD }}
                </div>
              </div>
              <div class="row">
                <div class="cell">
                  <label>Quantity:</label>
                </div>
                <div class="cell">
                  <input type="number" v-model.number="product.quantity">
                </div>
              </div>
            </form>
          </div>
          <div class="card-footer">
            <button @click="addToCart(product.name, i)" class="btn btn-light">
              Add to cart
            </button>
          </div>
        </div>

      </div>

    </main>

  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name : 'Home',
  props: ['inventory']
}
</script>
```
nothing is showing up on the page because the inventory is now broken. We have the food.json in our /src, but we need to also import it in Home.vue:
```
<script>
import food from '../food.json'

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name : 'Home',data () {
    return {
      inventory: food
    }
  },
  components: {
  }
}

</script>
Do the same with Producs.vue (we will make it dynamic later)
<template>
  <main class="wrapper">
    <h1>Products</h1>
  </main>

</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Products',  props: ['inventory', 'addToCart'],
  components: {
  }
}
</script>
```
Do the same with PastOrders.vue (we will make it dynamic later)
```<template>
  <main class="wrapper">
    <h1>Past Orders</h1>

    <table class="product-table">
      <thead>
      <tr>
        <td><span class="sr-only">Product Image</span></td>
        <td>Product</td>
        <td>Price</td>
        <td>Quantity</td>
        <td>Total</td>
        <td><span class="sr-only">Actions</span></td>
      </tr>
      </thead>
      <tbody>
      <tr>
        <td><i class="icofont-carrot icofont-4x" /></td>
        <td>Carrot</td>
        <td>$1.00</td>
        <td>1</td>
        <td>$1.00</td>
        <td><button class="btn btn-dark">Add</button></td>
      </tr>
      <tr>
        <td><i class="icofont-carrot icofont-4x" /></td>
        <td>Banana</td>
        <td>$0.50</td>
        <td>10</td>
        <td>$5.00</td>
        <td><button class="btn btn-dark">Add</button></td>
      </tr>
      </tbody>
    </table>
  </main>

</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name : 'PastOrders',
  components : {}
}
</script>
```
The PastOrders had an error in an <i> tag we just needed to close those tags with / so:   <td><i class="icofont-carrot icofont-4x" /></td>

17 - ⌨️ (3:06:07) Sidebar

We want the <sidebar /> to be a seperate COMPONENT, so in directory
components/ make Sidebar.vue and import this .vue file in App.vue file to make it available globally



18 - ⌨️ (3:20:46) Adding Items to Cart


*/































