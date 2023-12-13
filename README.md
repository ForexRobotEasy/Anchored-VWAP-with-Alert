# Anchored VWAP with Alert

## Description
This code is for a custom indicator called Anchored VWAP (Volume-Weighted Average Price) with Alert. It is developed by Forex Robot Easy Team and can be used for professional trading purposes. The code calculates the VWAP based on the volume and price data of the current symbol and period. It also allows for customizable alert levels and VWAP lines.

## Features
- Customizable Alert Levels: The code allows users to set three alert levels (AlertLevel1, AlertLevel2, AlertLevel3) based on price levels. Whenever the price reaches these levels, an alert will be triggered.
- Customizable AVWAP Lines: Users can set six AVWAP lines (AVWAPLine1, AVWAPLine2, AVWAPLine3, AVWAPLine4, AVWAPLine5, AVWAPLine6) to be displayed on the chart. These lines represent different price levels based on the VWAP calculation.
- Alert Function: The code includes a function called CheckAlert(), which checks if the price has reached any of the alert levels and triggers an alert if it has.
- AVWAP Lines Function: The DrawAVWAPLines() function creates horizontal lines on the chart representing the AVWAP lines set by the user.
- VWAP Calculation Algorithm: The CalculateVWAP() function calculates the VWAP based on the volume and price data of the current symbol and period. It uses a loop to iterate through the bars and calculates the total volume and total price volume. The VWAP is then calculated as the total price volume divided by the total volume.
- Alert Check Function: The CheckVWAPAlert() function calculates the VWAP using the CalculateVWAP() function and checks if any alert levels have been reached using the CheckAlert() function.
- User Interface: The code includes an OnChartEvent() function that handles the event when an object on the chart is clicked. It checks which AVWAP line was clicked and triggers an alert accordingly.
- Code Delivery: The OnDeinit() function deletes all the AVWAP lines when the indicator is removed from the chart.

## Product Description
Anchored VWAP with Alert is a powerful Forex software developed by the Forex Robot Easy Team. It is designed for professional traders who want to use the Volume-Weighted Average Price (VWAP) indicator in their trading strategy. The indicator calculates the VWAP based on the volume and price data of the current symbol and period. It also allows users to set customizable alert levels and display AVWAP lines on the chart.

With Anchored VWAP with Alert, traders can set alert levels to be notified when the price reaches certain levels. This can help them identify potential trading opportunities or monitor price movements. The indicator also provides the ability to display AVWAP lines on the chart, which represent different price levels based on the VWAP calculation. Traders can use these lines as reference points for their trading decisions.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates how the product works. For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Anchored VWAP with Alert Review](https://forexroboteasy.com/forex-robot-review/review-anchored-vwap-with-alert-a-powerful-forex-software-for-professional-traders/). To find the official developer of this product, please refer to MQL5.
