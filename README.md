Shopify-Wish-List
=================

non-app wish list using customer.tags

To make this wish list work, you'll need to add an include tag for wishlist-product.liquid in your product page -- make sure that it is not within the add-to-cart form. And you'll need to add an include tag for wishlist-page.liquid in a page with the handle wish-list. 

There's no in-line styling so this should pick up your product and page template styling.

The wish list works by adding the product id to the customers account tags. To remove the item, another tag is added 
with an "x" preceding the product id. Re-adding the item to the wish list adds another "x". At this point there are 
three tags for the one product. If a customer went crazy with the wish list, adding and removing and re-adding 
products, it could fill up their customer tags quickly. If there's any issue with their account or interference 
with an app (like a wholesale app), I'd look first to their tags.
