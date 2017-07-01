# JMeter Sitemap iteration


## Installation

### Download the current Version of JMeter

```
wget http://mirrors.ae-online.de/apache//jmeter/binaries/apache-jmeter-3.2.zip
unzip apache-jmeter-3.2.zip
cd jmeter
```

### Insert File and set the URL

`mv sitemap.jmx jmeter/bin/templates/`



Open the .jmx File ->File->Templates got to Thread Group and select the HTTP Request Tab. There you can set your sitemap.xml Path. The script will automaticly recognize the location and iterate throw the sitemap.

You can check the Requests already sent in the **View Results Tree** as well as set the output filename for saving your results. 





