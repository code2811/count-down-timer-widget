# Countdown Timer Widget Demo

This is my Flutter countdown timer app for a timed quiz question use case.

## How to run

1. Make sure Flutter is installed.
2. In this folder run:

```bash
flutter pub get
flutter run
```

## Widget + 3 properties I demonstrate

Widget: `LinearProgressIndicator`

I focused on these three properties in the demo:

1. `value` (default: `null`)
   - In my app I pass a number from `1.0` to `0.0` as time goes down.
   - This shows the progress shrinking while the timer counts down.

2. `minHeight` (default: `4.0`)
   - I set it to `8` so the bar is easier to see.
   - Higher value makes the bar thicker.

3. `valueColor` (default: theme color)
   - I set green while running and red when time is up.
   - This makes the state clearer at a glance.

## Screenshot

Place the screenshot at `docs/final-ui.png`.

![Final UI](docs/final-ui.png)

## Presentation date

Date I presented in class: `YYYY-MM-DD`
