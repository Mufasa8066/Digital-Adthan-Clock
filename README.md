# Digital Adthan Clock
As a muslim, there is a need to always have a muslim presence in our home. Given that we live in the USA, there are limitations to how mcuh of our religion we can include around the home. One of the most prominent features found in a muslim household in islamic countries is the sound of the adthan, which is the call of prayer that muslims perform five times a day. Every home is within a ear's distance from a mosque which gives off the adthan when due. Since there aren't many mosques here in the US that are allowed to raise their volume up for the community to hear, I've decided to design my own digital clock that gives off an adthan whenever the time changes. 

# Requirements
To start off with the design process, we will assess what requirements are necessary for a successful product. This device will need several essential features such as: 
 - Current time display: The clock will be displaying the current time just as a normal digital clock in the 12-hour format with a gregorian calendar & Islamic calendar as well. It will also show the date in (MM/DD/YYYY) format and time in (HH:MM:SS) format
 - Play prayer times (adthan): When the current time is equal to the Adthan time, the adthan will be called.
 - Prayer times storage: The prayers times are situated throughout the day, and given that these times are prone to changing, we will be connecting the digital system to an app that already provides the adthan times. Another alternative is to just allow the user to manually adjust the time whenever there is any change, but change happens to frequently in adthan times and, thus, would be an inconvenience to perform. If not included in the app, we may also add a function where users could also add an adthan time for different prayers (other than the five mandatory prayers). There will also be a list of mu'adthineen (people of call adthan) to choose from so that user can shoose as they prefer.
 - Location: Taking the different timezones into account, we see that location will be a crucial factor for deciding prayer times. However, as mentioned previously, we will try to connect our clock to the app and utilize that as as setter for calling the adthan, and it will naturally have the location set, so there isn't need to worry about this part.
 - Touchscreen: In the era of digital technology, touchscreens are a crucial element to our dailt lives, simplifying user interface. We intend to include a touchscreen in our product to enhace user experience.

# Components (Prototying)
Now that we have moved on from deciding our product's requirements, we will be moving on to gather the resources necessary to successfully implement a digital Adthan clock. We will be beginning with a prototyping phase on a breadboard before moving to design our own custom PCB. The components I will be using for testing will be:
- Arduino UNO: readily available and simple to use
- DS3231 RTC module: To keep accurate track of the current time, utilizes I2C communication
- ADA1770 TFT LCD Touchscreen: For user experience
- Adafruit STEMMA Speaker: To allow adthan to be heard throughout the house
- Buttons



