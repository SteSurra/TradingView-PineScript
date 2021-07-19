# <H1> Ichimoku Cloud </H1>

The Ichimoku Cloud is a tool that positioned on the chart provides information on the trend, support and resistance levels and volatility "at a glance".

This information is obtained through three components that make up the Ichimoku Cloud:
1. <ins> historical component </ins>: it compares the current price action with the historical price: the historical component is defined with the name of "Chikou Span" which defines the so-called momentum of the price action, ie the trend. Through this component it is possible to identify support and resistance levels
2. <ins> current component </ins>: it shows the current trend ie what is happening right now. Here we identify the so-called "Tenken sen" and "kijun sen" which are actually variations of simple moving averages.
3. <ins> future component </ins>: Senkou A and Senkou B define the so-called cloud which provides an indication of the strength and weakness of the market.
They are often a good indicator for trailing stops.

<ins> Advice </ins>

- Use all three components together
- Use the Ichimoku Cloud together with candlestick patterns

<H2> Cloud </H2>

In this implementation the cloud makes a 56-day (multiple) projection into the future:

1. if the price action is above the Cloud the trend is bullish

![etv6ENPQ](https://user-images.githubusercontent.com/57445485/126187865-27c140b4-5515-4d46-85b9-ec0bbfa2a226.png)

2. if the price action is below the cloud the trend is bearish

![jOw9Ki9r](https://user-images.githubusercontent.com/57445485/126187741-984d36ea-1239-4b47-8496-54ded1e696a5.png)

3. if the the price action and the cloud are one above the other we have latelarization.

![pWMH8yHN](https://user-images.githubusercontent.com/57445485/126188878-29142d21-b6bd-44a7-bda7-affe47fd5264.png)

The cloud area is green when the Senkou A (green line) is above the Senkou B (red line), otherwise it is red.

<h3> Supports and Resistances </h3>

Senkou B identifies what could be resistance or support in the future. The longer (horizontal) the Senkou B, the greater the indication of support or resistance that the SenkouB itself provides. For this reason Senkou B is excellent for trailing stop.

![fM3H7EWz](https://user-images.githubusercontent.com/57445485/126191763-4c00376f-8331-4a4a-a4c1-64b9840be2c8.png)

<h3> Crossings </h3>

When Senkou A and Senkou B cross this indicates that the market may change its direction in one direction or another; usually Senkou A crosses Senkou B the crossing is bullish, otherwise it is bearish.

![qexYafs8](https://user-images.githubusercontent.com/57445485/126193859-0dd51cd0-0470-4bbf-aa1b-d0a43d3f13ee.png)

By checking the "Cross_X" option, it is also possible to display on the graph only the intersections between the two leadLines always relative to different timeframes on a single timeframe. The green lines indicate a bullish intersection, while the red lines indicate a bearish intersection.

![QUyQt2bj](https://user-images.githubusercontent.com/57445485/125323473-1afa7b00-e33f-11eb-898d-de66acb97b35.png)

<H3> Cloud width </H3>

When the clouds are very large, a price reversal is unlikely (thick).

![mtnLFZ5T](https://user-images.githubusercontent.com/57445485/126195632-fb9870be-122d-466d-a636-7dc88433f895.png)

Usually the thinner they are, the more likely it is to change direction (thin).

![afxb81Ff](https://user-images.githubusercontent.com/57445485/126195653-a9ec44e4-795a-4133-bafa-d361defc0102.png)

<H3> Bullish </H3>

Senkou A | Senkou B
------------ | -------------
High | High | +++
High | Flat | ++
Down | Flat | +

![jfSRRZT0](https://user-images.githubusercontent.com/57445485/126212307-cd6bdc7a-b41e-4bf8-953c-f08581aa5add.png)

![bjW5t7ct](https://user-images.githubusercontent.com/57445485/126212836-abe2a427-792c-4e37-ad42-1eeb222c17e7.png)

![O7Z6fJyI](https://user-images.githubusercontent.com/57445485/126213329-8e2e0eb7-0e48-4316-b349-9ea48a7e06c7.png)

<H3> Bearish </H3>

Senkou A | Senkou B
------------ | -------------
Down | Down | +++
Down | Flat | ++
Up | Flat | +

![kpfb3GWU](https://user-images.githubusercontent.com/57445485/126214508-50670f74-26c4-4098-a27f-c7f1ad04ad28.png)

![d45q9M6Z](https://user-images.githubusercontent.com/57445485/126214021-96eabb37-1fcf-4590-948c-a706f1784bff.png)

![vs46rj5x](https://user-images.githubusercontent.com/57445485/126214272-7caeaae4-a016-48cf-b795-ad64a0f10981.png)

<H3> Updates <H3>

The Ichimoku Cloud tool has been modified compared to the basic version in order to display Ichimoku Cloud related to different time frames on the same timeframe. This makes it easier to identify resistance and intersection points.

![R0GM1Nqp](https://user-images.githubusercontent.com/57445485/125323748-6f9df600-e33f-11eb-8cc1-def4d79fc51a.png)








