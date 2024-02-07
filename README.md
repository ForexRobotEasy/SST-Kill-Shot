# SST Kill Shot Code ReadMe

This code is for the 'SST Kill Shot' expert advisor developed by the Forex Robot Easy team. The official developer's website for this product is [forexroboteasy.com](https://forexroboteasy.com).

## Indicator Initialization
The `OnInit` function is called when the indicator is initialized. You can add any initialization code here. The function should return `INIT_SUCCEEDED` if initialization is successful.

## Expert Initialization
The `OnDeinit` function is called when the expert advisor is deinitialized. You can add any deinitialization code here. The function should return `INIT_SUCCEEDED`.

## Expert Tick Function
The `OnTick` function is the main tick function of the expert advisor. It is called on each tick of the market. In this function, the following steps are performed during the first hour of trading:
1. Identify fair value gaps.
2. Determine if bulls or bears are in control.
3. Place pending market orders in and around the identified fair value gaps.

## Calculate Fair Value Gap
The `CalculateFairValueGap` function calculates the fair value gap. You can add your own calculation code here. The function should return the fair value gap as a double.

## Determine Control
The `DetermineControl` function determines who is in control, bulls or bears, based on the fair value gap. You can add your own determination code here. The function should return `true` if bulls are in control and `false` if bears are in control.

## Place Buy Orders
The `PlaceBuyOrders` function places buy orders in and around the fair value gaps. You can add your own buy order placement code here.

## Place Sell Orders
The `PlaceSellOrders` function places sell orders in and around the fair value gaps. You can add your own sell order placement code here.

## Custom Functions
There are three custom functions defined in the code: `CustomFunction1`, `CustomFunction2`, and `CustomFunction3`. You can add your own custom code in these functions.

Please note that Forex Robot Easy is not the official developer of this product. This is just a sample code provided to demonstrate how the product works. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, you can visit [here](https://forexroboteasy.com/forex-robot-review/sst-kill-shot-review-intra-day-forex-trading-strategy/).
