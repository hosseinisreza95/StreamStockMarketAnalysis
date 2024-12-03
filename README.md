# **Real-Time Stock Market Analysis Using Apache Spark**

## **Overview**

This project demonstrates real-time stock market analysis using Apache Spark. The system processes live stock data streams, allowing us to track market trends, monitor price changes, and detect significant losses or gains in stocks over time.

## **Key Features**

- **Total Market Assets**: Aggregates the total stock value over time intervals.
- **Identifying Price Drops**: Flags stocks with significant price losses between consecutive windows.
- **Highlighting Price Gains**: Identifies stocks showing consistent price increases over a period.

## **Technologies Used**

- **Apache Spark (v3.5.0)**
- **PySpark**
- **Kafka** (for real-time streaming, optional)
- **Python (v3.8+)**

## **Setup and Instructions**

### **Prerequisites**

1. Install Apache Spark and Kafka (optional for streaming).
2. Install the required Python libraries:

```bash
pip install pyspark
