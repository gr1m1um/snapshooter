# Snapshooter

Snapshots plugin for cockos Reaper DAW

Snapshooter allows to create param snapshots and recall them or write them to the playlist creating patch morphs.

Different from SWS snapshots, only the diffing of params is recalled or written to the playlist wich allows to create patch morphs

Requires rtk ui installed

Features:
  * Stores and retrieves FX params
  * ~~Stores and retries mixer track states: vol/pan/mute/sends~~ (disabled in alpha version)
  * Writes snapshots diffing from current state into the playlist creating patch morphs
  * recalls param values from snapshots into project timeline
  * performance, tested with dozens of tracks and hundreds of params with minimal cpu cost and linear overhead
