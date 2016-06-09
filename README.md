# land scout

## view the terrain (description)

Land scout scans MLS listings using an MLS "api" and rate properties based on
qualities desired from the various co-living members.

## hike it (usage)

(vague for now)

0. give the app the link to your favorite MLS listing site after you have done a
   search using the area desired
1. run the async job
2. start the web server
3. view the output of the job via the webserver

## view the topology (how does this work?)

1. poll the MLS source for listings
2. get detailed listing information
3. calculate distances to desired points of interest for various members using
   their preferred modes of transportation
4. tally up desired qualities for members - overlapping qualities are weighted
   higher
5. determine a score for each listing which represents the score for the group
6. persist the listing data and the scoring for later consumption
7. host the scoring data

## consult the guide (help)

Logan Barnett (logustus@gmail.com) - the best place to look for help would be in
the github issues page

## other campers (system interactions)

This app uses a web server to show the results as well as a command line script
to go get the results. Getting the results is very time consuming and needs to
be performed asynchronously.

## lead the scouts (contribution)

You could start by helping me get a contribution guide in place. Filing issues
is also a great way to help.

## arrive at the camp site (deployment)

TBD
