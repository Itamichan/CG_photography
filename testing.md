# Testing

## DevTools

In order to test the responsiveness of the web page the Google Chrome DevTools were used extensively.

I added media query for font size and image size in order to ensure their proper size and placement on different screen sizes.

All main sections were put in Bootstrap containers in order to have easy flow of column on different screen sizes.

The DevTools were used the most extensively from all types of testing. They allowed to identify cases of less responsive parts of the web page. In the same, time they allowed to quickly try different solutions and see how the page responds to them.

As a result the web page looks good on all devices, such as mobile, tablet or desktop.

## Manual Testing

In order to ensure that all links are working correctly a manual testing was performed.

As a result several dead links were found and updated.

Manual testing was also used to see the flow and intuitiveness of the content placement.

## User testing

At the point when the web page was 95% done I put the link to the live web page on #peer-code-review channel on Slack as well I sent it to several friends and acquaintances.

### #peer-code-review

The general feedback was that the web page looks good, with a nice layout and scheme.

#### Suggested improvements:

* Add more comments to the project - implemented.
* Change the title of the index page from "Home" to "CGphotography" - implemented.
* At the moment of the peer-code-review assessment the README.md was not done yet so I received multiple, helpful suggestions regarding the topic. - all taken into consideration.

### User review

The general feedback was positive. The web page was identified as well structured and good looking.

#### Identified problems:

* Some users didn't realise that the individual portfolios (with the name of the couple on them) were clickable. The users were using the page in desktop view. For desktop view the portfolio image has `:hover {transform: scale(1.05)}` as property.
    * The identifies problem will be addressed in a future release.