# JMeter Sitemap iteration
This scipt/file will go through a sitemap and call all URLs set in the <url><loc></loc></url> tags. It can be used to warm up a cache or to check the status of all indexed URLs in your sitemap.

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





