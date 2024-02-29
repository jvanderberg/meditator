# Calming meditation app

This is an app that provides an anchor for unguided meditation. It will
emit the selected sound on the selected interval, and at the end of the
session play the sound three times in succession to signal completion.

This helps you relax, not having to worry about when the session ends. The
sounds in the middle of the interval indicate progress and help to draw you back
into meditation and out of stray thoughts.

This app can also be used as a meeting timer. For example you might set a 60 minute session time with an interval of twenty or thirty minutes. 'First bell, and we haven't even gotten past the first slide, let's move it along folks'.

# Running the app

The app is written in modern 'vanilla JS' so there's no compilation step. Just run:

```
npm install
npm run start
```

And then open `http://localhost:3000` in your browser.

The app can also be found online at: [http://meditator.surge.sh](http://meditator.surge.sh)

# Using the app

1. Select a Bell
2. Select an Interval. 'Three Minutes' means the bell will play once ever three minutes.
3. Select a session length. This is how long the session will last.
4. Click 'Start'. The session will begin with a single bell chime. There's no visual indication that the session is in progress.

To stop the session click 'Stop'.
