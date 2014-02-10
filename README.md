## Team Members
- Hanchuan Li: hanchuan@uw.edu
- Shengjie Wang: wangsj@uw.edu

## Project Name
##Movie Explorer：Which movie to watch tonight?

The data domain for our visualization is a part of the movie.csv file from assignment 2, with correction of mistakes. We visualized movies produced from 2000-2010 for users to browse and compare according to different orderings and visual encodings so that they can pick up the movie in which they are interested.

Users can manually select the ordering of the movie data, as well as the dimension of data to be presented on either top or bottom of the x-axis, so that they can browse the movie data according to their interests. Moreover, by comparing different dimensions together, users may be able to discover the hidden relationship among the variables.

Data are first grouped into bins, and users can drill down each bin by clicking on the bar chart. Inside each bin, users can browse specific information about each movie. The detailed information about the bin, as well as the movie is displayed on the right side of the bar chart.

## Running Instructions
Live Version:
http://cse512-14w.github.io/a3-wangsj-hanchuan/

## Story Board
https://www.dropbox.com/s/mloa7q2cv7seu9p/A3_Story_Board.pdf

## Changes between Storyboard and the Final Implementation

The changes we applied to final visualization includes: 
We grouped the bar charts into bins each of which contained 19 movies, and used average value for the value of the bin. Because there are lots of movies, it is easier to browse them after grouping, and drill down some particular bin to see the details. 
We abandoned the visual encodings of the C volume (width for the bar chart), as it was difficult for users to click bars with varying widths. Moreover, people have a better sense about length as compared to area/volume. Therefore, we chose to fix the width of each bar.

## Development Process

The visualization development started with brain storming ideas and finding proper data set. Inspired form the work in assignment 2, we decided on working on a interactive movie visualization tool to help users selecting movies of their interests. Then we designed the bar chart browsing system and implemented the visualization. Finally, we fixed minor bugs to make our interactive visualization more robust. The most time consuming parts are system design and webpage lay out adjustment. A total 39 hours are user and separated among teammates as follow.

Hanchuan Li:
- Major contribution to data selection & brainstorming ideas: 6 hours
- Major contribution to sketching storyboard & system design: 10 hours.
- Minor contribution to system implementation & improvement on bugs: 3 hours.

Shengjie Wang:
- Major contribution on system implementation: 15 hours
- Minor contribution on brainstorming ideas & system design 5 hours.



