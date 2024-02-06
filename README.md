# Trading Session Time With Alert MT5

This code is a custom indicator for MetaTrader 5 (MT5) that displays the trading session times on the chart. It also includes an alert function that can be enabled to notify the trader when a new trading session starts.

## Indicator Settings

The indicator has several input parameters that can be customized:

- **Tokyo_Session**: Set to true to display the Tokyo trading session on the chart.
- **London_Session**: Set to true to display the London trading session on the chart.
- **NewYork_Session**: Set to true to display the New York trading session on the chart.

## Time Zone Offsets

The indicator requires the trader to specify the time zone offsets for each trading session. The default values are set for the Tokyo, London, and New York time zones, but these can be adjusted according to the trader's preference.

## Alert Settings

The indicator includes an alert function that can be enabled or disabled. The alert settings can be customized:

- **Enable_Alerts**: Set to true to enable the alerts.
- **Sound_Alert**: Set to true to play a sound alert when a new trading session starts.
- **Popup_Alert**: Set to true to display a popup alert when a new trading session starts.
- **Email_Alert**: Set to true to send an email alert when a new trading session starts.

## Drawing Indicator

The indicator uses a buffer to draw the session lines on the chart. The session times are calculated based on the time zone offsets specified by the trader. The indicator then converts the session times to the local time of the trading platform.

## Custom Alert Function

The custom alert function is called when a new trading session starts. It checks the alert settings and executes the corresponding actions if enabled. The actions include playing a sound alert, displaying a popup alert, and sending an email alert.

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/trading-session-time-mt5-review-optimize-forex-trades-globally/).
