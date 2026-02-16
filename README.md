# Find Duplicates

## Version history

| Date      | Author               | Version | Details                            |
| ----------|----------------------|---------|------------------------------------|
| 2026      | Marcus Bogenstaetter | 1.3.0   | UI bug fixes and UI improvements   |
| 2006-2025 |                      |         |                                    |
| 2002-2006 | Arnab Bose           | 1.2.5   | Initial version, all functionality |


## Details about 1.3.0

Over the course of time (more than 20 years), MFC and Windows have changed. While DPI-scaling is still not optimal in latest Windows, this feature together with the out-dated MFC libs, made the UI sometimes unusabe due to disappeared buttons and alike.

Thankfully, Arnab uploaded the source code to GitHub, so I was able to fix some UI issues:

* Update the MFC version to 1.43 (hopefully, this fixes many issues in newer windows)
* Put the check boxes to an options menu, so that they do not use space from the folder list.
* Make the layout resizable and use the added space
* Make the column widths of the folder list and file result list auto resizing (no truncation of long paths and file names)
* The whole program logic was not touched at all!

## Disclaimer

This program is provided as is, no warranty whatsoever. If you do not agree, do not use it.

