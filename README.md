# Gold King Pro ReadMe

Gold King Pro is a Forex trading robot developed by the Forex Robot Easy Team. This code represents a simplified version of the Gold King Pro trading algorithm, demonstrating the functionality of its VirtualStopLossModule.

## VirtualStopLossModule

The VirtualStopLossModule is a class that handles the virtual stop loss functionality of the Gold King Pro robot. It allows users to set a virtual stop loss level and check if the current price has hit the stop loss.

### Methods

- `SetVirtualStopLossLevel(double level)`: Sets the virtual stop loss level.
- `GetVirtualStopLossLevel()`: Retrieves the virtual stop loss level.
- `SetCurrentPrice(double price)`: Sets the current price.
- `GetCurrentPrice()`: Retrieves the current price.
- `IsStopLossHit()`: Checks if the stop loss has been hit.

## GoldKingPro

GoldKingPro is the main class of the Gold King Pro robot. It utilizes the VirtualStopLossModule to manage the virtual stop loss functionality.

### Methods

- `SetVirtualStopLoss(double level)`: Sets the virtual stop loss level.
- `GetVirtualStopLoss()`: Retrieves the virtual stop loss level.
- `SetCurrentPrice(double price)`: Sets the current price.
- `GetCurrentPrice()`: Retrieves the current price.
- `Start()`: Starts trading.
- `Stop()`: Stops trading.
- `IsStopLossHit()`: Checks if the stop loss has been hit.

## Usage

The code demonstrates the basic usage of the Gold King Pro robot. It initializes the GoldKingPro object, sets the virtual stop loss level and current price, and checks if the stop loss has been hit. If the stop loss is hit, it stops trading; otherwise, it continues trading.

To use the Gold King Pro robot in an actual trading environment, refer to the official developer of this product using MQL5.

## Disclaimer

Forex Robot Easy is not the official developer of Gold King Pro. This code is provided as a sample and may not reflect the exact functionality of the actual product. For detailed reviews and trading results of Gold King Pro, please visit [Forex Robot Easy - Gold King Pro Review](https://forexroboteasy.com/forex-robot-review/gold-king-pro-mt5-v2-7-review-enhanced-forex-software/). To find the official developer of this product, please use MQL5.
