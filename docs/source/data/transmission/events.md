---
# Events

The `events` collection includes measurement data recorded by transmission PMUs during various events on the transmission grid. These include a sub-synchronous wide-area oscillation, and two switching events.

These data have been anonymized by removing details about the geography of the sensors or the assets they're connected to. We've also changed the time stamps, so the events themselves can't be identified. Voltage and current measurements are reported in per-unit notation (i.e., normalized based on their nominal values).

The data can be used to explore signal processing techniques for detecting events and for studying how events propagate throughout the transmission system.

For each event, the data includes two minutes of PMU measurements recorded across 23 sensors. The sensors report three-phase voltage and current at each measurement node.
