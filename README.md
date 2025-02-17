![Banner Image](docs/generic-screenshot.png)
# Flipp Pomodoro

Boost Your Productivity with the Pomodoro Timer for Flipper Zero! Don't let your flipper get bored, let him help you instead.

## Instalation

[DOWNLOAD application from releases](https://github.com/Th3Un1q3/flipp_pomodoro/releases) and follow instructions there.

## Development

### Current state and plans

At the moment following functionality implemented:
![Working Screen](docs/working.png)
![Resting Screen](docs/resting.png)
* Generic pomodoro cycle with two stages (Work: 25 min and rest 5 minutes)
* Automatic and manual phases switch
* Notification(sound, vibration, backlight, led) on stage change.
* Energy Effecient workflow
* Increase flipper happines score when completing pomodoros

Will do(if I've got time):
* ~~Publish a .fap package to let anyone download and install the app.~~
* ~~Configure CI pipeline for automatic releases~~
* Stats on exit(how many pomodoros complete)
* Background work or restore from last state
* ~~Integration with passport to develop your flipper profile by completing pomodoros~~
* Configuration of notifications
* Blind mode(no timer updates, just background and notification) for more energy saving

###  Build and Package
Build application
```shell
# For standard(official) firmware
bash tools/build.sh

# For unleashed firmware
bash tools/build.sh -f unleashed 
```
