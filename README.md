# Mission To Mars
## Project overview:
The purpose of this project is to build a web application that scrapes new data every time we press a button. The designed web page will scrape websites for information regarding mars planet and will display this information in a single HTML page containing information about new articles (headings and paragraphs), and a Mars planet facts table. Plus, all four Mars’s hemisphere images are included as well as the titles of those images. Finally, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images. To do this we use:
-	**Chrome Developer** tools **(DevTools)** to identify **HTML** components.
-	**Beautiful Soup/Splinter** to automate a web browser and perform the scraping.
-	**MongoDB** to store the data.
-	**Flask** to create a web application to display the data.

## Challenges: 
1. Scrape Full-Resolution Mars Hemisphere Images and Titles:
2. Update the Web App with Mars’s Hemisphere Images and Titles.
3. Add Bootstrap 3 Components.

## Results and Summary:
### Scrape Full-Resolution Mars Hemisphere Images and Titles:
- Code is written that retrieves the full-resolution image and title for each hemisphere image- Update the Web App with Mars Hemisphere Images and Titles.
- The full-resolution images of the hemispheres are added to the dictionary. 
- The titles for the hemisphere images are added to the dictionary.
- The list contains the dictionary of the full-resolution image URL string and title for each hemisphere image.

![image](https://user-images.githubusercontent.com/62036983/143665279-63a57357-8840-4749-aa24-dfbba266295f.png)

### Update the Web App with Mars’s Hemisphere Images and Titles.
- The scraping.py file contains code that retrieves the full-resolution image URL and title for each hemisphere image.
- The Mongo database is updated to contain the full-resolution image URL and title for each hemisphere image.

![image](https://user-images.githubusercontent.com/62036983/143665190-0eec0c0c-1283-4b4b-9c98-c2895f41fdc2.png)

- The index.html file contains code that will display the full-resolution image URL and title for each hemisphere image.

![image](https://user-images.githubusercontent.com/62036983/143665118-72dcaf64-514c-4b58-bc57-54efe8c5bb8e.png)

- After the scraping has been completed, the web app contains all the information from this module and the full-resolution images and titles for the four hemisphere images.

### Add Bootstrap 3 Components.
1.	Use the Bootstrap 3 grid system (Links to an external site.) examples to update your index.html file so your website is mobile-responsive. Use the DevTools to test the responsiveness of your website.
- Click on the Toggle Device Toolbar icon to open the UI that enables you to simulate responsiveness.
- Choose a device to test your webpage, as shown in the following image.

![image](https://user-images.githubusercontent.com/62036983/143665405-be03f1e8-8b4f-426f-948a-da85062bb973.png)

2.	Add two other Bootstrap 3 components from this list (Links to an external site.).
- Styling the "Scrape New Data" button.
- Customizing the facts table. 
- Adding the hemisphere images as thumbnails.

![image](https://user-images.githubusercontent.com/62036983/143665331-8a845a41-cc57-484c-936c-6378516a6cd1.png)
