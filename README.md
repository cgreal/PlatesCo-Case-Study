# PlatesCo-Case-Study
* Open index page with any browser
* As the product is added to the cart, (item.price * item.numberOfUnits) runs the process.
* If there is a discount, the discounted amount is subtracted from the total price
* As the last step Shipping prices are added.


# Some processes had rounding issues caused by javascript;

- I tried multiple methods for this issue.
- The most stable of the methods was edited using Math.floor
- Created the most stable operation using "Math.floor".
  -- Math.floor(totalPrice * 100) / 100).toFixed(2)
 
* No framework used.
