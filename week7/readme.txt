Consider the following pair of images. In the second image, few toys have been
placed in the scene.
The following code tries to count the number of toys by subtracting the two images,
thresholding the result and then counting the connected components. Your job is to
fix this code to get the correct number of toys and find the biggest toy.
Change the threshold variable and see the result. Find a reasonable threshold
(it does not need to give the correct result.)


● Uncomment the four lines after the line ## opening. Run the code. What does
the opening operator do? Change the kernel size and see the results.


● Uncomment the four lines after the line ## closing. Run the code. What does
the closing operator do?


● Tune the threshold, opening kernel size and closing kernel size until you get
the desired result, finding all the toys and their number.


● Uncomment all the lines after ## connected components with statistics. It
gives statistics about each connected component including centroid, left-most
pixel location, top-most pixel location, width, height and area (number of
pixels) of each connected component. We want to detect Jenab Khan (the
biggest toy) in the image and paint it in red. Currently, the code paints the last
connected component (j=n-1). Use the statistics to find the connected
component with the largest area, and paint the biggest toy in red