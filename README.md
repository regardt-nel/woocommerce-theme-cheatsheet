# WooCommerce template file cheatsheet

1. `archive-product.php`: Controls the display of product archives (e.g., product category and tag pages).
2. `content-product.php`: Defines the structure of a single product when it is displayed in a loop.
3. `single-product.php`: Controls the layout of an individual product page.
4. `cart.php`: Manages the layout of the shopping cart page.
5. `checkout`: This folder contains various template files related to the checkout process, including `form-checkout.php` for the checkout form and `thankyou.php` for the order confirmation page.
6. `myaccount`: This folder contains template files for user account-related pages, such as `my-account.php` for the main account page, `orders.php` for the order history page, and `view-order.php` for viewing a specific order.
7. `content-widget-product.php`: Determines the display of products in widgets.
8. `loop`: This folder contains template files used in loops, including `loop/loop-start.php` and `loop/loop-end.php`.
9. `content-single-product.php`: Defines the structure of a single product when it is displayed individually.
10. `content-product_cat.php`: Controls the display of product category archives.
11. `content-product-search.php`: Defines the layout of the search results page for products.
12. `content-product-tag.php`: Controls the display of product tag archives.
13. `content-product-quickview.php`: Determines the structure of the quick view popup for products.
14. `content-product-rating.php`: Defines the layout of the product rating and review section.
15. `content-product-related.php`: Controls the display of related products on a product page.
16. `content-product-reviews.php`: Determines the layout of customer reviews for a product.
17. `content-product-share.php`: Controls the display of social sharing buttons for products.
18. `form-login.php`: Manages the layout of the user login form.
19. `form-lost-password.php`: Controls the appearance of the lost password form.
20. `form-register.php`: Defines the structure of the user registration form.
21. `content-widget-price-filter.php`: Determines the display of the price filter widget.
22. `content-widget-product-categories.php`: Controls the appearance of the product categories widget.
23. `content-widget-recent-reviews.php`: Defines the layout of the recent reviews widget.
24. `content-widget-recently-viewed.php`: Controls the display of the recently viewed products widget.
25. `single-product-add-to-cart.php`: Determines the layout of the add-to-cart section on a product page.
26. `single-product-reviews.php`: Controls the appearance of customer reviews for a product.
27. `taxonomy-product_cat.php`: Defines the layout of the product category taxonomy archive.
28. `taxonomy-product-tag.php`: Controls the appearance of the product tag taxonomy archive.
29. `form-checkout-coupon.php`: Controls the appearance of the coupon code input field on the checkout page.
30. `form-checkout-payment.php`: Defines the layout of the available payment methods on the checkout page.
31. `form-checkout-shipping.php`: Determines the appearance of the shipping methods and address fields on the checkout page.
32. `form-edit-account.php`: Controls the layout of the account information editing form.
33. `form-edit-address.php`: Defines the structure of the address editing form.
34. `form-lost-password.php`: Manages the appearance of the lost password form.
35. `form-reset-password.php`: Determines the layout of the password reset form.
36. `form-tracking.php`: Controls the display of the order tracking form.
37. `loop/add-to-cart.php`: Defines the structure of the add-to-cart button for products displayed in loops.
38. `loop/no-products-found.php`: Determines the appearance when no products are found in a loop.
39. `loop/pagination.php`: Controls the display of pagination on archive pages.
40. `loop/result-count.php`: Defines the layout of the result count information on archive pages.
41. `single-product/meta.php`: Determines the appearance of the product metadata (categories, tags, etc.) on a single product page.
42. `single-product/price.php`: Controls the display of the product price on a single product page.
43. `single-product/product-image.php`: Defines the structure of the product image section on a single product page.
44. `single-product/product-thumbnails.php`: Determines the layout of the product thumbnail images on a single product page.
45. `single-product/rating.php`: Controls the appearance of the product rating on a single product page.
46. `single-product/related.php`: Defines the structure of the related products section on a single product page.
47. `single-product/tabs/description.php`: Determines the layout of the product description tab on a single product page.
48. `single-product/tabs/additional-information.php`: Controls the appearance of the additional information tab on a single product page.
49. `single-product/tabs/reviews.php`: Defines the structure of the reviews tab on a single product page.
50. `taxonomy-product_shipping_class.php`: Controls the display of products based on their shipping classes.
51. `cart/cart-empty.php`: Determines the layout when the shopping cart is empty.
52. `cart/cart-item-data.php`: Controls the appearance of additional data for each item in the shopping cart.
53. `cart/cart-shipping.php`: Defines the structure of the shipping calculator section on the cart page.
54. `cart/cart-totals.php`: Determines the layout of the order totals section on the cart page.
55. `cart/mini-cart.php`: Controls the display of the mini cart dropdown or widget.
56. `checkout/form-billing.php`: Defines the structure of the billing address form on the checkout page.
57. `checkout/form-coupon.php`: Controls the appearance of the coupon code form on the checkout page.
58. `checkout/form-gateways.php`: Determines the layout of the available payment gateways on the checkout page.
59. `checkout/form-login.php`: Defines the structure of the login form on the checkout page.
60. `checkout/form-shipping.php`: Controls the display of the shipping address form on the checkout page.
61. `checkout/payment-method.php`: Determines the appearance of each available payment method on the checkout page.
62. `checkout/payment.php`: Controls the layout of the payment options section on the checkout page.
63. `checkout/review-order.php`: Defines the structure of the order review section on the checkout page.
64. `checkout/thankyou.php`: Determines the layout of the thank you page after a successful order.
65. `global/form-login.php`: Defines the structure of the login form used across different pages.
66. `global/quantity-input.php`: Controls the appearance of the quantity input field for products.
67. `global/wrapper-end.php`: Determines the end of the wrapper element used in various templates.
68. `global/wrapper-start.php`: Controls the start of the wrapper element used in various templates.
69. `loop/add-to-cart.php`: Determines the structure of the add-to-cart button for products displayed in loops.
70. `loop/loop-end.php`: Defines the end of the loop element used in various templates.
71. `loop/loop-start.php`: Controls the start of the loop element used in various templates.
72. `order/order-details-customer.php`: Determines the layout of the order details section for customers.
73. `order/order-details-item.php`: Controls the appearance of each item in the order details section.
74. `order/order-details.php`: Defines the structure of the entire order details section.
75. `order/tracking.php`: Controls the display of the order tracking form and information.
76. `single-product/add-to-cart/variable.php`: Controls the appearance of the variable product options on a single product page.
77. `single-product/meta.php`: Determines the layout of the product metadata (categories, tags, etc.) on a single product page.
78. `single-product/product-image-carousel.php`: Defines the structure of the product image carousel on a single product page.
79. `single-product/product-thumbnails.php`: Controls the appearance of the product thumbnail images on a single product page.
80. `single-product/rating.php`: Determines the layout of the product rating section on a single product page.
81. `single-product/review.php`: Controls the display of individual customer reviews on a single product page.
82. `single-product/review-rating.php`: Defines the appearance of the star rating for customer reviews.
83. `single-product/review-meta.php`: Determines the layout of the metadata for customer reviews.
84. `single-product/sale-flash.php`: Controls the display of the "Sale" flash badge on a single product page for discounted products.
85. `single-product/share.php`: Determines the appearance of the social sharing buttons on a single product page.
86. `single-product/short-description.php`: Controls the display of the short description for a product on a single product page.
87. `single-product/tabs/additional-information.php`: Defines the structure of the additional information tab on a single product page.
88. `single-product/tabs/description.php`: Controls the appearance of the product description tab on a single product page.
89. `single-product/tabs/reviews.php`: Determines the layout of the customer reviews tab on a single product page.
90. `single-product/title.php`: Controls the display of the product title on a single product page.
91. `single-product/up-sells.php`: Determines the appearance of up-sell products on a single product page.
92. `taxonomy-product_cat.php`: Controls the display of product category archive pages.
93. `taxonomy-product_tag.php`: Determines the layout of product tag archive pages.
94. `widget-recent-reviews.php`: Defines the appearance of the "Recent Reviews" widget.
95. `widget-recently-viewed.php`: Controls the display of the "Recently Viewed Products" widget.
96. `widget-top-rated-products.php`: Determines the layout of the "Top Rated Products" widget.
97. `widget-product-categories.php`: Controls the appearance of the "Product Categories" widget.
98. `widget-layered-nav.php`: Defines the structure of the layered navigation widget.
99. `widget-price-filter.php`: Determines the layout of the price filter widget.
100. `widget-product-search.php`: Controls the display of the product search widget.
101. `cart/cart-collaterals.php`: Determines the layout of additional cart collaterals such as cross-sells and related products.
102. `cart/cart-item.php`: Controls the appearance of each item in the shopping cart.
103. `cart/cart-shipping-calculator.php`: Defines the structure of the shipping calculator on the cart page.
104. `cart/mini-cart-button.php`: Determines the layout of the mini cart button or icon.
105. `checkout/form-additional.php`: Controls the display of additional fields on the checkout page, such as order notes.
106. `checkout/form-checkout.php`: Defines the structure of the entire checkout form.
107. `checkout/form-pay.php`: Determines the appearance of the payment information form on the checkout page.
108. `checkout/review-order.php`: Controls the display of the order review section on the checkout page.
109. `checkout/review-order-table.php`: Determines the layout of the order review table on the checkout page.
110. `checkout/terms.php`: Controls the display of terms and conditions acceptance on the checkout page.
111. `global/form-reset-password.php`: Defines the structure of the password reset form.
112. `global/flash-notice.php`: Determines the appearance of flash notices or messages.
113. `global/form-lost-password.php`: Controls the layout of the lost password form.
114. `global/form-login-logout.php`: Defines the structure of the login/logout form.
115. `global/form-register.php`: Determines the appearance of the user registration form.
116. `global/notices.php`: Controls the display of various notices throughout the WooCommerce pages.
117. `global/quantity-input.php`: Defines the structure of the quantity input field.
118. `global/sidebar.php`: Determines the layout of the sidebar on WooCommerce pages.
119. `loop/loop-pagination.php`: Controls the display of pagination on archive pages.
120. `loop/loop-result-count.php`: Determines the appearance of the result count information on archive pages.
121. `order/form-tracking.php`: Defines the structure of the order tracking form.
122. `order/order-details.php`: Controls the layout of the order details section.
123. `order/order-details-item.php`: Determines the appearance of each item in the order details section.
124. `order/order-details-customer.php`: Defines the structure of the customer information in the order details section.
125. `order/order-receipt.php`: Controls the display of the order receipt template.
126. `single-product/add-to-cart/external.php`: Controls the appearance of the external product options on a single product page.
127. `single-product/add-to-cart/grouped.php`: Determines the layout of the grouped product options on a single product page.
128. `single-product/add-to-cart/simple.php`: Defines the structure of the simple product options on a single product page.
129. `single-product/add-to-cart/variation-add-to-cart-button.php`: Controls the display of the add-to-cart button for variable product variations.
130. `single-product/meta.php`: Determines the layout of the product metadata (categories, tags, etc.) on a single product page.
131. `single-product/product-image-gallery.php`: Defines the structure of the product image gallery on a single product page.
132. `single-product/product-thumbnails.php`: Controls the appearance of the product thumbnail images on a single product page.
133. `single-product/rating.php`: Determines the layout of the product rating section on a single product page.
134. `single-product/review.php`: Controls the display of individual customer reviews on a single product page.
135. `single-product/review-rating.php`: Defines the appearance of the star rating for customer reviews.
136. `single-product/review-meta.php`: Determines the layout of the metadata for customer reviews.
137. `single-product/sale-flash.php`: Controls the display of the "Sale" flash badge on a single product page for discounted products.
138. `single-product/share.php`: Determines the appearance of the social sharing buttons on a single product page.
139. `single-product/short-description.php`: Controls the display of the short description for a product on a single product page.
140. `single-product/tabs/additional-information.php`: Defines the structure of the additional information tab on a single product page.
141. `single-product/tabs/description.php`: Controls the appearance of the product description tab on a single product page.
142. `single-product/tabs/reviews.php`: Determines the layout of the customer reviews tab on a single product page.
143. `single-product/title.php`: Controls the display of the product title on a single product page.
144. `single-product/up-sells.php`: Determines the appearance of up-sell products on a single product page.
145. `taxonomy-product_shipping_class.php`: Controls the display of products based on their shipping classes.
146. `widget-recent-reviews.php`: Defines the appearance of the "Recent Reviews" widget.
147. `widget-recently-viewed.php`: Controls the display of the "Recently Viewed Products" widget.
148. `widget-top-rated-products.php`: Determines the layout of the "Top Rated Products" widget.
149. `widget-product-categories.php`: Controls the appearance of the "Product Categories" widget.
150. `widget-layered-nav.php`: Defines the structure of the layered navigation widget.
