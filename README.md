# Gerties Bakeshop

## Demo
A live demo of the finished project can be found [here](https://francesjgonzales.github.io/gertiesfinal/).

![Desktop Demo](../gertiesfinal/readme/gerties.gif)

---

## Aim
My aunt is running a bakeshop called **Gerties** for 20 years now. To get her shop up to date, her son set up a Facebook and Instagram accounts to extend their customer reach. I googled their shop and under Questions and Answers there were 3 questions asking for product price list and delivery.

I'm proposing a website for them so they can reach out to potential new customers and hope to increase audience likes and engagement in their Facebook and Instagram. 

---
## UX
### Research and Strategy
#### Stakeholder information:

1. Gerties' [Facebook](https://www.facebook.com/GertiesBakeshopFastfood/), [Instagram](https://www.instagram.com/gertiesph/) & [Tripadvisor](https://www.tripadvisor.com.sg/Restaurant_Review-g298458-d16710720-Reviews-Gertie_s_Bakeshop_Fastfood-Tarlac_Tarlac_Province_Central_Luzon_Region_Luzon.html) accounts. 
2. [Google](readme/gerties-google.png) reviews & questions and answers.
3. Competitor's facebook account - [@CindysBakeryRestaurant](https://www.facebook.com/CindysBakeryRestaurant/?ref=py_c)

#### I found out that:

1. Competitor has a website with a high number of followers.
2. Enquiries from Gerties' social media accounts & google are based on pricelists and delivery.
3. Information awareness is limited to per enquiry basis and no standard template.

#### Scope

1. External user’s goal: The users are new and existing customers who wants to get promotions, updates and possibly book for delivery or catering.
2. Site owner’s goal: The owner is interested in maintaining existing customers and attracting new customers*.
3. Potential features to include: to showcase product photos, menus, delivery, and information about the company.
4. User goal: make them go to delivery or contact page for enquiry.

#### Structure

I gathered key information that will be used for wireframing. This helped me out in organising and labeling the content efficiently to the users. Click here for your reference.

For wireframing, I used keynote for taking down notes for research, information architecture and creating low-fidelity mockup and Adobe XD for medium-fidelity mockup . This tool helped me when exporting assets to web-friendly sizes.

**Low-fidelity mockup**
![low-fidelity](../gertiesfinal/readme/low-fidelity-mockup.jpg)

**Medium-fidelity mockup**
![medium-fidelity](../gertiesfinal/readme/midfidelity-mockup.jpg)

#### UI

Based on their current logo (refer to this link), the colours are yellow, red and lime green. I wanted to propose a whole new look of Gerties by focusing on the name, toning down the red and limiting the colours to be just red and dark grey for simplicity and clean look.*

1. For fonts, I used open sans, helvetica & sans-serif font for clear & easy readability.*
2. The landing page will have 3 sections - Cakes and Pastries, All day menu & Delivery. Using a 12-col layout, I can maximise the space by applying 2-4col images and texts. 
3. I'm using form for users to send in their enquiries and orders. 
4. Under each sections, there will be 3-col of thumbnail product image and information. Since the user goal to make them go tp delivery and contact page, I will add an 'Order Here' text that links to the contact page. 
5. There will be carousel images to highlight Gerties latest promotions. 
6. I will also add links to their social media accounts. 
7. Instagram feed is also added at the bottom of the website after contacts page. This will help increase followers. 
8. This will be responsive for easy accessibility.

---

## Features

#### The website will feature the following:

1. Landing page has responsive nav buttons like Home, Menu, Delivery, Contact pages
   1. About us - a paragraph form of their history and what they do.
   2. Carousel - showcase latet promotion 
   3. Delivery - showing address, contact information and enquiry form.
2. Menu page - Hero image with short description on top of page. After that, there will be 3-col thumbnail photos and product details. 
   1. Cakes and Pastries
   2. All day menu - breakfast, lunch, snacks, & dinner.
3. Delivery page - form that consist of name, contact, & a 3-row text area for enquiries and orders.
4. Contact page - includes location map, address, contact details and social media icons.
5. Carousel - will have a fade transition accompanied by headline and subtext describing the photos.
6. Order now buttons - when hovered it will change to black and when clicked, it will change to white.
 

#### Future implementation

- Shopping cart - for users to place orders.
- Payment gateway - to support shopping cart. 
- Pop-up version showing detailed information of each product when they click the product image or *Order now button.
- Pop up chat - for urgent response and faster enquiry. 


#### Features Left to Implement
- Enhance animation
- Product gallery


#### Technologies Used

List of tools I used for this website:
- [Getbootstrap](https://getbootstrap.com/)
   + The project uses **getbootstrap** to make the site responsive.
- [Fontawesome](https://fontawesome.com/) 
   + The project uses **fontawesome** to add icons for contact and footer pages.
- [Powr.io](https://www.powr.io/) 
   + The project uses **powr.io** to get more followers in shop's instagram account.
- [Bootstrap’sJavaScript](https://getbootstrap.com/)
   + The project uses **Bootstrap's Javascript** to make animation work in carousel.
- [JQuery]
- [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#emphasis)
   + The project uses **MarkdownCheatsheet** as quick reference for documenting readme file.
- [Keynote]
   + The project uses **Keynote** as UX research tool for documenting stakeholder's background, information architecture and low-fidelity mock up.
- [AdobeXD](https://www.adobe.com/sea/products/xd.html)
   + The project uses **AdobeXD** as wireframing tool for creating medium-fidelity mock up and converting images for web.
- [HTML5] For consistent rendering in every browser.
- [LanguageAttribute] For translation tools to determine what rules to use.
- [CSS3]
- [MediaQuery] Added breakpoints for parts of the design that is different. 
- [Illustrator] For tracing Gertie's logo.
 
---

## Testing
I shared the repository link to my family and Aunt Gertie to ask her consent in using the photo. 

I used [**getsitecontrol**](https://getsitecontrol.com/p/mqknmm2q) as reference for my questions after they used the website. The questions are:
1. Did you find you were looking for? Yes or No
   - Google
   - Facebook
   - Instagram
   - Referred by a friend
2. Is there anything I should improve?

The feedbacks were they want to see more of the menu list so I have to adjust the menu page from thumbnails of each product to column list where each column represents breakfast, lunch & dinner, cakes & pastries & snacks. 

Aside from the adjustment, I noticed that my width is not aligned properly because when I'm scrolling sideways, I see an extra gap. I debugged it by creating a new index.html and going through the process and setting my codes according to their syntax. The site is not aligned properly when I made the width at 100% or not specifying specific measurements to it. 

---

## Deployment
I used Visual Studio Code to work on my code locally.
I used Github to deploy my project. I have separated folders for images, plug ins and readme files.

I had a slight problem commiting my readme file because I saved a gif file that is 117.4mb in size. There was an error that occured after pushing the file. My mentor, Arif suggested to run the [bfg code](https://stackoverflow.com/questions/32428981/error-unable-to-access-jarfile-bfg-jar-bfg) to clean up my repository by deleting large files and it worked.

---

## Credits

### Content

- The product descriptions for cakes and pastries, breakfast, lunch, snacks and dinner were copied from the [GertiesTripadvisor](https://www.tripadvisor.com.sg/Restaurant_Review-g298458-d16710720-Reviews-Gertie_s_Bakeshop_Fastfood-Tarlac_Tarlac_Province_Central_Luzon_Region_Luzon.html)
- The prices shown are not accurate and meant for visual purposes only. Actual prices can come on next stage of site development.
- For quick reference on carousel animation, I watched Clever Techie's [Youtube] (https://www.youtube.com/watch?v=AvMl3StAju4) 
- I referred to [w3schools](w3schools.com) for currency symbol, animated buttons and text formatting. 


### Media

- The product photos used in this site were obtained from [Pexel](https://www.pexels.com/).
   - Main-All day menu Lunch & Dinner Photo by William Choquette from Pexels
   - Main-All day menu Breakfast Photo by Krisztina Papp from Pexels
   - Main-Carousel Photo by Acharaporn Kamornboonyarush from Pexels
   - Main-Carousel Photo by Ella Olsson from Pexels
   - Main-Carousel Photo by energepic.com from Pexels
   - Menu-Header Photo by Igor Ovsyannykov from Pexels
   - Menu-Breakfast Photo by Julian Jagtenberg from Pexels
   - Menu-Lunch & Dinner Photo by Lisa Fotios from Pexels
   - Menu-Pastries Photo by Artem Beliaikin from Pexels
   - Delivery-Breakfast Photo by Daria Shevtsova from Pexels
   - Delivery-Lunch & Dinner Photo by Rajesh TP from Pexels
   - Delivery-Cakes & Pastries Photo by Dmitry Zvolskiy from Pexels

- The About us photo was obtained from Gertie's Bakeshop Instagram account.


### Acknowledgements

- This website is inspired by my Aunt Gertie who has given me permission to use her photos and logo.
- To my husband whose been supportive of me and kept sending me links relating to this course.
- To mentors Arif and Malcolm for guiding me in this project. To Alex for being helpful with my school requests.
