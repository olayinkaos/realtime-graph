# Flask Realtime Graph
Flask Realtime Graph built with Plotly and Pusher. You can view the tutorial [here](https://pusher.com/tutorials/bitcoin-live-graph-python).

## Getting Started
To run locally:
- Clone/Download this repo - `git clone https://github.com/olayinkaos/realtime-graph.git`
- [Optionally] Create a local virtualenv in the project folder (You must have virtualenv installed) - `virtualenv .venv`
- [Optionally] Activate virtual environment - `source .venv/bin/activate`
- Install all dependencies - `pip install -r requirements.txt`
- Replace the values of  `YOUR_APP_ID`, `YOUR_APP_KEY`, `YOUR_APP_SECRET`, `YOUR_APP_CLUSTER` with your Pusher credentials in `app.py` and `index.html`. These can be gotten from the [Pusher dashboard](https://dashboard.pusher.com/).
- Run app - `python app.py`
- Visit [localhost:5000](http://localhost:5000/) to view the app.

### Prerequisites

To run this app, you would need the following installed:

- [Python](https://www.python.org/)

## Built With

* [Pusher](https://pusher.com/) - APIs to enable devs building realtime features
* [Flask](http://flask.pocoo.org/) - Python web framework
* [Plotly](https://plot.ly/) - Data visualization tool
