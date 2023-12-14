# Di Napoli Thrust Scanner MT5

This is the code for the Di Napoli Thrust Scanner MT5 indicator, developed by the Forex Robot Easy Team. This indicator scans for the Di Napoli thrust pattern in the market and provides alerts when the pattern is detected.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Review Di Napoli Thrust Scanner MT5](https://forexroboteasy.com/forex-robot-review/review-di-napoli-thrust-scanner-mt5-a-powerful-forex-software-for-market-analysis/).

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use the MQL5 platform.

## Indicator Input Parameters

- `displacement`: Number of bars required above or below the displacement.

## Indicator Initialization Function

The `OnInit()` function is called when the indicator is initialized. In this function, the indicator's short name is set.

## Custom Function to Scan for Di Napoli Thrust Pattern

The `ScanForDiNapoliThrustPattern()` function is a custom function that scans for the Di Napoli thrust pattern. It loops through all required timeframes and calculates the Di Napoli thrust pattern using the Bears Power and Bulls Power indicators. If the thrust pattern is detected, it prints the result.

## Expert Initialization Function

The `OnInit()` function is also called when the expert advisor is initialized. In this function, the expert advisor's short name is set.

## Expert Tick Function

The `OnTick()` function is called on each tick of the market. In this function, the `ScanForDiNapoliThrustPattern()` function is called to scan for the Di Napoli thrust pattern.

## Expert Deinitialization Function

The `OnDeinit()` function is called when the expert advisor is deinitialized. In this function, necessary cleanup operations can be performed.

For more information and detailed usage instructions, please refer to the official developer of this product using the MQL5 platform.
