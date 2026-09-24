# picacatalog
Offline-first photo, video and file catalogue inspired by Picasa 3, with local search, metadata, removable-drive support and exact duplicate detection.

# PicaCatalog

PicaCatalog is an offline-first photo, video and general file catalogue inspired by the simplicity and local-first workflow of Google Picasa 3.

It is designed to catalogue files where they already exist across local disks, removable drives and mounted storage without requiring a server, cloud account, NAS or web service. The catalogue and metadata are stored locally in SQLite, allowing PicaCatalog to remain useful even when removable storage is disconnected.

The current beta includes:

* Photo and video browsing with thumbnail generation
* General file cataloguing and file-type resolution
* Local search
* Folder and date-based navigation
* Favourites and 0–5 ratings
* Captions and tags
* Albums
* Persistent removable-drive identity and offline source tracking
* Exact duplicate detection using file hashing
* Hidden file/folder inclusion and exclusion controls
* Local activity logging
* Native desktop file and folder integration on Linux

PicaCatalog is being developed in small, testable chunks so each subsystem can be verified before more destructive functionality is introduced.

The current beta is deliberately non-destructive. Duplicate detection is available, but automatic consolidation, file moving and deletion are not yet enabled while those safety-critical features are being developed and tested.

The long-term goal is a fully local media and file-management application that combines a Picasa-style catalogue with safe duplicate consolidation across multiple storage devices.
