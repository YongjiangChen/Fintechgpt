
# This is a demo of FinGPT-Forecaster.

FinGPT-Forecaster takes random market news and optional basic financials related to the specified company from the past few weeks as input and responds with the company's **positive developments** and **potential concerns**. Then it gives out a **prediction** of stock price movement for the coming week and its **analysis** summary.

This model is finetuned on Llama2-7b-chat-hf with LoRA on the past year's DOW30 market data. Inference in this demo uses fp16 and **welcomes any ticker symbol**.

Company profile & Market news & Basic financials & Stock prices are retrieved using **yfinance & finnhub**.




