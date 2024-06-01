<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Real-Time Forex Chart</title>
    <style>
        #chart-container {
            width: 100%;
            height: 600px;
        }
    </style>
</head>
<body>
    <div id="chart-container"></div>
    <script src="https://s3.tradingview.com/tv.js"></script>
    <script src="script.js"></script>
</body>
</html>
new TradingView.widget({
    "container_id": "chart-container",
    "width": "100%",
    "height": "600",
    "symbol": "FX:EURUSD",
    "interval": "D",
    "timezone": "Etc/UTC",
    "theme": "light",
    "style": "1",
    "locale": "en",
    "toolbar_bg": "#f1f3f6",
    "enable_publishing": false,
    "withdateranges": true,
    "hide_side_toolbar": false,
    "allow_symbol_change": true,
    "save_image": false,
    "studies": [
        "MACD@tv-basicstudies",
        "StochasticRSI@tv-basicstudies",
        "RSI@tv-basicstudies",
        "BollingerBands@tv-basicstudies",
        "Volume@tv-basicstudies"
    ],
    "show_popup_button": true,
    "popup_width": "1000",
    "popup_height": "650",
    "referral_id": "your_referral_id"
});


<!---
coderB32/coderB32 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
