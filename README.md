# Historical Sales Data Analysis and Visualizations

## Overview

This repository contains a dataset for a Power BI-based data analysis project, developed for a freelance gig seeking insights from historical e-commerce sales data. The goal is to create interactive dashboards to support cross-departmental decision-making, focusing on two key areas: demographics and sales operations. The dashboards will analyze data from four tables (customer, orders, payments, and items) to provide actionable insights.

- **Demographics**: Suggested: Analyzing customer distribution by city, state, and unique customer IDs to understand purchasing patterns.
- **Sales Operations**: Suggested: Evaluating order trends, payment types, shipping performance, and product pricing to optimize operations.

## Repository Content

- `ecommerce_orders.zip`: Dataset containing e-commerce sales data (customer, orders, payments, and items tables).
- `README.md`: This file, providing an overview and instructions.

## Data Description

The dataset consists of four tables, sourced from the Kaggle Brazilian E-commerce Dataset:

### Customer Dataset
| Column Name                | Description                                      |
|----------------------------|--------------------------------------------------|
| `customer_id`              | Unique identifier for the customer                |
| `customer_unique_id`       | Unique identifier for individual customer         |
| `customer_zip_code_prefix` | Zip code prefix of the customer’s location        |
| `customer_city`            | City of the customer                              |
| `customer_state`           | State of the customer                             |

### Order Items Dataset
| Column Name            | Description                                           |
|------------------------|-------------------------------------------------------|
| `order_id`             | Unique identifier for the order                        |
| `order_item_id`        | Identifier for items within an order                   |
| `product_id`           | Unique identifier for the product                      |
| `seller_id`            | Unique identifier for the seller                      |
| `shipping_limit_date`  | Deadline for shipping the order                       |
| `price`                | Price of the item                                     |
| `freight_value`        | Freight cost for the item                             |

### Orders Payments Dataset
| Column Name            | Description                                           |
|------------------------|-------------------------------------------------------|
| `order_id`             | Unique identifier for the order                        |
| `payment_sequential`   | Sequence of payments for the order                    |
| `payment_type`         | Payment method (e.g., credit card, boleto)            |
| `payment_installments` | Number of installments for the payment                |
| `payment_value`        | Total payment value for the order                     |

### Orders Dataset
| Column Name                      | Description                                           |
|----------------------------------|-------------------------------------------------------|
| `order_id`                       | Unique identifier for the order                        |
| `customer_id`                    | Unique identifier for the customer                    |
| `order_status`                   | Status of the order (e.g., delivered, canceled)       |
| `order_purchase_timestamp`       | Timestamp of order purchase                           |
| `order_approved_at`              | Timestamp of order approval                           |
| `order_delivered_carrier_date`   | Date order was handed to the carrier                  |
| `order_delivered_customer_date`  | Date order was delivered to the customer              |
| `order_estimated_delivery_date`  | Estimated delivery date                               |

Dataset can be found at: [ecommerce_orders.zip](https://github.com/taloc/ecommerce_analysis/blob/main/ecommerce_orders.zip)

## Notes

- This dataset is sourced from the Kaggle Brazilian E-commerce Dataset, representing a sample of e-commerce transactions. [Kaggle Brazilian E-commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
- Due to privacy concerns, the dataset is a sample and does not contain sensitive information.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
