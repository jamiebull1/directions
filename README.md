directions
==========

A package to integrate with directions APIs to find journey distance and duration, as well as other characteristics returned by the API.

The only API implemented at present is Google Directions.

Usage
=====
`GoogleDirections().query("london","leeds").distance`
`GoogleDirections().query("london","bristol", options={"mode": "bicycling"}).duration`

Options available are listed at:
https://developers.google.com/maps/documentation/directions/#DirectionsRequests

The whole JSON dict result will be in
`GoogleDirections().query("london","leeds").result`
