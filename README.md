

# VIDEO SAMPLE OF THE RESULT WITH IPHONEXR:

https://github.com/Gualberto-Vannini/Sample/blob/master/sample.mov?raw=true

# WRITTEN WITH:
Xcode 10.1 | Swift 4.2 



# DEVELOPED ONLY FOR:
IphoneXR


# SETTING UP:

I used Libraries during this test installed by COCOAPODS:

**Alamofire** | to handle the Api Call

**Gmaps**     | to handle the maps rendering  **PLEASE ====>  Follow the next steps to add your gmaps API key

To use the project, please use the file named:

lastMinute_GV.xcworkspace

# DEVELOP:

**Creation labels:**
I used both methods to create elements: programmatically and with graphically. 
  1. ListHotelVC class is created entirely with subviews. 
  2. SingleHotelVC class is created entirely using graphic components. 

**Performe Segue:**
I use both methods to create this: programmatically and with graphically. 

**Services:**
I created different classes to have separated Services and Code.

**Extensions:**
There are 3 extensions in the footer of appDelegate (after line 47):
1. UIImage extensions            ===> can rendering image from url 
2. UIImage extensions            ===> giving a size, returning cropped immage 
3. hexStringToUIColor extensions ===> can use as UIColor hex value

**Icons:**
Free download from https://thenounproject.com.
All images are correctly uploaded into Assets' folder in their correct form 1x, 2x 3x

**Goals:**
1. SpashPage (usefull to create a login form)
2. List af all Hotels with all the informations
3. Filter for Reviews or Stars
3. Single Page
4. Image Carousel
5. Hotel's position Map
6. This detailed documententations <3


# EXTRAS:

**Animation:**
A simple animation into the Splash page that helped me to get the time to collect all API data. 

**Carousel Images:**
Into the Single hotel's page, the header's image has a carousel with all the images presents. Maybe isn't easy to understand without arrow to the left and right or dots above of it but there are many images! Just scrolling to enjoy. 

**UIAlertController:**
They are very usefull to offer information.

**Filters:**
Due to lack of time, is a bit incomplete: I correct sorted for Reviews and Stars both however even if the right elements are shown, clicking any element there are still the older elements. 

# TO DO:
**stil opened**
Lack the time, I didn't handle all possibility as:
  1. no values retrivied from Api.
  2. no connection.
  3. Carousel of the hotel's image into the single page isn't not understandable that there is. 
  4. Code Refactory. 
  5. Filters click results.
 
**Gmaps** 
It is possible to see the location of the hotels on a map. Please, ADD YOUR KEY into this root:
"Api Services" Folder > EndPointApi.swift > insert as String into value of var authGMaps

If you don't want to create a new gmaps API key, please ask to me I'll share one.
I cant share here with bitbucket into a pubblic repository.


# CONTACT ME:

**For any problem, feel free to contact me.**

