# Monty Hall Game

An interactive simulation of the Monty Hall problem. Pick one of three doors, the host opens a door with a goat, and you decide whether to switch or stay. The app tracks statistics for both strategies and can auto-run 1000 games to show the win rates.

Available in Ukrainian and English.

## Run locally

Open `index.html` in a browser, or serve it:

```
python -m http.server 8000
```

Then go to http://localhost:8000.

## The idea

Your first pick has a 1/3 chance of being the car. Switching after the host reveals a goat wins about 2/3 of the time, while staying wins about 1/3.
