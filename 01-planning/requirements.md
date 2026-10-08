# Requirements

## 1. Document Information

| Field | Details |
|---|---|
| Project | SauceDemo Manual QA Testing |
| Application | SauceDemo |
| Document | Requirements |
| Prepared By | Sowndarya Swetha |
| Version | 1.0 |
| Status | Defined |

> **Note:** SauceDemo does not provide a formal client SRS for this portfolio project. The requirements below are QA-derived functional requirements based on the application's observed functionality and intended user workflows. Where specific user accounts have distinct expected behavior, that behavior is captured as a separate requirement.

---

## 2. Login

| Req ID | Requirement |
|---|---|
| REQ-001 | User shall be able to log in successfully using valid credentials. |
| REQ-002 | Application shall prevent login when invalid credentials or unsupported login input are provided. |
| REQ-003 | Application shall validate empty and whitespace-only login fields and display appropriate validation behavior. |
| REQ-004 | Application shall handle leading/trailing spaces and invalid login input formats appropriately. |
| REQ-005 | Locked-out users shall be prevented from logging in and shown an appropriate error message. |
| REQ-006 | Unauthenticated users shall not be able to access protected pages through direct URLs. |

---

## 3. Logout and Session Behavior

| Req ID | Requirement |
|---|---|
| REQ-007 | Authenticated users shall be able to log out and return to the Login page. |
| REQ-008 | After logout, users shall not be able to access authenticated pages through browser Back navigation or direct protected URLs. |
| REQ-009 | Products added to the cart shall persist after the user logs out and logs in again using the same account. |

---

## 4. Products and Inventory

| Req ID | Requirement |
|---|---|
| REQ-010 | Application shall display available products with relevant product information such as name, image, price, and product action. |
| REQ-011 | Application shall provide product sorting options including Name A-Z, Name Z-A, Price Low-High, and Price High-Low. |
| REQ-012 | User shall be able to add a product to the shopping cart from the Products page. |
| REQ-013 | User shall be able to remove a product from the shopping cart from the Products page. |
| REQ-014 | The cart indicator shall update correctly when products are added to or removed from the cart from applicable pages, including the Products page and Product Details page. |
| REQ-015 | User shall be able to open the corresponding Product Details page by selecting either the product image or product title. |

---

## 5. Sidebar and Navigation

| Req ID | Requirement |
|---|---|
| REQ-016 | User shall be able to open and close the application sidebar menu. |
| REQ-017 | Sidebar shall provide access to All Items, Dynamic Catalog, About, Logout, and Reset App State options. |
| REQ-018 | Selecting All Items shall navigate the user to the Products page. |
| REQ-019 | Selecting Dynamic Catalog shall provide access to its available catalog features. |
| REQ-020 | Selecting About shall navigate the user to the About page. |
| REQ-021 | Reset App State shall reset the applicable application state as designed. |
| REQ-022 | Selecting Logout shall end the current user session and return the user to the Login page. |

---

## 6. Dynamic Catalog

| Req ID | Requirement |
|---|---|
| REQ-023 | Lazy Load functionality shall dynamically load additional catalog items as the user scrolls, as designed. |
| REQ-024 | Spinner functionality shall display the applicable loading indicator during the loading operation and resolve when loading is complete. |
| REQ-025 | Slider functionality shall allow the user to interact with the slider control and observe the corresponding application behavior. |

---

## 7. Product Details

| Req ID | Requirement |
|---|---|
| REQ-026 | Product Details page shall display the selected product's relevant information, including name, image, description, price, and cart action. |
| REQ-027 | User shall be able to add the selected product to the cart from the Product Details page. |
| REQ-028 | User shall be able to remove the selected product from the cart from the Product Details page. |
| REQ-029 | User shall be able to return from Product Details to the Products page. |

---

## 8. Shopping Cart

| Req ID | Requirement |
|---|---|
| REQ-030 | User shall be able to access and view the shopping cart. |
| REQ-031 | Cart shall display relevant information for added products, including product name, price, quantity, and available actions. |
| REQ-032 | User shall be able to remove products from the shopping cart. |
| REQ-033 | Products added to the cart shall persist when navigating between Products, Product Details, and Cart pages. |
| REQ-034 | User shall be able to continue shopping from the Cart page and return to the Products page. |
| REQ-035 | Cart indicator shall reflect the current number of products in the cart. |
| REQ-036 | Checkout shall not be completed when the shopping cart contains no products. |

---

## 9. Checkout

| Req ID | Requirement |
|---|---|
| REQ-037 | User shall be able to access Checkout when the cart contains at least one product. |
| REQ-038 | Checkout form shall provide First Name, Last Name, and Postal Code fields. |
| REQ-039 | Required checkout fields shall be validated when mandatory information is missing or invalid. |
| REQ-040 | User shall be able to proceed to the Order Overview when valid checkout information is provided. |
| REQ-041 | User shall be able to cancel checkout and return to the appropriate previous page while retaining cart contents. |
| REQ-042 | Order Overview shall display the products selected for purchase and their relevant pricing information. |
| REQ-043 | Application shall calculate and display Item Total, Tax, and final Total correctly. |
| REQ-044 | User shall be able to finish the order when all required conditions are satisfied. |

---

## 10. Order Completion

| Req ID | Requirement |
|---|---|
| REQ-045 | User shall be able to submit a valid order successfully. |
| REQ-046 | Application shall display an order confirmation page after successful order completion. |
| REQ-047 | Order confirmation page shall display appropriate confirmation information. |
| REQ-048 | Cart shall be cleared after successful order completion. |
| REQ-049 | User shall be able to return to the Products page after completing an order. |

---

## 11. Footer and External Links

| Req ID | Requirement |
|---|---|
| REQ-050 | Application shall display the footer with the available footer information and social-media links on applicable pages. |
| REQ-051 | Social-media links shall navigate to their corresponding external destinations. |
| REQ-052 | External footer links shall behave as designed when selected by the user. |

---

## 12. Requirement Coverage

The requirements cover the following major application areas:

- Login
- Logout and Session Behavior
- Products and Inventory
- Sidebar and Navigation
- Dynamic Catalog
- Product Details
- Shopping Cart
- Checkout
- Order Completion
- Footer and External Links

These requirements will be traced to test scenarios, test cases, and execution results through the Requirements Traceability Matrix.
