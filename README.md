**Web Africa** one page website template assesment.

### Task 1

Convert “WebAfrica_Web_Design_960.psd” 

### Task 2

 Implement basic Google maps page.

 ### Task 3
 Webafrica Website Review
![Website brief audit](http://creativescene.co.za/webafrica/webafrica-audit.png)
 
1. Firstly reduce website speed load time currently sitting at 6.4sec complete load time.Website has total of 84 Request.
- This page has 29 external Javascript scripts & 7 external stylesheets . By combining scripts together and stylesheets together could lower amount of HTTP request and speed up load time.
- There are 18 static components  without far-future expiration date that could have expired headers added to it for giving returning users much quicker response time.
- These 4 static components could be added to a cdn for much quick response
    https://wchat.freshchat.com/js/widget.js
    https://widget.flowxo.com/embed.js
    https://widget.flowxo.com/widget.dll.js
    https://widget.flowxo.com/widget.js
- These files require minfication  css/js
    https://www.webafrica.co.za/wa-front-res/js/promo-explosive-fibre-freebies/promo-home.js?v=12-07-2018
    https://www.webafrica.co.za/wa-front-res/js/connectivity-1-map.js?v=10-17-2018
    https://www.webafrica.co.za/wa-front-res/js/connectivity-vox.js?v=05-03-2019
- There are 9 images that could be deferred and perhaps lazy loaded when needed, this could save loading time by 1.9sec.
- There is a saving of 0.9sec to be made on css/js rules that are not in use and only consume network activity
2. Main header logo needs replacing with an svg with high res png fallback as well as all other selling point images everything seems very low res needs to be retina ready ready,basically needs to x2 the size of its intent,  current logo and one selling point image also seems cropped, Good quality images form part of selling point conversation as it entices the user more to engage with your product especially for the ones that are not fond of reading.
3. Updating header- combining the main and sub header and enticing user with a current special happening so on page load the user will already be interested by the promo currently running. Perhaps even personalizing that promo with showing the users current location, fibre ready availability or fastest adsl capability and the best available promo. Psychologically making the user feel more welcome due to the fact that web africa knows bit more about your current internet situation and wants to give you better experience.
4. Utilizing color scheme better: this one speaks a bit more to the target market as with my experience men and women share different taste in color satisfaction and conversion in my opinion i would almost making blue my primary colour as it cultivates the users trust more speaks to loyalty second to that would be white and speaking more in terms of white space in order to create a sense of freedom, spaciousness, and breath-ability. as a tertiary colour i use black as it adds a sense of luxury and value, Black used correctly could indicate exclusivity. For buttons i would use bright primary colours as the highest converting colors for calls to action are bright primary and secondary colors – red, green, orange, yellow.
5. Changing the font from 'Poppins(currently ranked 15th) / Muli(currently ranked 21st)' to ether Open sans or Roboto would already uplift the website by 50% visually, Reasons for using these are they are the currently best-performing web fonts for body text, as it’s very low in what they call ‘visual noise’ ,it doesn’t have an obtrusive texture, dark patches or rendering issues. It’s just a beautifully clear and well-balanced typeface.
6. Make the fibre package carousel (fibre page) auto scroll, i did not even notice that it was carousel due to the large amounts of blue being used in that section, the carousel navigation buttons seem to be competing with the many info popover icons and the floating chat button.
7. Streamline the sections that have many info icons, some list items dont require explaining as the title is self explanatory. These sections just seem to overcrowded with info popovers
8. Apply more consistency with buttons, some have hover states others dont as well as border radius's also lack in consistency,Text & icon within buttons seem bit squashed so applying some more padding should give it the relevant even breathing space. 
9. Include more interactive elements such as subtle animations on hover and click, eg: on mobile animate the burger menu to the 'x', Also perhaps a interactive Infographic, those are a fantastic tools to show an idea or how something works.
10. Upon inspecting the layout i found the class naming convention is self explanatory easy to figure however to improve on this i possibly would introduce the BEM or SMACS naming convention as it makes your code scale able and modular, thus increasing productivity and facilitating teamwork for more info on this http://getbem.com/ or http://smacss.com/.
11. Upon inspecting the fibre/adsl/lte map locator on home page i noticed the colour codes for the network service don't match up, eg: fibre being purple on the map doesn't indicate its purple on the right side or check box. I would indicate the various color codes for the services available as the user might not notice this.

### Basic Usage

After downloading, run **'npm start'** in the root of the project, It should run all tasks and spin up a web sevrer with the project template
You must have **npm** and **Gulp** installed globally on your machine in order to use these features.

## Preview
**[View Live Preview](http://creativescene.co.za/webafrica/)**
![Web Africa psd preview](http://creativescene.co.za/webafrica/WebAfrica_Web_Design_960.jpg)
