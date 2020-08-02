*All copyrights and licensing reserved; Chatterjee and Jogalekar Solutions*
# Project Title - "Embedded Systems Examples"
## Identify two embedded systems that are sold on the market today and analyze their interfaces:
- Smart Watch: Small interactive screen + Comfortable wearable device
- Smart Fridge: Easy to use monitor/screen + different APP frameworks + software modules
## Describe all inputs to each system and outputs from each system:
### Smart Watch 
- INPUT: 
  1) Touchpad
  2) Power 
  3) Bluetooth
  4) Wifi integration
        
- OUTPUT: 
  1) Weather info
  2) Steps completed
  3) Blood pressure 
  4) SpO2  
  5) Make calls

### Smart Fridge:
- INPUT: 
  1) Touchpad on monitor/screen
  2) Food
  3) Power 
  4) Bluetooth
  5) Voice wake up  
  6) Feature to store display photos and music
         
- OUTPUT: 
  1) Temperature and Humidity display (ice level, water level etc)
  2) Food reminder display(through pressure transducer and infrared sensor)
  3) Food detection display(via ARM processor to APP)
  4) Memo function 
  5) Electronic photo album function
  6) Edit and Reset function to facotry settings/default

## Classify the inputs and outputs based on their mode of interaction:
- Visual - describing data carried by visible light
- Audio - describing data carried by sound
- Tactile - describing data carried by touch
- Electronic - describing data encoded in electrical signals
    
### Smart Watch:
- Visual: The screen denotes the number of steps completed, time, weather info, and other data we need to understand by visual input/output
- Audio: The device might play a cue on completing a certain objective of steps completed or an alarm/beeping signal if blood pressure/heart rate is abnormal
        Voice input or voice wake up feature based on Voice Recognition and AI can help improve audio interaction
- Tactile: The touch sensors associated with the small LCD screen provide ease of access and premium feel;most inputs are via touch
- Electronic: Bluetooth and WiFi system integrated into smart watch wearable device is a good example of electronic interaction
       
### Smart Fridge:
- Visual: The monitor/screen denotes temperature, humidity, reminders about low stock on food, displays future food memos, recipes, audio track, etc
- Audio: Voice recognition and AI integration can help voice wake up be a possible input feature for audio interaction
        Audio output is speaker when a command to play a specific song is executed.
- Tactile: Touchpad on the small monitor/screen provides a better interoperability to access different features swiftly
- Electronic: Bluetooth and WiFi system + Internet connectivity makes the smart fridge an intelligent IoT because:
             it can send/receive info from Internet regarding recipes
             suggest healthy fruits and vegetables
             set up a balanced diet/healthy routine for week
             install new songs/download albums as part of Electronic Audio(speaker) Function
                    
                    
#### For each input and output, estimate the rate at which data is transferred in any units that seem appropriate. 
***For example, a video game with a screen might output video data at 24 frames per second:***
  - Information, Bluetooth: Alot
  - Calls: 5 calls / day
  - Touchpad: 1 Touch / min
  - Food: 10 Food / day
  - Power: Frequency 50Hz
      
***Estimate the “response time” of the system for different inputs. That is, what is the time between when the system receives input and the system responds to that input?***
*For example, a digital camera might take a picture after a button is pressed. The response time would be the time between pressing the button and taking the picture. Explain how you made your estimation:*
  - Bluetooth -> Slow
  - Touchpad -> Fast
  - Food -> Slow
  - Power -> Fast
         
         
