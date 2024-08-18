### Requirements
This exact implementation requires `python3.11`, which is only needed to server the game files on your browser.

#### Install requirements
```shell
python3.11 -m venv .venv
source .venv/bin/activate
pip install -r requirements
```

### How to run
To run the game, you must run the `app/app.py` using `fastapi`.
```shell
fastapi dev app/app.py
```

You can now access the game on [http://127.0.0.1:8000/static/index.html](http://127.0.0.1:8000/static/index.html).


### Game basics
#### Player 1 (left) controls
- `W`: move up
- `S`: move down

#### Player 2 (right) controls
- `UP`: move up
- `DOWN`: move down

First player that reaches 10 points, wins and the game ends. To restart it, simply press `F5`.