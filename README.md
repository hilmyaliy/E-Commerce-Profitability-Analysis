# E-Commerce Profitability Analysis

## Project Overview
This project analyzes e-commerce performance across product categories, sales channels, returns, and marketing spend to identify the main drivers of profitability and provide actionable business recommendations.

## Dataset
| File | Description |
|------|-------------|
| `orders.csv` | Transaction-level order data |
| `products.csv` | Product details and costs |
| `marketing_spend.csv` | Marketing performance by platform and month |

## Key Business Questions
1. Which product categories have the highest profit margin?
2. Which sales channels are the most profitable after platform fees?
3. How much revenue is lost due to returns?
4. Which marketing platform has the best ROAS?
5. Where should the company cut 20% of the marketing budget?

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Key Findings
| Area | Insight |
|------|---------|
| Product Category | Electronics has the highest average profit margin |
| Product Category | Books has the lowest average profit margin |
| Sales Channel | Mobile App has the best profit per order |
| Sales Channel | Marketplace has the weakest profitability after platform fees |
| Marketing | TikTok Ads and Influencer deliver the strongest ROAS |
| Marketing | Email Marketing has the lowest ROAS, though engagement quality remains promising |

## Recommendations
1. Focus on high-margin categories such as Electronics and Toys.
2. Improve Marketplace profitability by reducing fee-heavy transactions.
3. Reallocate marketing budget away from lower-ROAS platforms and optimize Email Marketing instead of removing it entirely.

## Repository Structure
```bash
.
├── Analysis-Result.ipynb
├── orders.csv
├── products.csv
├── marketing_spend.csv
└── README.md