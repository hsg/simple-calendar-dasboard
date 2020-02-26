Simple Calendar/Dasboard
=================

A calendar/dashboard provider for a wall-mounted e-ink display. 

Forked from https://github.com/niccokunzmann/open-web-calendar.


Software Components
-------------------

- Python3 and the packages in requirements.txt
  - [Flask](http://flask.pocoo.org/)
- [DHTMLX scheduler](https://docs.dhtmlx.com/scheduler/)
- [python-recurring-ical-events](https://github.com/niccokunzmann/python-recurring-ical-events)


Development
-----------

1. Optional: Install virtualenv and Python3 and create a virtual environment.
    ```
    virtualenv -p python3 ENV
    source ENV/bin/activate
    ```
2. Install the packages.
    ```
    pip install -r requirements.txt
    ```
3. Start the app.
    ```
    python3 app.py
    ```
