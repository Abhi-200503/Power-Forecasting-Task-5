# Power Consumption Forecasting – Task 5

## Task Objective

Design prompts for telemetry queries and forecast explanations.

## Overview

This task focuses on designing natural-language prompts that allow users to interact with grid telemetry data and understand power-consumption forecasts using simple questions.

## Telemetry Query Prompts

The prompt design supports queries related to:

- Average power consumption
- Peak power consumption
- Minimum power consumption
- Recent power readings
- Top consumption readings
- Historical power consumption
- Consumption at a specific time
- Number of available records

### Example Queries

- What is the average power consumption?
- What was the peak power consumption?
- What is the minimum power consumption?
- Show the last 10 readings.
- Show the top 10 peak readings.
- What is the average consumption at 5 PM?
- How many records are available?

## Forecast Explanation Prompts

Prompts are also designed to help users understand forecast results.

### Example Forecast Questions

- What is the predicted average consumption?
- What is the predicted peak consumption?
- What is the predicted minimum consumption?
- Show the next 24-hour forecast.
- Which forecasting model is being used?
- How accurate is the forecasting model?
- Explain the forecast results.

## Prompt Design Approach

The prompts are designed using simple natural-language questions so that grid operators can retrieve telemetry information without needing to write SQL queries or Python code.

The interface identifies the user's question and provides the relevant telemetry or forecast information.

## Prompt Categories

| Category | Example |
|---|---|
| Historical Data | What is the average power consumption? |
| Peak Analysis | What was the peak consumption? |
| Recent Data | Show the last 10 readings. |
| Forecast | What is the predicted average consumption? |
| Forecast Statistics | What is the predicted peak? |
| Model Information | Which forecasting models are used? |
| Model Performance | How accurate is the model? |

## Project File

```text
docs/
└── telemetry_query_prompts.md
