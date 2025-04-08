# hugo-countdown-shortcode
Javascript countdown timer shortcode for HUGO generated sites.
I needed a countdown for a specific point in time. I found https://github.com/rickosaws/hugo-countdown-shortcode and modified it to fit my needs.

![Countdown Timer](/.images/countdown.png)

The countdown timer contains 2 Messages (Start/End) which can be customised and will hide the countdown elements when it reaches 0.

### Installation
Simply copy the shortcode and JS into the respective HUGO folders and your done. This shortcode is independent of any theme

### Usage
The Shortcode uses the {{< countdown end=`timestamp` headline=`string` endText=`string` >}}. Use a unix seconds timestamp to set the end datetime and optionally a headline for the countdown as well as a message for when its finished.

e.g ```{{< countdown end=1744308000 headline="Countdown" endText="Countdown ended" >}}``` for a countdown to Thu, 10 Apr 2025 18:00:00 GMT with customized headline and end text.
