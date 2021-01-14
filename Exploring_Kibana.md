## Exploring Kibana

Answers to first questions regarding the Kibana output from the sample data taken from the Kibana Dashboard

![alt text](https://github.com/sshsjames/Project-1/blob/main/Kibana_Dashboard.png) 

*NOTE  The above is just an example.  I set the date 12/12-12/19 to answer the following:

In the last 7 days, 249 unique visitors were from India
In the last 24 hours, 16.67% of the visitors from China were using Mac OSX
In the last 2 days, 26 people received 404 errors, while 15 received 503 errors.
In the last 7 days, China produced the majority of traffic on the website at 19.5%.
It appears that 1300hrs, or 1:00PM was the peak hour of traffic from China.
In the last 7 days, the following file types were identified: deb, gz, zip, css,  and rpm. 

A deb file is a Debian package or software package for a linux distribution.  

A gz file is a compressed archive file, a zip is a compressed file often made up of
archived files or folders.  

A css file is a cascading style sheet file used to format the contents of a webpage, and an rpm file is a Redhat package manager file primarily 
for linux distributions.  

In the last 7 days of this file, December 14, 2020 at 1800hrs had the most activity 
with almost 16,000 bytes of data.  

All of this data was from originating in India, with a destination within China.  
The data appears to be a successful transfer of HTTP data (response code 200).  

## Filter the data Answers

What is the timestamp for this event? December -14th at 1800hrs
What kind of file was downloaded? -Rpm file
From what country did this activity originate? -India
What HTTP response codes were encountered by this visitor? -200


## Switch to the Kibana Discover Page Answers

![alt text](https://github.com/sshsjames/Project-1/blob/main/Kibana_Discover.png)

*Note The above is just an example taken of where I pulled the information from.


What is the source IP address of this activity?  85.255.36.162

What are the geo coordinates of this activity?  

{
  "lat": 41.70742861,
  "lon": -73.73802889
}

What OS was the source machine running? -OSX

What is the full URL that was accessed?

https://elastic-elastic-elastic.org/people/

type:astronauts/name:andrei-borisenko/profile

From what website did the visitor's traffic originate? 

http://facebook.com/error/neil-woodward

## Finish investigation with a short overview of insights...

What do you think the user was doing?
-Looking up an astronaut!

Was the file they downloaded malicious?  
-No

Is there anything that seems suspicious about this activity?
-It seems to be a Facebook page of Neil Woodward, yet it is being 
serviced by an IP out of China.  
-They are still using Windows 7? (Ha!)

Is any of the traffic you inspected potentially outside of compliance guidelines?
-No. Not within this instance.
