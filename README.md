# **Code Refactor**

## **Goals**

The inspiration for this project was the client's stated need to increase the accessability of thier website using semantic HTML to increase search engine recognition. 
![Screenshot of clients page](assets/images/ClientPage.png)
This also has the added benefit of allowing the application to reach wider audience of users. Along with accessability, testing the application for functionality and eliminating redundancy in the code are areas covered in the brief.

## **Implementation**

Initially, the basic functionality of the application was addressed in checking all the links and images. The first jump link did not have an appropriate ID to the correct location. The ID was added to the HTML, so the link could work.

Next, there was not alternate text for any of the images in the application. Brief descriptions of all photos and logos were added in the event such images could not be loaded on the page. Also these descriptions can be detected by systems any users with disabilities might employ.

The next obsticle was replacing most of the "div" tags in the HTML with semantic tags. These included header, navigation, section, article, aside, and footer tags in the appropriate locations. The general layout of the application was a very standard format, and the semantic tags follow that symmetry.

On the CSS end of things, there was a great deal of redundancy in the code that needed to be addressed. In four instances there were three classes of instructions where only one was needed to accomplish the same goal. The extra code was eliminated, and the remaining class renamed for a more cohisive flow. There were several instances where classes were unnecessarily included in code sets and could be taken out without damaging the aesthetic of the page. All specific changes are messaged in the CSS code. In the reverse, there was code in the footer element of the page meant to shrink that specific text which was not working. This required the introduction of an ID to affect that individual change in text. 

Lastly, the client expressed a need for an appropriate title for the page. After looking at several sites that are in the same and similar fields to the client, "Social Media Marketing Services" was chosen to reflect the client's image. In the absence of smaller symbol, the first letter of the business name was chosen as a flavicon. This liberty was taken in an effort to enhance the presentation of the page.

The end result of these efforts did a great deal toward streamlining the codeing and increasing the accessability of the application without adversely affecting the overall look: [Horiseon](https://geoff7709.github.io/02-homework/)

## **List of Image Files**

* [Brand Awareness](assets/images/brand-awareness.png)
* [Cost Management](assets/images/cost-management,png)
* [Lead Generation](assets/images/lead-generation.png)
* [Online Reputation Management](assets/images/online-reputation-management.jpg)
* [Search Engine Optimization](assets/images/search-engine-optimization.jpg)
* [Social Media Marketing](assets/images/social-media-marketing.jpg)

## **License**

Standard [MIT](https://github.com/Geoff7709/02-homework/blob/main/LICENSE) License





