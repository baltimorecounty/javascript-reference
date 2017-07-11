# Baltimore County Javascript Utilities

More to come...

## Tips and Tricks

* [Statements and Declarations](statements-and-declarations)

## Interval Timer

Adds functionality to the [setInterval](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setInterval) method.

### File Name
bc.interval-timer.js

### Dependencies
none

### Usage
```javascript
var intervalTimer = new IntervalTimer(function() {
  console.log("I fire every 60 seconds");
}, 60000);
```

### Pause
```javascript
$(document).on('click', '#stopButton', function() {
  intervalTimer.Pause();
});
```

### Resume
```javascript
$(document).on('click', '#resumeButton', function() {
  intervalTimer.Resume();
});
```

### Stop
```javascript
$(document).on('click', '#resumeButton', function() {
  intervalTimer.Stop();
});
```