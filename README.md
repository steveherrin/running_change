Blog
----
This repo contains the raw data and analysis for [my blog post](https://https://medium.com/@SteveHerrin/how-i-made-a-little-money-by-running-a-lot-3d7bf39b436a).

The `csv` file
--------------
The data is tab-separated and has the following columns:

* `date` (in ISO-8601 YYYY-MM-DD format)
* `distance` (in miles)
* `route_type`
    * `loop` (I traveled in a loop)
    * `out_and_back` (I traveled out along a path and came back the same way)
    * `hybrid` (a route with both loops and out-and-back sections)
* `pace` (m:ss format, denoting minutes per mile)
* `money` (how many dollars I found)
* `coins` (a JSON string that can be a parsed into an array of the coin denominations I found, in cents)
