## Screen Changes
Tracking all the design iterations, component fixes, and UX improvements made while building out these screens.

---

## Screen Changes: Cart in Collapsed State

* **Progress Stepper:** Fix the alignment and color of the `{ProgressStepper}` component.
* **Card:** Reduce the delete icon size from **15px to 13px**.
* **Save for Later:** Change the text style from highlighted to dim by setting the opacity to **70%**. Also, reduce the typography size from **16px to 14px**.
* **Button Spacing:** Reduce the spacing between buttons.
* **Coupons:**
* Change the color fill and outer stroke of the **Applied** button from 100% cyan to a gradient to highlight that the coupon has been applied.
* Reduce the **Remove** button typography size from **16px to 11px**.


* **Proceed Button:** Increase the size of the **Proceed** button from small to big, and add a message showing the remaining/consisting steps.
* **Navigation Bar:** Reduce the number of icons from 5 to 4 by removing the **Wishlist** icon. The active icons should now be: `{Home, Search, Cart, Profile}`.
* **Color Consistency:** Use a consistent color scheme to reduce friction and eye strain for the user, as the previous design caused eye strain due to having too many colors.
* **Color Purpose:** Define a clear purpose for each color used; remember its naming convention.



---

## Cart: Out of Stock

* Reduce the opacity of the "Out of Stock" bar.
* Change the color of the warning triangle icon ($\triangle$) from red to yellow.
* Change the copy from `{incomplete order...}` to `{Out of stock description: "This item is currently no longer available"}`.
* **For the card containing the item that is unavailable:**
* It should be highlighted in the same color used for "Out of Stock".
* Remove the quantity selector (`no. of qty`) and replace it with a **"Notify me"** button.
* Remove the "Low inventory / recently sold out" text and replace it with **"See similar products"**.
* Change the action button to an **"Add"** button.
* Add a **"See similar products"** link/button.
* Clearly mark it as **"Out of Stock"**.



---

## Payment Method

* Add a recommendation message: `{In your previous order, you used another payment option: COD}`.
* Separate the section so it doesn't look joined together.
* Reduce the opacity of the bar.




---

## Order Placed Success

* Add a gradient to the page for a pop-up message to highlight the success.
* Add a small description message: `"Thank you for your purchase"`.

---

## Track Order

* Add an order number along with an **"In Transit"** button styled with a gradient to highlight it.
* Display the carrier name (e.g., **Carrier: FedEx**), so the user doesn't get confused.
* Provide detailed tracking history and add a map in **dark mode** to match the overall color vibe.


## Accessibility & UI Design Notes

* **Contrast Ratio:** Check the text/background pair to ensure it is recorded with a measured contrast ratio of > 4.5:1.
* **UI Hierarchy & Meaning:** Give a clear sense of purpose to every UI page.
* **Tab Order Annotations:** Create an intended tab-order annotation document for the payments and declined card screens, keeping keyboard navigation and focus management in mind.
* **Interaction Documentation:** Detail how it works, understand why this is important, and outline exactly how the user interacts with it.
