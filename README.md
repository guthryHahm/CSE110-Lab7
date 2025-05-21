Guthry Hahm

1. I would use a github action, as it would automate the process further and put all your tests on place, so you're less likely to miss it.

2. No, It would probably make more sense to run unit tests for that.

3. Navigation mode runs after a page is loaded. It can give performance data on loading only. Wheras in snapshot mode, a "snapshot" of the page is analyzized a static point in time. Neither can analyze interactions.

4. Primarily it looks like we could cut back on the size of the images to improve performance. In terms of accesibility, we could stand to add a [lang attribute] to the html, to outwrite declare the languages that are supported. We also should proabably have a meta tag in the header with important/useful information.
