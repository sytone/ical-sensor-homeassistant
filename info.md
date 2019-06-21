# Usage Overview

In your configuration.yaml you'll need:

```
sensor:
- platform: ical
  name: "My Calendar"
  url: "http://url.to/ical"
```

It will create sensors for the next few future calendar events, called:

* sensor.my_calendar_event_0
* sensor.my_calendar_event_1
* sensor.my_calendar_event_2

etc