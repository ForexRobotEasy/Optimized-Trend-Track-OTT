# Optimized Trend Track OTT

This repository contains the code for the Optimized Trend Track (OTT) indicator, developed by Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/ott-forex-software-review-unveiling-trend-tracking-efficiency/).

## Description

The Optimized Trend Track (OTT) indicator is designed to identify and track trends in the financial markets. It calculates the OTT value based on a specified period/length parameter and determines the market trend based on this value. The OTT value represents the average price over the specified period, and the sensitivity of the OTT can be adjusted using the ottPercent parameter.

## Input Parameters

- `period` (default: 14): The period/length parameter used to calculate the OTT value.
- `ottPercent` (default: 0.5): The OTT percent parameter used to adjust the sensitivity of the OTT.

## Indicator Initialization

The `OnInit` function is responsible for initializing the indicator. It sets the short name of the indicator as 'Optimized Trend Track OTT'.

## Indicator Calculation

The `OnCalculate` function is called for each new bar in the chart. It calculates the OTT value, determines the market trend based on the OTT value, adjusts the sensitivity of the OTT, and outputs the result.

The `calculateOTT` function is used to calculate the OTT value based on the specified period/length and the close prices of the bars.

The `determineTrend` function is used to determine the market trend based on the OTT value and the current close price.

## Usage

To use this indicator, simply import it into your MetaTrader platform and apply it to the desired chart. The indicator will then display the market trend based on the OTT value.

Please note that Forex Robot Easy is not the official developer of this product. We are only providing a sample code that can work as described in the official product. To find the official developer of this product, please refer to the MQL5 website.

For more information and detailed reviews of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/ott-forex-software-review-unveiling-trend-tracking-efficiency/).
