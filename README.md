# Digital Adhan Clock
In Muslim-majority countries, the adhan, or call to prayer, is a beautiful and essential feature of daily life, resonating from mosques and reminding everyone of the prayer times. Living in the USA, we face certain limitations in incorporating this important aspect of our faith into our daily lives. One significant challenge is the limited number of mosques and the restrictions they often face in broadcasting the adhan loudly for the community.

To address this, I have decided to design a digital clock that will play the adhan at the appropriate prayer times. This digital clock will be a valuable addition to Muslim households, ensuring that we can maintain a strong presence of our faith within our homes, regardless of our geographical location.

*Note: There are digital adhan clocks available on the market. This is just to showcase the step-by-step process of designing one on my own.*

# Requirements
To design our digital clock for Muslim households, we need the following features:

- **Current Time Display**: Shows time in 12-hour format with both Gregorian and Islamic calendars, displaying the date in MM/DD/YYYY and time in HH:MM:SS formats.
- **Adhan Playback**: Calls the adhan at designated prayer times.
- **Prayer Times Storage**: Connects to an app for up-to-date adhan times, with an option to choose different mu'adhdhin (person who calls the paryer) voices.
- **Location-Based Settings**: Automatically adjusts prayer times based on the user's location via the app.
- **Touchscreen Interface**: Enhances user experience with a modern, user-friendly interface.
- **Weight**: Ranging from 1.5 - 2 pounds

These features ensure the clock effectively supports Muslim practices in the home.

The technical requirements for this clock goes as follows:

- **Power**: 9V, 500-800mA power adapter. The goal is to remain as power-efficient as possible.
- **Audio**: 70 dB
- **Display**: LCD Screen due to affordability
- **Controls**: Buttons & touchscreen
- **Temperature sensing**: 

# Components (Prototying Phase)
Now that we have moved on from deciding our product's requirements, we will be moving on to gather the resources necessary to successfully implement a digital Adthan clock. We will be beginning with a prototyping phase on a breadboard before moving to design our own custom PCB. The components I will be using for testing will be:
- Arduino UNO: readily available and simple to use
- DS3231 RTC module: To keep accurate track of the current time, utilizes I2C communication 
- ADA1770 TFT LCD Touchscreen: For user experience
- Adafruit STEMMA Speaker: To allow adthan to be heard throughout the house
- Buttons: For powering on device, different lighting functionalities.
  
I've ordered the necessary components from Adafruit. I will begin the prototyping phase by 


