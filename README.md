# Digital Adthan Clock
As Muslims, it is essential to maintain a presence of our faith in our homes. Living in the USA, we face certain limitations on how much we can incorporate our religious practices into our daily lives. One prominent feature of a Muslim household in Islamic countries is the sound of the adhan, the call to prayer performed five times a day. Typically, every home is within earshot of a mosque, allowing everyone to hear the adhan when it is time for prayer. However, in the US, there are fewer mosques, and they are often restricted from broadcasting the adhan loudly for the community. To address this, I have decided to design a digital clock that will play the adhan at the appropriate prayer times.

# Requirements
To design our digital clock for Muslim households, we need the following features:

- **Power requirements**: Receive Power from outlet (120V) and step down to 
- **Current Time Display**: Shows time in 12-hour format with both Gregorian and Islamic calendars, displaying the date in MM/DD/YYYY and time in HH:MM:SS formats.
- **Adhan Playback**: Calls the adhan at designated prayer times.
- **Prayer Times Storage**: Connects to an app for up-to-date adhan times, with an option to choose different mu'adhdhin voices.
- **Location-Based Settings**: Automatically adjusts prayer times based on the user's location via the app.
- **Touchscreen Interface**: Enhances user experience with a modern, user-friendly interface.

These features ensure the clock effectively supports Muslim practices in the home.

# Components (Prototying)
Now that we have moved on from deciding our product's requirements, we will be moving on to gather the resources necessary to successfully implement a digital Adthan clock. We will be beginning with a prototyping phase on a breadboard before moving to design our own custom PCB. The components I will be using for testing will be:
- Arduino UNO: readily available and simple to use
- DS3231 RTC module: To keep accurate track of the current time, utilizes I2C communication
- ADA1770 TFT LCD Touchscreen: For user experience
- Adafruit STEMMA Speaker: To allow adthan to be heard throughout the house
- Buttons: For powering on device, different lighting functionalities.
- 



