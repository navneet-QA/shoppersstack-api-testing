# ShoppersStack API Testing Project

Postman API testing project based on the uploaded **Shoppersstack** collection. The original collection is a Postman Collection v2.1 export. cite not included in file; see project source.

## Project scope
- 14 API modules
- 46 API requests
- HTTP methods covered: GET, POST, PUT, PATCH, DELETE
- Bearer-token authentication
- Request bodies using JSON
- Query parameters and path parameters
- Postman pre-request scripts and response assertions

## Modules
1. Shoppers Profile
2. Product View Action
3. Shoppers Address
4. Shoppers Wishlists
5. Shopper Cart
6. Shopper Order
7. Shopper Product Review
8. Bank Cards
9. Shopper Profile Cards
10. Shopper Bank Account
11. Shopper Wallet
12. Shopper Likes
13. Admin Profile
14. Admin Action

## Important security note
The original uploaded collection contained real-looking credentials, bearer tokens, phone numbers and payment-card data. Those values have been replaced with variables/placeholders in this GitHub-ready copy. **Do not commit real passwords, JWTs, CVVs, PINs, card numbers, or other secrets to GitHub.**

## How to use
1. Import `postman/ShoppersStack_API_Collection.json` into Postman.
2. Import `postman/ShoppersStack_API_Environment.json`.
3. Select the environment.
4. Replace placeholder values with valid test data.
5. Run requests individually or use Collection Runner.

## Existing assertions
The uploaded collection already contains Postman test scripts for selected requests, including status-code/response-time checks and response-body validation. This project preserves those scripts.

## GitHub
Suggested repository name: `shoppersstack-api-testing-postman`

## Source
Built from the user's exported `Shoppersstack` Postman collection (Collection v2.1).
