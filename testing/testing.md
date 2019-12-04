# Testing

[back to README.md file](../README.md)

## Table of Content

1. [DevTools](#devtools)
2. [Manual Testing](#manual-testing)
3. [User testing](#user-testing)
    * [Peer-code-review](#peer-code-review)
    * [User review](#user-review)
4. [Google Analytics](#google-analytics)
5. [Hotjar](#hotjar)
    * [Heatmaps](#heatmaps)
    * [Recordings](#recordings)
[PageSpeed Insights](#pagespeed-insights)


## DevTools

Was used for:
* Testing the responsiveness of the web page.
    * As an outcome I added media query for font size and image size in order to ensure their proper size and placement on different screen sizes.
    * All main sections were put in Bootstrap containers in order to have easy flow of columns on different screen sizes.
* Debugging - which allowed to identify incorrect use of bootstrap or CSS. 

As a result the web page looks good on all devices, such as mobile, tablet and desktop.

## Manual Testing

Was used for:
* To test links functionality. As a result several dead links were found and updated.
* To assess the flow and intuitiveness of the content placement.
* To see web page's performance in different browsers, such as Chrome, Firefox and Safari.

## User testing

At the point when the web page was 95% done I put the link to the live web page on #peer-code-review channel on Slack. In the same time I sent it to several friends and acquaintances.

### Peer-code-review

The general feedback was that the web page looks good, with a nice layout and scheme.

#### Suggested improvements:

* Add more comments to the project - implemented.
* Change the title of the index page from "Home" to "CGphotography" - implemented.
* At the moment of the peer-code-review assessment the README.md was not done yet so I received multiple, helpful suggestions regarding the topic - all taken into consideration.

### User review

The general feedback was positive. The web page was identified as well structured and good looking.

#### Identified problems:

* Some users didn't realise that the individual portfolios (with the name of the couple on them) were clickable. The users were using the page in desktop view. For desktop view the portfolio image has `:hover {transform: scale(1.05)}` as property.
    * The identified problem will be addressed in a future release.

## Google Analytics

In order to address issue #7, Google Analytics plugin was added to the project before the live link was shared with #peer-code-review and other users.

Google Analytics is a great tool to get more information about what devices/ browsers users are using.

This information can be used for future prioritization of features implementation.

### Obtained data

* Top used device: Desktop (68.2%).
* Top visited page: /CG_photography/index.html (89 views).
* Top used desktop browser: Chrome (62.07%).
* Top operating system for desktop: Windows (35.48%).
* Top operating system for mobile: Android (61.54%).

Access the [link](images/google-analytics) to see the screenshots of the obtained data.

### Conclusion

From the gathered data we can conclude that for future releases we need to keep in mind  that our users primarily use such browsers as Chrome and Firefox. As well, as that they prefer desktop to mobiles.

The conclusion should be perceived with skepticism considering that at the moment only 29 new users visited the web page.

## Hotjar

As well as Google Analytics, Hotjar was added in order to track user behaviour.

Hotjar provides heatmaps and recordings of user behaviour. Such information is very useful for identification of user confusions and their elimination.

### Obtained data

#### Heatmaps

* Desktop - accessed 59 times
    * 100% of users sees the hero image and the contact button on top of it on the landing page.
    * Only 48% of users reaches the contact button at the bottom of the landing page.
    * The navigation items are highly used.
    * 5.66% users clicked on the reviews columns.
* Mobile - accessed 23 times
    * 100% of users sees the hero image and the contact button on top of it on the landing page.
    * 65.2% of users reaches the contact button at the bottom of the landing page.
    * 15.38% of users clicked on the menu burger.
    
#### Recordings

* Users don't seem to have problems to navigate through different pages.
* The navigation bar is extensively used both for desktop and mobile view.

Access the [link](images/hotjar) to see the screenshots of the obtained data.

#### Conclusion

* Heatmaps
    * It was a good decision to have a Contact button at the beginning of the landing page even though it exists at the bottom as well.
    * Some users seem to assume that the reviews are clickable - could link the reviews to the relevant portfolios in a future release.
* Recordings
    * The web page has an intuitive, easy design.
    
The conclusion should be perceived with skepticism considering that it is based only on a small number of recordings.

## PageSpeed Insights

**Initial loading speed of the web page:**
* On mobile - 92
* On desktop - 99

**Opportunities for improvement:**
* Serve images in next-gen formats - which will save 0.36s loading time
* Efficiently encode images - which will save 0.16s loading time.

Identified images are the ones which serve as cover images and which size was not reduced in order to ensure that they look good on big screens too.

In order to improve the speed I used tinyjpg.com in order to apply compression on my hero images. After the reload of the page most of the images looked good except one (couple-carousel.jpg). This image was restored to its initial size.
    
**Speed after the compression of hero images:**
* On mobile - 96
* On desktop - 99

The compression of images allowed to increase of speed on mobile. Additionally, this means that the user will spend less mobile data on loading the content of the page.

After additional manual checking of the page load speed I noticed that on desktop you can notice how the images in the gallery a loading.

Therefore, I decided to run the gallery images through tinyjpg.com as well.

**Speed after the compression of gallery images:**
* On mobile - 96
* On desktop - 99

The compression didn't make a visible change. Therefore, in a future release the photographs in the gallery should load in a consecutive manner, maybe with some animation in order to look smooth.