# Deploying Pipelines with Snowflake and dbt Labs

## Overview

In this hands-on lab, we will build a data pipeline using Snowflake and dbt to analyze trading P&L across multiple currencies, normalize trade data using FX rates, and compare actual performance against portfolio targets. We will integrate datasets from Snowflake Marketplace (FX rates, US equity price history) and manual sources (trading history, target allocation ratios) to generate insights. Additionally, we will leverage LLMs to extract patterns and sentiment from trader execution notes, helping assess decision-making. By the end of this lab, you will have a working pipeline that blends market and portfolio data, enabling performance assessment and deeper insights into trading behavior.

## Step-By-Step Guide

For prerequisites, environment setup, step-by-step guide and instructions, please refer to the [QuickStart Guide](https://quickstarts.snowflake.com/guide/data_engineering_deploying_pipelines_with_snowflake_and_dbt_labs/index.html).


## 🛠 Core Tech Stack

- **[Snowflake](https://www.snowflake.com/)** – Cloud data platform for scalable, secure data storage and compute
- **[dbt (Data Build Tool)](https://www.getdbt.com/)** – SQL-based transformation and ELT orchestration
- **[Python](https://www.python.org/)** – Environment management and CLI execution via `pipx` or `pip`
- **[Git & GitHub](https://github.com/)** – Version control and collaboration platform
