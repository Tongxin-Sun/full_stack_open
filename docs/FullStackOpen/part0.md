# b. Fundamentals of Web apps

> On macOS, open the Developer Console by pressing fn - F12 or option-cmd-i simultaneously. On Windows or Linux, open the console by pressing Fn - F12 or ctrl-shift-i simultaneously.

Make sure that the _Network_ tab is open, and check the _Disable cache_ option as shown. _Preserve log_ can also be useful (it saves the logs printed by the application when the page is reloaded) as well as "Hide extension URLs" (hides requests of any extensions installed in the browser).

> The "Disable cache" option in the Network tab of browser developer tools, like Chrome DevTools, temporarily disables the browser's HTTP cache for the duration the developer tools are open. This means that when you reload a webpage or navigate to a new one, the browser will fetch resources (like CSS, JavaScript, images) directly from the server instead of serving them from the cache. This is useful during web development to ensure you're always seeing the latest version of your website, especially when making frequent changes to your code.

> To refresh a webpage, on windows, press the Fn - F5 keys. On macOS, press command - R. 

> If you want to loopup a hostname from an IP address, you can use the command `dig -x IP`.

## Traditional web applications

The content of the HTML page has been saved as a **`template string`**.

Writing HTML amid the code is of course not smart, but for old-school PHP programmers, it was a normal practice.

In traditional web applications, the browser is "dumb". It only fetches HTML data from the server, and all application logic is on the server. A server can be created using JavaSpring, Python Flask or Ruby on Rails to name just a few examples.

## Running application logic in the browser

By default, Chromium-based browsers are not too good at displaying JSON data. Plugins can be used to handle the formatting. Install, for example, JSONView on Chrome, and reload the page. The data is now nicely formatted.