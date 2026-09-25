# Route Lab: how a GPS uses live data

An interactive demo that shows how navigation apps turn live phone data into routes.

Students watch a simulated navigation system turn live speed reports from drivers' phones into a traffic picture, then route a car with Dijkstra's shortest-path algorithm.

## What it shows

1. **Live data feed.** Probe phones report their speed after each block.
2. **Processing.** Reports blend with historical patterns into a speed estimate for each road. Click a road in Inspect mode to see the math.
3. **Optimization.** Dijkstra's algorithm finds the fastest path. "Show the search" animates it.
4. **Output.** ETA, reroutes, and predicted versus actual trip time.

Incidents change reality, not the system's knowledge. The system has to detect them from the reports.

## Run it

Open `index.html` in any modern browser. No install, server, or build step.

## Notes

Traffic is simulated. The mechanism mirrors how services such as Google Maps and Waze use phone data, but no real traffic data is used.

Author: Cynthia McGinnis
