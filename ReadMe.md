#Workshop Outline:

##Introduction to GIS and Digital Mapping

##Examples of Digital Mapping and "Fusion" of Historic and Digital Maps

##Georeferencing an Historic Map on DavidRumsey.com

##Creating a Map on CartoDB.com

##Crowdsourcing a Map with CartoDB.com and Google Docs

We're going to collaborate on a map of San Francisco's oldest bars, today. To do this, we will use several different digital tools. This mimics what one typically does on a real "Digital Mapping" project, combining various tools into what one refers to as the "technical stack."

###Assignment:


You will be provided with a piece of paper that has some basic information about one of the bars referred to in this article from [The Thrillist](https://www.thrillist.com/drink/san-francisco/oldest-bars-in-san-francisco).

The piece of paper you are given will contain some information of interest in this task, but you will also need to do some research on the internet (just using Google, really) to complete the task.

Research the bar you were given and enter the information that is requested into this Google Form [http://bit.ly/crbsform](http://bit.ly/crbsform)



##You will need to do the following to complete the task:

###Enter the easy stuff first
* The paper you were provided with should have the **Name**, **Year Established**, and the **Neighborhood** for your bar, already researched. 
* Enter the above information into the appropriate boxes on the Google Form. 

###You will need to find an image to use in the popup for your bar.  

* Go to [Google.com](http://www.google.com) and type the name of the bar and it's neighborhood into the search box and hit enter.
* Click on the **Images** link at the top of the Google Search Results Page.
  * *If you happen to find any offensive images (it's the internet, it happens), you can click on the **SafeSearch** button at the top of the page and select "Filter explicit results," to hide most of that type of material.*
* When you find a suitable image On the **Image Results Page** click on it and then click on the  **View Image** button. This should open the **just** image in a new page.
* Copy the URL in the resulting page and paste it into the **Image URL** box on the Google Form.
* Use the Browser's **Back** button to return to the **Image Search Results** and, this time, click on the **Visit page** button to go to the page that contains the image. 
* Copy the URL in the resulting page and paste it into the **Image Source URL** box on the Google Form.

###You will need the location of your bar.

* Use the Broswer's **Back** button to return to the Google Image Results page and click on the **Web** link at the top of the page to return to the Web Results view.
* There will probably be a Google Info Panel on the right side of the results page, with an image, map, StreetView, and some detailed information about the bar you are researching.
* Click on the Map to open a view of the location in [maps.google.com](http://maps.google.com)
  * *If for some reason you **don't** see a map, go to [maps.google.com](http://maps.google.com) and search for your bar using the same search term you used originally.*
* Use the Zoom controls to zoom into your bar location, if needed. 
* **RIGHT-CLICK** on the icon for your bar and select **What's Here** from the menu that should appear.
* At the bottom of your Google Map, you should see a small rectangle with a StreetView thumbnail image and some information about the location. **Copy & Paste** the Latitude and Longitude coordinates into the appropriate box (latitude or longitude) in the Google Form. [Hint: For San Francisco, the Longitude value should be negative].

###You will need 


##Creating a StoryMap with Odyssey.js

This part of the workshop is a bit "codey" for some people, so I will treat this as a demonstration. But, don't forget. There wouldn't be any map data for me to work with, if you hadn't done the research you did in the previous section. 

As I move through the process of taking our various elements (A georeferenced historic map, a CartoDB Map/Dataset, and the code that I will create in Odyssey.js), I will explain how each of these bits works along with the others to create a visually compelling "Narrative Map" of the history of taverns in San Francisco. 

If, at some point, you'd like to "get your hands dirty" so to speak, I've actually created a complete tutorial on the process of creating an application like we are creating today, from scratch. You can find this tutorial on the Stanford Geospatial Center's GitHub repository at:  
 [https://github.com/StanfordGeospatialCenter/CartoDB_Odyssey_Tutorial_for_Story_Maps](https://github.com/StanfordGeospatialCenter/CartoDB_Odyssey_Tutorial_for_Story_Maps)
 
###The Basic Workflow for Creating an Odyssey.js Story Map

####Learn a little Markdown

####Select the Odyssey.js Template you want to Use

####Customize the config block of Your Odyssey.js Application

####Add Your CartoDB Map/Data to Your Odyssey.js Application

####Create Your Slides Using Markdown

###Adding a Custom Basemap from DavidRumsey.com

####Find a Map that is Already Georeferenced, or Georeference One

####Go to the Embed OGC WMTS Tiles Page for your Map

####Copy the Web Address of the Map's Tile Service

####Add the URL to your Odyssey.js Config Block to Change Your Basemap

####Share your Story Map with Others


