Phil's Amazon Price Tracker
=======================

A  project that exists as an aid to monitor any product price on amazon.

This is my first project, please contribute and be nice :)

----

Install
----
Simply use 
```
pip install Phils-Amazon-Price-Tracker``` to install my Project.

Dependencies
----
```'plotly', 'html2text','robobrowser','jupyter','pillow'```

NOTE: These will be installed automatically

NOTE: At the Moment Image export will only work if you create a free account at plotly.com and configure it correctly

Run
----
```python3 -m priceTracker``` will start the programm

Options: ```-l link``` add a link to be monitored. Only links from the share option at amazon will work.

I recommend tu use a cronjob to run the programm every hour once automatically.

The file should use UTF-8 encoding and be written using ReStructured Text. It
will be used to generate the project webpage on PyPI and will be displayed as
the project homepage on common code-hosting services, and should be written for
that purpose.

Typical contents for this file would include an overview of the project, basic
usage examples, etc. Generally, including the project changelog in here is not
a good idea, although a simple "What's New" section for the most recent version
may be appropriate.
