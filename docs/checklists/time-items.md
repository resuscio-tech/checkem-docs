## Stopwatch ![Stopwatch icon](../images/stopwatch-icon.svg)
Simple stopwatch capable of recording duration, start time, and end time. Option to notify user at certain durations.
![Stopwatch item](../images/stopwatch.gif)

### Customizations
- Record time at beginning and end of stopwatch: Show timestamp when stopwatch is started/stopped. Resuming/pausing will reset end time.

#### Alarms
Add alarms to notify the user when a specific duration has passed. Choose from multiple sounds, and set `Ring at` to the desired duration. Choose `Repeat` if you'd like the alarm to loop indefinitely.

Users can click the bell icon on the stopwatch item to silence alarms. ![Bell icon](../images/bell-icon.svg)

![Stopwatch alarm customization](../images/stopwatch-alarms.png)

## Timer ![Timer icon](../images/timer-icon.svg)
Countdown timer capable of recording start and end time. User is notified when time is up.
![Timer item](../images/timer.png)

### Customizations
- Record time at beginning and end of stopwatch: Show timestamp when stopwatch is started/stopped.
- Notification text: Text that will be displayed when time is up.
- Minutes / Seconds: Duration of timer.
- Sound: Choose from 5 alarm sounds.

![Timer customization](../images/timer-alarm.png)

Users can click the bell icon on the timer item to silence the alarm. ![Bell icon](../images/bell-icon.svg)

## Time Marker ![Time Marker icon](../images/time-marker-icon.svg)
Button which records the current time when clicked. Can do this repeatedly.
![Time Marker item](../images/time-marker.gif)

Use the undo ![undo icon](../images/undo-icon.svg) to remove the latest marked time, or click `Reset` to remove all marked times.

### Customizations
Button text: Change the button text. Default is `Mark Time`.

## Metronome ![Metronome icon](../images/metronome-icon.svg)
Metronome for keeping pace. When button is pressed, audio is emitted at the desired rate.
There are 2 configurations for the Metronome app:

- CPR: *Continuous, Continuous+10 BPM Ventilations, 30:2, 15:2*
- Ventilations: *8, 10, 12, 16, 20, 25, and 30 beats per minute*

| CPR | Ventilations |
| --- | --- |
| ![Metronome in CPR configuration](../images/metronome-cpr.png) | ![Metronome in Ventilations configuration](../images/metronome-ventilations.png)