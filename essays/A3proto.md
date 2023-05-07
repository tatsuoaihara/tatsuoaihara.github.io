---
layout: essay
type: essay
title: "A3 Protoype"
# All dates must be YYYY-MM-DD format!
date: 2023-05-04
published: true
labels:
  - Assignment 3
---
Show what each page will look like. The pages do not have to be “functional” but the design should clear. Here is an example PPT prototype

Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.
The design of my site will be rather simple in the sense that I do not intend to make it super complicated with a lot of features. The shopping cart will be integrated into the products page when they choose to add the items to the cart as well as remove the items from the cart. But when they wish to checkout, they will be taken to a separate page. When in the products page, they will be able to access the "Remove from cart" and "add to cart" buttons along the quantity desired textboxes. This will allow for a change in the amount of products they desire. 


Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.
The data and the amount of quantities being requested will be in the sessions to help rather than have it all jammed in the query string like before. For the data format, I will have three things being stored, the product name, the number they are asking for and its key, such as chocolates, sour gummies and regular gummies. Code examples will be as provided: { ProdKey: 'Chocolates', ProdIndex: 1, ProdQty: '1' }. This helps to store the amount being seeked to the session allowing for them to come back to this even if they have not logged in yet.

How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?
To avoid access, it would be predoominantly to the invoice and anything that comes after that. They can view all the products, add products to the cart and remove them, but they should not be able to proceed to the cart to clarify, nor the invoice until after they log into their account of register one to their name.

Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)
I intend to greet them with a "welcome xxx, you last logged in __ times @ xxx HST" which provides a personal experience per user knowing that we can see when they last visited us.

If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?
I am not working with partners.

How are you approaching Assignment 3 differently than Assignment 2?
I am trying to read through the entire assignment first to make sure I am only doing things that i need first. If I have time afterwards, then I can go back and do the extra things rather than stress about everything from the beginning.
