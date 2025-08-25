*****Please README at https://greasyfork.org/en/scripts/419825-aigpt-everywhere
<br><br><br><br><br><br>
<details>
<summary><strong>How to Install scripts? (Click here)</strong></summary>
<video width="100%" height="50%" src="https://github.com/cyber-sec0/cyber-sec0.github.io/raw/refs/heads/main/Videos/How%20to%20install%20TM%20scripts.mp4"><video>
</details>

<h3><strong>If you like my work, please consider supporting it!</strong> (Cryptos / Patreon / Ko-Fi / BuyMeACoffee https://cyber-sec0.github.io)</h3>

<video width="100%" height="50%" src="https://github.com/cyber-sec0/cyber-sec0.github.io/raw/refs/heads/main/Videos/A.I.%20Everywhere.mp4"></video>
<img src="https://i.imgur.com/koYcwbp.gif">
<img src="https://i.imgur.com/gWp8Z8M.png" alt='https://greasyfork.org/en/scripts/6911-select-like-opera'>

<details>
<summary><strong>How to add my Artificial Intelligence API Key?</strong></summary>
1 Open https://aistudio.google.com/app/apikey
2. Click on "Get API Key."
3. Click on "Create API Key".
4. Click on "Got it."
5. Click on the input button
6. Click on "Generative Language Client."
7. Click on "Create API Key in existing project."
</details>

*The script color theme changes to dark/white mode depending on your browser theme.

<details>
<summary><strong>Future Update Plans</strong></summary>
Add the ability for all users to create custom prompt boxes with stored prompt text, and also add a "summarize page" button as a black dropdown menu when the tab key is pressed.
Add an option to let users choose the API endpoint.
Add an option to let users choose the default AI voice.
Add an option to let users choose the default answer language.
Add a send written prompt BTN on click.
Add an option to let users use only the CSS/JS/HTML site context for website coding questions.
Add a code block with a black background color and a copy code button when the AI response returns codes.
Add support for uploading files to the AI.
Add support to switch between different AIs.
Add ChatGPT.

<strong>Add AI fine-tuning support by letting users adjust all of the following AI parameters:</strong>
System Instructions: Custom directives for guiding the model's behavior.
Stop Sequence: Specifies tokens or sequences where the model should stop generating further output.
Number of Response Candidates: Defines how many different responses the model should generate for a given prompt.
Temperature: Controls the creativity of the model’s responses. Lower values make the model more focused and deterministic, while higher values increase randomness and diversity.
Max Output Tokens: Limits the length of the model's response.
Top-P (Nucleus Sampling): Adjusts the diversity of responses by focusing on the most probable words whose cumulative probability is below a threshold.
Top-K: Restricts sampling to the top K most probable words.
</details>

<details>
<summary>If you use the Opera Browser, please click here and follow the steps below before installing the script.</summary>
1 Copy and Paste this on a new browser tab <strong>opera://settings/?search=Enable+Mouse+Gestures</strong>
2 Turn OFF <strong>Enable Mouse Gestures</strong>.

3 Copy and Paste this on a new browser tab <strong>opera://settings/?search=Enable+the+search+pop-up+when+selecting+text</strong>
4 Turn OFF <strong>The search pop-up when selecting text</strong>.

5 Copy and Paste this on a new browser tab <strong>opera://settings/?search=Enable+Rocker+Gestures</strong>
6 Turn OFF <strong>Enable rocker gestures</strong>.
</details>

<strong>*Click on the bold texts to read.</strong>
You can open the AI prompt box by pressing CTRL + / or Ctrl + Shift + 7. When CTRL + / or Ctrl + Shift + 7 is pressed on a textbox, the textbox text is automatically copied into the AI prompt.

<details>
<summary><h1><center><strong>Mouse Gestures</strong></h1></center></summary>
If you want to modify/disable (or add) the mouse gestures. (Start below the line "const funcs = {" in the script codes.)
<details>
<summary>Here's how to do it.</summary>
L = Means Left.
D = Means Down.
U = Means Up.
R = Means Right.

*You can also adjust the script's mouse sensitivity here between 1 ~ 5
Just change the number 3 below to a number between 1 and 5 in the script codes
const SENSITIVITY = 3;

<strong>If you want to modify the actual mouse gestures</strong> of the script follow this example:
Change this 'L': function() {
to
'LU': function() {

Previously, the right-click + left mouse gesture would Go Back to your browser history. Now,w we've changed it to Left-Click + up, so the right-click + left-up mouse gesture will Go Back to your browser history from now on.

<strong>If you want to disable any of the gestures</strong>, you just need to add 2 slashes "//" in front of all the line codes from
//Function that will run when the mouse movement *** is performed
Till
 //Finishes the mouse movement ***

Example:
//  'R': function() { //Function that will run when the mouse movement Right is performed
//    window.history.forward(); //Go Forward
//  }, //Finishes the mouse movement Right

Before, the right-click+Right mouse gesture would Go Forward your browser history, but now, when you do a right-click+Right mouse gesture, nothing will happen.

<strong>If you want to ADD a new mouse gesture</strong> follow this example:
Copy and paste the 3 lines below the line "const funcs = {" in the script codes, then add the mouse actions or just modify the 'LU' mouse action example below.

  'LU': function() { //Function that will run when the mouse movement Left+Up is performed
    // Here you write the JavaScript/jQuery codes that you want to be executed when the mouse movement Left+Up is performed
  }, //Finishes the mouse movement Left+Up

I may or may not make these modifications easier to do in the future, and install the script so you can be aware of new release updates.
</details>

<br>
<table>
<tbody>
<tr>
<th>Action</th>
<th>Gesture</th>
</tr>
<tr>
<td>Go back one page</td>
<td><img src="https://www-static-sites.operacdn.com/wp-content/uploads/sites/2/2018/02/previous.gif"></td>
<td>Move left</td>
</tr>
<tr>
<td>Go forward one page</td>
<td><img src="https://www-static-sites.operacdn.com/wp-content/uploads/sites/2/2018/02/next.gif"></td>
<td>Move right</td>
</tr>
<tr>
<td>Open a new tab</td>
<td><img src="https://www-static-sites.operacdn.com/wp-content/uploads/sites/2/2018/02/open_new.gif"></td>
<td>Move down</td>
</tr>
<tr>
<td>Reload the page</td>
<td><img src="https://www-static-sites.operacdn.com/wp-content/uploads/sites/2/2018/02/reload.gif"></td>
<td>Move straight up, then straight down</td>
</tr>
<tr>
<td>Close current tab</td>
<td><img src="https://www-static-sites.operacdn.com/wp-content/uploads/sites/2/2018/02/close.gif"></td>
<td>Move down, then right</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th></th>
<th></th>
</tr>
<tr>
<td>Open a link in a background tab</td>
<td><img src="https://www-static-sites.operacdn.com/wp-content/uploads/sites/2/2018/02/upDown.png"></td>
<td>Move straight down, then straight up</td>
</tr>
<tr>
<td>Open a link in a new tab</td>
<td><img src="https://www-static-sites.operacdn.com/wp-content/uploads/sites/2/2018/02/open_new.gif"></td>
<td>Move down</td>
</tr>
<tr>
<td>Open a link in a new window</td>
<td><kbd>Shift ⇧</kbd>&nbsp;+&nbsp;<img src="https://www-static-sites.operacdn.com/wp-content/uploads/sites/2/2018/02/open_new.gif"></td>
<td>Move down, holding shift</td>
</tr>
</tbody>
</table>
</details>

<details>
<summary><h1><center><strong>Rocker Mouse Gestures</h2></strong></h1></center></summary>
<strong>(Disabled by default)

You can go backward and forward through a tab’s history with rocker gestures.</strong>
When you enable rocker gestures, you can navigate backward and forward through pages by rocking your fingers between the right and left mouse buttons. Simply click and hold one button, click the other, then release the first before releasing the second. With a little practice, you can speed through web pages with this gesture.

<strong>Right Click and hold+Left Click to navigate backward, and Left Click and hold+Right Click to navigate forward.</strong>

Note: Enabling rocker gestures while using a Magic Mouse or trackpad can cause unpredictable behavior.

If you want to modify/disable the Rocker mouse gestures. (Start on the line "var LeftClicked, RightClicked;" in the script codes.)
<details>
<summary>Here's how to do it.</summary>
<strong>If you want to disable any of the gestures</strong>, you just need to add 2 slashes "//" in front of all the line codes from
//If *** was Clicked and then *** Click was released
Till
} //Finishes the if condition

Example:
//if (LeftClicked && RightClicked === false) { //If Left was Clicked and then Right Click was released
//      window.history.back(); //Go Back
//    } //Finishes the if condition

Before, if Left was clicked and then Right Click was released, it would navigate forward, but now nothing will happen when Left is clicked and then Right Click is released.

<strong>If you want to modify the actual Rocker mouse gestures</strong> of the script follow this example:
Change this line window.history.back(); to anything you want

Example:
if (LeftClicked && RightClicked === false) { //If Left was Clicked and then Right Click was released
      window.location.reload(); //Reload the Tab
    } //Finishes the if condition

Before, if Left was clicked and then Right Click was released, it would navigate forward, but now, when Left was clicked and then Right Click was released, the tab will reload.
</details>
</details>



<details>
<summary><h1><center><strong>Image Generation</h2></strong></h1></center></summary>
*Click on the image to download it.

<p>Here’s a simple breakdown of valid keywords to trigger the image generation:</p>
<strong>(generate|create|draw|make)</strong> = Must begin with one of these words.
<strong>(me|an?|the|this|that)?</strong> = Optionally followed by one of these words.
Any words after that (space required).
<strong>(at|in|on|of|for|about|showing|depicting|illustrating)</strong> = Must contain one of these before the actual subject.</p>
<p>This matches prompts like:
&quot;generate me a picture of...&quot;
&quot;create the image showing...&quot;
&quot;draw an illustration for...&quot;</p>

You will know that your prompt worked when you see the text "Generating image..." after sending your prompt.

Prompt examples and try out at:
https://regex101.com/r/t2ltmH/1

*For best performance, use the following languages:
• EN: English (Likely a general version, potentially US English if not specified further)
• es-MX: Spanish (Specifically the Mexican dialect)
• ja-JP: Japanese (Japan)
• zh-CN: Chinese (Simplified, as used in mainland China)
• hi-IN: Hindi (India)


*Rate limits: 10 images per minute, 100 images per day.
</details>


<details>
<summary><h1><center><strong>Search HighLight (+ Converters)</h2></strong></h1></center></summary>
<strong>Keep the Search Highlight function enabled to be able to use the converters.</strong>
<strong>The search pop-up tool allows you to search or copy the text you highlight on a web page.</strong> With just one click, your highlighted text opens a new tab and is queried by Google or any search engine of your choice. You can also copy the text to your clipboard to use later on, and you can open non-links as if they were clickable.

If you want to change the default script search engine from Google to another search engine, change the line 'https://www.google.com/search?q=' in the script code.
<details>
<summary>Here's how to do it.</summary>
You just need to change

var LinkfyOrSearch = 'https://www.google.com/search?q='; //Creates a variable to open google

To

var LinkfyOrSearch = 'LINK OF THE SEARCH ENGINE'; //Creates a variable to open THE SEARCH ENGINE YOU WANT

Example:
var LinkfyOrSearch = 'https://duckduckgo.com/?q='; //Creates a variable to open DuckDuckGo


</details>

<strong>Any of the converted values can be copied to your clipboard by hovering your mouse pointer over the conversion and clicking the revealed Copy button. Enjoy browsing made just a little bit easier for you.</strong>

<details>
<summary><h1><center>Time zone Converter</h2></strong></h1></center></summary>
Don’t confuse the start time of something important!

<img height="400" src='https://i.imgur.com/pmwBmsw.png'></a>

https://www.forbes.com/sites/jamiecartereurope/2020/02/14/the-moon-is-about-to-eat-mars-and-some-north-americans-can-feast-their-eyes-on-this-rare-sight/

Need to check what time locally your hometown football club is playing at a 20:00 GMT kickoff while traveling in Moscow? Can’t be late for a 9:00 EST conference call with clients in New York when you’re in Prague? <strong>Highlighting a distant time zone will adjust it to your local time.</strong>

The integrated time zone converter is a simple quality-of-life feature that really comes in handy when you need it. If you’re reading an article online and find an unfamiliar time like 16:20 NST or 4:00 AM EST, <strong>just highlight the time and the time-zone abbreviations (CET, JST) and it will be converted to your local time zone.</strong>

<details>
<summary><h1><center>Time zones Supported</h2></strong></h1></center></summary>
<strong>The script supports 17 different types of time zones that are:</strong>
<table>
<tbody>
<tr>
<td>1.</td>
<td>PST / PDT: Pacific Standard / Daylight Time</td>
<td>4:00 PST</td>
</tr>
<tr>
<td>2.</td>
<td>MST / MDT: Mountain Standard / Daylight Time</td>
<td>7:00pm MDT</td>
</tr>
<tr>
<td>3.</td>
<td>CST / CDT: Central Standard / Daylight Time</td>
<td>2:37am CST</td>
</tr>
<tr>
<td>4.</td>
<td>EST / EDT: Eastern Standard / Daylight Time</td>
<td>20:30 EDT</td>
</tr>
<tr>
<td>5.</td>
<td>AST / ADT: Atlantic Standard Time / Daylight Time</td>
<td>11:35AM AST</td>
</tr>
<tr>
<td>6.</td>
<td>NST / NDT: Newfoundland Standard Time / Daylight Time</td>
<td>3:55 NST</td>
</tr>
<tr>
<td>7.</td>
<td>GMT: Greenwich Mean Time</td>
<td>8:00 GMT</td>
</tr>
<tr>
<td>8.</td>
<td>BST: British Summer Time</td>
<td>12:12 BST</td>
</tr>
<tr>
<td>9.</td>
<td>MET: Middle Europe Time</td>
<td>9:14 MET</td>
</tr>
<tr>
<td>10.</td>
<td>CET / CEST: Central Europe Time / Daylight (Summer) Time</td>
<td>16:33 CEST</td>
</tr>
<tr>
<td>11.</td>
<td>EET / EEST: Eastern European Time / Daylight (Summer) </td>
<td>16:33 EEST</td>
</tr>
<tr>
<td>12.</td>
<td>WET / WEST: Western European Time / Daylight (Summer) </td>
<td>16:33 WET</td>
</tr>
<tr>
<td>13.</td>
<td>JST: Japan Standard Time</td>
<td>23:55 JST</td>
</tr>
<tr>
<td>14.</td>
<td>KST: Korean Standard Time</td>
<td>1:12 KST</td>
</tr>
<tr>
<td>15.</td>
<td>IST: Indian Standard Time</td>
<td>0:00 IST</td>
</tr>
<tr>
<td>16.</td>
<td>MSK: Moscow Standard Time</td>
<td>5:22PM MSK</td>
</tr>
<tr>
<td>17.</td>
<td>PT: Pacific Time</td>
<td>5:22PM PT</td>
</tr>
</tbody>
</table>
</details>
</details>

<details>
<summary><h1><center>Currency Converter</h2></strong></h1></center></summary>
<img src="https://i.imgur.com/koYcwbp.gif">

Highlighted currency conversion helps you keep things simple, with no need to go to a currency converter webpage or do math. The Script will convert foreign currencies like CAD to USD, Euro to Rupee, the British Pound to Japanese Yen, or any popular foreign currency with the current rate of exchange.

The currency converter is especially useful for planning trips, reading international news, online shopping, reading business reports, writing school papers, and anything involving money, which is quite a lot.
<strong>*Foreign exchange rates are always up-to-date.
Just make sure you are highlighting both the number and the currency symbol or abbreviation, like 120.37 GBP, 250 EUR, JPY 702, or 8,089 BTC. Cryptocurrencies are included in the currency converter.</strong>

To select your preferred currency (local currency), which all foreign currencies will be converted into, select any currency, and then a pop-up box will appear so that you can write and press OK to add your local currency.

<details>
<summary><h1><center>Currencies Supported</h2></strong></h1></center></summary>
<strong>The script supports 37 types of currencies that are:</strong>

AUD – Australian Dollar – $71,52 AUD
BCH – Bitcoin Cash – 100 BCH
BGN – Bulgarian Lev – 93,88 BGN, 93.88лв
BRL – Brazilian Reals – 178.46 BRL, R$178,46
BTC – Bitcoin – 200 BTC, 200₿
BYN – Belarusian Ruble – 300 BYN, 300Br
CAD – Canadian dollar – $71.09CAD
CHF – Switzerland Francs – 54,64 CHF, 54.64Fr
CNY – Chinese Yuan – 376.75CNY
CZK – Czech Koruna – 1252,12 CZK, Kč 1,252.12
DKK – Danish Krone – 357.03 DKK
EUR – Euros – €48, 48 EUR
GBP – British Pounds – 43,97 GBP, £43.97
GEL – Georgian Lari – 400 GEL, 400₾
HKD – Hong Kong Dollar – 441,61HKD, HK$ 441.61
HUF – Hungarian Forint – 14559,22 HUF
IDR – Indonesian Rupiah – 752995,06 IDR, 752,995.06 Rp
ILS – Israeli New Shekel – 204,05 ILS, ₪ 204.05
INR – Indian Rupee – 3618,91 INR
JPY – Japanese Yen – 6174,09 JPY, ¥ 6,174.09, 6174.09 円
KRW – South Korean Won – 63899,08 KRW, ₩63,899.08
KZT – Kazakhstani Tenge – 600 KZT, 600₸
LTC – Litecoin – 400 LTC
MXN – Mexican peso – 1000,80 MXN
NOK – Norwegian Krone – 446,36 NOK, 446,36kr
NZD – New Zealand Dollar – 78.10 NZD
PHP – Philippine Peso – 2,890.56 PHP, ₱ 2890,56
PLN – Polish Zloty -205.184 PLN, 205,18zł
RON – Romanian Leu – 220.03 RON, 220,03 lei
RUB – Russian Ruble – 3334,29 RUB, 3334,29₽, 3334.29руб
SEK – Swedish Krona – 457.45 SEK
SGD – Singapore Dollar – 76.84 SGD
THB – Thai Baht – 1879,73 THB, 1879.73฿
TRY – Turkish Lira – 197,48 TRY, 600 YTL, 600₺
UAH – Ukrainian hryvnia – 500 UAH, 500₴
USD – United States Dollar – $56.38, 56,38 USD
ZAR – South African Rand – 746,35 ZAR
</details>
</details>

<details>
<summary><h1><center>Units Converter</h2></strong></h1></center></summary>
<video width="700" height="400" src="https://github.com/cyber-sec0/cyber-sec0.github.io/raw/refs/heads/main/Videos/Units%20Converter.mp4"></video>

<strong>The script also has built-in measurement converters to convert unfamiliar numbers with a simple highlight.</strong>
The Unit Converter tool is an easy-to-use and convenient tool that saves you time and effort.

With this script, there’s no need to search for a conversion webpage, copy/paste the relevant information, and search menus for the right units.
The unit Converter is easy to use and does the work for you, with precise conversions.

How tall, heavy, fast, or far away is that thing you want?
Crafting a seasonal beer for the winter, but don’t know how much 4 oz of yeast is in grams? Unsure if your 20 x 30 cm poster from Paris fits a 10 x 16 in frame from California? Travelling and don’t know how far 258 mi is? A simple highlight of these strange values and times with the script quickly converts them into a familiar form.

The automatic unit of measurement conversion in the script gives you one less thing to worry about. Highlight imperial or metric units, and you will see their counterparts in the pop-up menu. Again, just make sure you are highlighting both the number and the measurement symbol or word, such as 132 lb, 150 pounds, 25kg, 94 mph, 150 kilometers per hour, 21 feet, 10yd, etc. You can also convert Celsius and Fahrenheit. This feature makes it so much easier when you’re planning a trip, doing homework, writing papers, reading about foreign countries, or simply browsing the web.

<details>
<summary><h1><center>Units Supported</h2></strong></h1></center></summary>
<strong>The script supports 27 units of measurement that are:</strong>
Inches
Centimeters
Meters
Feets
Kilograms
Pounds
Ounces
Grams
Fluid ounces
Kilometers per hour
Miles per hour
°C
°F
Milliliters
Liters
Gallons
Yards
Millimeters
Kilometers
Miles
Kilowatts
Mechanical HorsePower
Miles per Gallon
Liters per 100 Kilometers
Liquid Quarts
Foot-Pounds
Newton-Meters

<strong>The conversions are:</strong>

<table cellspacing="0">
<tbody>
<tr>
<td>Inches ⇄ Centimeters</td>
<td>72in, 72″</td>
<td>182.88 cm</td>
</tr>
<tr>
<td>Millimeters ➜ Inches</td>
<td>50mm</td>
<td>1.97in</td>
</tr>
<tr>
<td>Meters ⇄ Feet</td>
<td>6.50 ft</td>
<td>1.98 m</td>
</tr>
<tr>
<td>Yards ➜ Meters</td>
<td>239 yd</td>
<td>218.46 m</td>
</tr>
<tr>
<td>Ounces ⇄ Grams</td>
<td>1.76 oz</td>
<td>49.90 g</td>
</tr>
<tr>
<td>Kilometers ⇄ Miles</td>
<td>60mi</td>
<td>96.54 km</td>
</tr>
<tr>
<td>Kilometers per hour ⇄ Miles per hour</td>
<td>62.14mph</td>
<td>99.98 km/h</td>
</tr>
<tr>
<td>°F ⇄ °C</td>
<td>39°C</td>
<td>102.20°F</td>
</tr>
<tr>
<td>Milliliters ⇄ Fluid ounces</td>
<td>49.98 ml</td>
<td>1.69 fl</td>
</tr>
<tr>
<td>Liters ⇄ Gallons</td>
<td>2.06 gal</td>
<td>7.80 l</td>
</tr>
<tr>
<td>Kilowatts ⇄ Mechanical HorsePower</td>
<td>700kW</td>
<td>938.70 mhp</td>
</tr>
<tr>
<td>Miles per Gallon ⇄ Liters per 100 Kilometers</td>
<td>33.6mpg</td>
<td>7l/100km</td>
</tr>
<tr>
<td>Liquid Quarts ⇄ Liters</td>
<td>4 qt</td>
<td>3.78 l</td>
</tr>
<tr>
<td>Foot-Pounds ⇄ Newton-Meters</td>
<td>250lb ft</td>
<td>338.95 N·m</td>
</tr>
</tbody>
</table>
<br>

For convenience, the script also calculates Math^Power (2^3) numbers.
</details>
</details>
