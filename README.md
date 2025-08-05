# APIAutomationExercise
This project tests the CoinGecko public API to verify critical details of the Bitcoin cryptocurrency using **Postman** and **Newman**.

## ✅ Objective

Automate API testing for the endpoint:
GET https://api.coingecko.com/api/v3/coins/bitcoin


### Test Cases Covered

1. ✅ **Status Code Validation**
   - Ensure response status is `200 OK`.

2. ✅ **Verify 3 Key Currencies (BPIs)**
   - The response must contain current price data for:
     - USD
     - GBP
     - EUR

3. ✅ **Market Cap & Total Volume**
   - Each currency (USD, GBP, EUR) must have:
     - `market_cap`
     - `total_volume`

4. ✅ **24-Hour Price Change**
   - Response should contain `price_change_percentage_24h`.

5. ✅ **Homepage URL Validation**
   - The homepage URL should exist and not be empty.

---

## Technologies Used

- [Postman](https://www.postman.com/) – API Testing Tool
- [Newman](https://www.npmjs.com/package/newman) – CLI Runner for Postman
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) – For scripting in Postman tests
- [CoinGecko API](https://www.coingecko.com/en/api/documentation)

---


