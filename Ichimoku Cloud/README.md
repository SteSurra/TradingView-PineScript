# <H1> Ichimoku Cloud </H1>

The Ichimoku Cloud is a tool that positioned on the chart provides information on the trend, support and resistance levels and volatility "at a glance".

This information is obtained through three components that make up the Ichimoku Cloud:
1. <ins> historical component </ins>: it compares the current price action with the historical price: the historical component is defined with the name of "Chikou Span" which defines the so-called momentum of the price action, ie the trend. Through this component it is possible to identify support and resistance levels
2. <ins> current component </ins>: it shows the current trend ie what is happening right now. Here we identify the so-called "Tenken sen" and "kijun sen" which are actually variations of simple moving averages.
3. <ins> future component </ins>: the "Senkou A" and "Senkou B" define the so-called cloud which provides an indication of the strength and weakness of the market.
They are often a good indicator for trailing stops.

<ins> Advice </ins>

- Use all three components together
- Use the Ichimoku Cloud together with candlestick patterns

<H3> Cloud </H3>

![etv6ENPQ](https://user-images.githubusercontent.com/57445485/126187865-27c140b4-5515-4d46-85b9-ec0bbfa2a226.png)
![jOw9Ki9r](https://user-images.githubusercontent.com/57445485/126187741-984d36ea-1239-4b47-8496-54ded1e696a5.png)
![pWMH8yHN](https://user-images.githubusercontent.com/57445485/126188878-29142d21-b6bd-44a7-bda7-affe47fd5264.png)


In this implementation, the cloud makes a 56-day (multiple) projection into the future:
1. if the price action (the chart) is above the Cloud the trend is bullish
2. if the price action is below the cloud the trend is bearish
3. in the event that the price action and the cloud are one above the other we have latelarization.

The green line is the Senkou A, the red line is the Senkou B.
The cloud area is green when the Senkou A is above the Senkou B, otherwise it is red.

![R0GM1Nqp](https://user-images.githubusercontent.com/57445485/125323748-6f9df600-e33f-11eb-8cc1-def4d79fc51a.png)

The Ichimoku Cloud indicator has been modified compared to the basic version in order to display Ichimoku Cloud related to different time frames on the same timeframe. This makes it easier to identify resistance and intersection points.

![QUyQt2bj](https://user-images.githubusercontent.com/57445485/125323473-1afa7b00-e33f-11eb-898d-de66acb97b35.png)

By checking the "Cross_X" option, it is also possible to display on the graph only the intersections between the two leadLines always relative to different timeframes on a single timeframe. The green lines indicate a bullish intersection, while the red lines indicate a bearish intersection.
