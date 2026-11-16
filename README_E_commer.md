# E-Commerce Test Cases

## TC_01_P

- **Scenario ID:** TS_01
- **Test Type:** Positive
- **Severity:** Medium
- **Test Case Description:** Verify Solar System Color Imager is displayed on the Hot Products page.
- **Test Steps:**
  1. Open the e-commerce application.
  2. Navigate to the Hot Products section.
  3. Check the Solar System Color Imager product.
- **Test Data:** Solar System Color Imager
- **Expected Result:** Product image, name and price ($175.00) should be displayed correctly.
- **Actual Result:** 

## TC_02_N

- **Scenario ID:** TS_02
- **Test Type:** Negative
- **Severity:** High
- **Test Case Description:** Verify that incorrect or missing product information is not displayed.
- **Test Steps:**
  1. Open the Hot Products section.
  2. Check the product image, name and price.
  3. Verify the displayed information.
- **Test Data:** Solar System Color Imager
- **Expected Result:** Product information should not be incorrect or incomplete.
- **Actual Result:** 

## TC_03_P

- **Scenario ID:** TS_03
- **Test Type:** Positive
- **Severity:** Medium
- **Test Case Description:** Verify the Solar System Color Imager product details page.
- **Test Steps:**
  1. Open Hot Products.
  2. Click Solar System Color Imager.
  3. Verify the product image, name, description and price.
- **Test Data:** Solar System Color Imager
- **Expected Result:** Product details should be displayed correctly, including the price of $175.00.
- **Actual Result:** 

## TC_04_N

- **Scenario ID:** TS_04
- **Test Type:** Negative
- **Severity:** High
- **Test Case Description:** Verify that product details are consistent with the Hot Products page.
- **Test Steps:**
  1. Open the Solar System Color Imager product details page.
  2. Compare the product name and price with the Hot Products page.
  3. Verify the displayed information.
- **Test Data:** Product name and price
- **Expected Result:** Product name and price should match the information displayed on the Hot Products page.
- **Actual Result:** 

## TC_05_P

- **Scenario ID:** TS_05
- **Test Type:** Positive
- **Severity:** High
- **Test Case Description:** Verify quantity selection and Add To Cart functionality.
- **Test Steps:**
  1. Open the product details page.
  2. Select quantity 2.
  3. Click Add To Cart.
  4. Open the Shopping Cart.
- **Test Data:** Product: Solar System Color Imager; Quantity: 2
- **Expected Result:** Product should be added to the cart with quantity 2 and a subtotal of $350.00.
- **Actual Result:** 

## TC_06_N

- **Scenario ID:** TS_06
- **Test Type:** Negative
- **Severity:** High
- **Test Case Description:** Verify that an invalid quantity is not accepted.
- **Test Steps:**
  1. Open the product details page.
  2. Try to enter or select an invalid quantity, if the application permits.
  3. Click Add To Cart.
  4. Verify the result.
- **Test Data:** Quantity: 0 or negative value, if accepted by the input
- **Expected Result:** Invalid quantity should not be accepted or added to the cart.
- **Actual Result:** 

## TC_07_P

- **Scenario ID:** TS_07
- **Test Type:** Positive
- **Severity:** Critical
- **Test Case Description:** Verify Solar System Color Imager details in the Shopping Cart.
- **Test Steps:**
  1. Add Solar System Color Imager to the cart.
  2. Open the Shopping Cart.
  3. Verify product name, quantity, price and total.
- **Test Data:** Product: Solar System Color Imager; Quantity: 1
- **Expected Result:** Product should be displayed with quantity 1, price $175.00 and the correct total including shipping.
- **Actual Result:** 

## TC_08_N

- **Scenario ID:** TS_08
- **Test Type:** Negative
- **Severity:** Critical
- **Test Case Description:** Verify that the cart total is recalculated correctly when the quantity is changed.
- **Test Steps:**
  1. Add Solar System Color Imager to the cart.
  2. Change the quantity from 1 to 2.
  3. Verify the updated subtotal and total.
- **Test Data:** Quantity changed from 1 to 2
- **Expected Result:** Subtotal should update to $350.00 and the total should include the applicable shipping charge.
- **Actual Result:** 

## TC_09_P

- **Scenario ID:** TS_09
- **Test Type:** Positive
- **Severity:** Critical
- **Test Case Description:** Verify successful order placement for Solar System Color Imager.
- **Test Steps:**
  1. Add the product to the cart.
  2. Enter valid shipping address details.
  3. Enter valid payment details using authorized test data.
  4. Click Place Order.
  5. Verify the order confirmation page.
- **Test Data:** Valid shipping address and authorized payment test data
- **Expected Result:** Order should be placed successfully, and the confirmation page should display the order ID and order details.
- **Actual Result:** 

## TC_10_N

- **Scenario ID:** TS_10
- **Test Type:** Negative
- **Severity:** Critical
- **Test Case Description:** Verify checkout when mandatory shipping or payment details are missing.
- **Test Steps:**
  1. Add the product to the cart.
  2. Leave a mandatory shipping or payment field blank.
  3. Click Place Order.
  4. Verify the application response.
- **Test Data:** One mandatory checkout field left blank
- **Expected Result:** Validation should be displayed and the order should not be placed with incomplete mandatory details.
- **Actual Result:**
