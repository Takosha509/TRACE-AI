# TRACE AI – Product Arbitrage Agent (Backend)

## Overview

TRACE AI helps you discover the best products to buy and resell for profit. It fetches deals from Walmart (mocked), analyzes resale potential across eBay, Alibaba, AliExpress, Walmart, and Target (mocked), and recommends opportunities via a simple API.

## Endpoints

- `/products/on-sale`: List products on sale at Walmart (mocked).
- `/market/analyze?product_id=wm1&market=ebay`: Analyze a product's resale market in a given marketplace.
- `/recommendations?markets=ebay,alibaba,aliexpress,walmart,target&limit=10`: Get top arbitrage recommendations across multiple markets.

## Quickstart

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

Then open [http://localhost:8000/docs](http://localhost:8000/docs) for the interactive API docs.

---

*Replace mocked data and functions with real APIs for production use!*