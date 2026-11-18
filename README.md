# SurfaceScout

An Android app for adventure and dual sport riders. One tap while you ride records the road's surface, a gate or
a closure. After the ride you review what it found and send it to [OpenStreetMap](https://www.openstreetmap.org),
the map behind most riding apps and route planners.

**[Download the latest version](https://github.com/dparisoe/SurfaceScout-releases/releases/latest/download/SurfaceScout.apk)**
· [About the app](https://www.regulatorsdualsport.com/software/surface-scout/)
· [Privacy policy](https://www.regulatorsdualsport.com/software/surface-scout/privacy/)

## Install

1. On the phone, tap the download link above.
2. Open the downloaded file. If Android asks, allow your browser or Files app to install unknown apps.
3. Allow location when the app asks. It needs it to know which road you are on.
4. To update later, install the new version over the old one. Your rides are kept.

Android 7.0 or later. Road data covers Florida only so far. To send what you find you need a free OpenStreetMap
account; you don't need one to record a ride or share its GPX.

## What it sends to OpenStreetMap

- A surface tag (`surface=paved`, `compacted`, `gravel`, `dirt`, `sand`, `clay` or `unpaved`) on roads that have **no surface** on the map. It
  never replaces a surface someone already mapped: each road is read again just before its edit goes, and the
  edit is dropped if the road has a surface by then.
- Notes for local mappers where one tag can't say it: a surface that changes along a road, a gate the map
  lacks, a closure.
- Only what you leave switched on in the review, under your own account, in a changeset tagged
  `created_by=SurfaceScout` and `source=survey`.

Questions, ideas, a mapper's concerns: dparisoe@regulatorsdualsport.com

Each [release](https://github.com/dparisoe/SurfaceScout-releases/releases) lists what's new in it. This
repository holds only the app's releases.
