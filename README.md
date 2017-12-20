# Website Performance Optimization portfolio project

This project is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques I've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

## Steps taken to optimize

### Part 1: Optimize PageSpeed Insights score for index.html
[Google PageSpeed Insights tool](https://developers.google.com/speed/pagespeed/insights/).
The optimization is done through the image compression

### Part 2: Optimize with Chrome Dev Tools
[Chrome Dev Tools tips-and-tricks](https://developer.chrome.com/devtools/docs/tips-and-tricks).
The optimization is done through reduce the forced reflow and move some calculate to be outside of the loop
