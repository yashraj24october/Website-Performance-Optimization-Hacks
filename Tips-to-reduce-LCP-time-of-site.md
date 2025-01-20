#  LCP ( Largest Contentful Paint)
## - It is time taken my largest element of our 'About the fold content'
## About the fold content: the top part of page that users first see, any elements in this part should be lighter in this part and should load fast, especially the largest element in this part
## If any element in this part take more time, it become the LCP time and it reduce the performance of page.
## SO, lower the LCP, higher the performance and user experience.

### Tips to reduce LCP time

1. Identify the largest element of 'Above the fold' part and ensure it is lighter and will load faster. Make effort by code that it load faster.<br>
2.  Optimize the images size by using Webp, Avif instead of PNG and JPEG.<br>
3.  Add <b>font-display: swap; </b> in @font-face{} <br>
 it will impove the LCP. because of this browser will not wait for downloading of assigned font,<br> it will initially use the downloaded font first then swap after downloading of required font.
4.  Add defer in script elements
5. Minify html, css and JS file it will decrease the execution and load time.
6. Reduce of database queries and try caching of query result
7. Implement caching of view results.
8. Remove unused codes from CSS and JS.
9. Remove unnecessary commented codes.
   

