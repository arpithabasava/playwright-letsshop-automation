# Playwright Automation – Rahul Shetty Academy E-commerce App

End-to-end test automation for the Rahul Shetty Academy practice e-commerce app
(https://rahulshettyacademy.com/client) using **Playwright with JavaScript**.
Built to practise test design, the Page Object Model and test reporting.

## What is covered

- **Login:** valid login, invalid credentials and field validations
- **Products:** viewing the product list and searching for a product
- **Cart:** adding a product to the cart and checking the cart items
- **Checkout:** entering shipping details, selecting a country and placing an order
- **Orders:** confirming the placed order appears in the order history

[Edit this list so it matches the tests you actually wrote.]

## Tech stack

- Playwright (JavaScript)
- Node.js
- Page Object Model
- Playwright HTML report
- Git and GitHub

## Project structure

```
├── tests/                  # test specs
├── pages/                  # page object classes
├── playwright.config.js
└── package.json
```

## How to run

```bash
git clone [repo URL]
cd [repo-name]
npm install
npx playwright install
npx playwright test
npx playwright show-report
```

## Test report

[Add a screenshot of the HTML report here.]

## What I learned

- Writing stable locators and assertions
- Organising tests with the Page Object Model
- Handling dynamic elements such as the country auto-suggest on checkout
- Reading Playwright reports and traces to debug failures

## Author

**Arpitha B B**
[LinkedIn](https://www.linkedin.com/in/arpitha-rajesh-itagi-723826130) | arpithabasava@gmail.com# playwright-letsshop-automation
This is the demo shopping website which lets us shop and add to cart and process the order
