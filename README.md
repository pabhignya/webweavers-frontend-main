# webweavers-frontend

Webweavers is a small size e-commerce website for a grocery store where we can view all the products search based on the product name and/or category, add products to wishlist, view each product with its description add it to cart, change the quantities on cart, view previous orders and update the user profile.

## Heroku Deployment:
https://webweavers-frontend.herokuapp.com/

## Iteration 1
### Pachava Abhignya:

Components:

    1) All products
    2) Product

Functionality:

    1) Add/Remove Favorites
    2) Increase/Decrease quantities
    3) Search based on product name
    4) Search by catogery
    5) Search based on both product name and catogery
![image](https://media.github.ccs.neu.edu/user/11128/files/76b1977d-12a9-4597-91c3-3d1ed949745f)
![image](https://media.github.ccs.neu.edu/user/11128/files/44144f40-ae2a-412d-9730-ff27d0215abe)


---
### Marwa Elali

Components:

    - Cart
    - OrdersList

Functionality:

    - In App.js, added links and routes for 'Cart' and 'Orders'
    - In Product.js, implement 'Add to cart' button functionality
    - View items in cart
    - Checkout cart order
    - View previous orders

Screenshots:

- Navbar shows links to Cart and Orders pages
- Cart page has a checkout button that completes the order when clicked

![Cart page](./public/images/screenshots/cart-page.png)

![Orders page](./public/images/screenshots/orders-page.png)

### Peter Murphy

Components:

    1) Profile

Functionality:

    - Added links and routes for user profile page
    - Made links to cart and profile appear only when logged in
    - Added profile page that displays the user first and last name if found in db
    - Added profile service to make get and update requests to the profile db collection via the backend API

Screenshots:

Navbar Logged Out:
![navbar logged out](./public/images/screenshots/navbar_logged_out.jpg)

Navbar Logged In:
![navbar loged in](./public/images/screenshots/navbar_logged_in.jpg)

Profile Page:
![profile page](./public/images/screenshots/profile_page.jpg)


## Iteration 2

### Marwa Elali
Components:

- Update Cart.js component with ability to update product quantities and checkout order
![updated Cart page](./public/images/screenshots/itr2-cart-page.png)

- Implement basic OrdersList.js (to be completed) showing previous orders
![previous orders page](./public/images/screenshots/itr2-orders-page.png)


### Peter Murphy

- Added user profile page where a user can view their profile information
![profile page](public\images\screenshots\profile_page.png)

- User can edit and save any of the information found on the profile page
![edit profile](public\images\screenshots\editing_profile.png)
![save profile](public\images\screenshots\save_profile_changes.png)

### Pachava Abhignya
- Added a wishlist page where user can reorder the wishlist products 
- A wishlist product can also directly be added to cart.
 ![image](https://media.github.ccs.neu.edu/user/11128/files/04a355be-bd95-4d06-9dbc-6adcab1eeb63)


## Iteration 3

### Marwa Elali
- Implemented functionality to remove items from shopping cart
- Refactored styling of components and CSS to match the theme from the wireframes
- Implemented third party library - Material UI - replaced "delete" button in cart, profile and cart links in the navbar, and favourites heart with @mui icons. Also included an icon in the logout button

![home page](./public/images/screenshots/itr3-home-page.png)
![product page](./public/images/screenshots/itr3-product-page.png)
![orders page](./public/images/screenshots/itr3-orders-page.png)
![wishlist page](./public/images/screenshots/itr3-wishlist-page.png)
![cart page](./public/images/screenshots/itr3-cart-page.png)
![profile page](./public/images/screenshots/itr3-profile-page.png)

### Peter Murphy
- Added improvements to user profile page such as better editing UI and formatting.
![Profile UI Update](./public/images/screenshots/Profile_UI.jpg)

- Refactored Cart page for better handling of changing quantity of items in cart, and added a live total price counter.
![Cart Update](./public/images/screenshots/Cart_multiple_items_and_total.jpg)

- Updated orders list page to include Bootstrap Accordion component. Also includes Bootstrap Table to show summary of items in order.
![Order History](./public/images/screenshots/order_history.jpg)


### Pachava Abhignya
- Added the functionality of adding item from wishlist to cart
