# Data-visualization Dashboard - Project for Stream 2 - Code Institute

Created in PyCharm using:
- Flask framework;
- MongoDB database (data taken from DonorsChoose.org);
- Bootstrap - website is mobile responsive;
- jQuery;
- dc.js, D3.js, crossfilter.js - to create graphs which change in real time according to the data the user has selected;
- intro.js - to create a tutorial for the dashboard
- the web app is then deployed to Heroku using heroku toolbelt and git.

Go to http://boiling-island-50928.herokuapp.com/ to check it out. 

The index page has a very basic design that tells a little bit about the organisation itself.

The dashboard page takes a good few seconds until it loads all data as it goes through the database (loading times vary and it's dependent of the user's Internet connection). The number of data entries is limited to 20000 entries.

There is a loader image that comes up when you navigate to the dashboard page.
There is some text that tells the user to click on "Start tutorial" to understand how the dashboard works. If the user clicks/taps on this section then it fades away. jQuery has been used to achieve this.

Then the tutorial goes through each graph and explains what they mean. The user can exit the tutorial at anytime and come back to it at a later time.

The graphs respond and update themselves in real time. By selecting/tapping/clicking on the graphs these change accordingly.

