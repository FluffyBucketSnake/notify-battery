# notify-battery
## A utility for displaying battery notifications

*notify-battery* is a small utility I made for easy displaying of battery notifications, using *dunst*.

Keep in mind this scripts is only responsible for displaying notifications, not actually keeping track of the battery state. You can use *check-batery* as a script to continuously check the battery level and call the script.

### Requirements
- Dunst

### Usage
- Display battery level
```sh 
notify-battery level percentage[%] full|good|normal|low|critical
```
- Display power adaptor event
```sh 
notify-battery plug in|out
```