Hi,

- Revised plots for downlink and uplink utilization (passive bitrate/ active capacity estimate) for the April data are here:
http://gtnoise.net/~sarthak/files/output201304/downlink_utilization.eps
http://gtnoise.net/~sarthak/files/output201304/uplink_utilization.eps

All downlink utilizations are under 1.0. But the uplink utilization for home 20 is too high. So I've plotted passive bitrate v/s active capacity plots for each home which can be viewed here: http://gtnoise.net/~sarthak/files/output201304/bitrate/. Home 20 is the file 20_OW100D7F64C8A3_up.eps. Clearly the active estimate seems to be off in this case.

- I have classified devices based on their manufacturers using the first few digits of the anonymized MAC addresses. This is a histogram of number of devices seen per manufacturer: http://gtnoise.net/~sarthak/files/output201304/devices_seen.eps

The most common devices we see are:
Apple          60
Asustek           6
Azurewave           3
Hewlett-packard     4
Hon                 9
Htc                 3
Intel              17
Lg                  3
Microsoft           4
Netgear            23
Nintendo            3
Samsung          13
We also see a couple of Tivo and Roku boxes on the list.

- Sarthak

------------------------------------------------------------------------------

Hi,

I have plotted new figures from the health data (# of end hosts attached for wired, wireless). New figures are in our SVN directory:
/figures/health/region_stat

This time, I get the maximum number of attached hosts from each household (during almost 2 months), and then group households into Developed or Developing countries. 

Reason for getting maximum: it is impossible to get the # of unique devices in household, as health data does not record the mac address of endhosts. Maximum number will at least give us a *lower bound* of # of unique devices in household.

For the bar graph, I get the *median* out of all household's data in a group  (and each household' data has the maximum number of attached hosts recorded).
- region_stat_combined.eps 
- region_stat_combined_wl.eps

Just getting *median* loses some information. I decided to plot a boxplot with the data:
- region_stat_box_developed.eps
- region_stat_box_developing.eps

-Joon

------------------------------------------------------------------------------

Hi,

I replaced old bytes per domain plots with new one and is in svn directory: /figures/bytesperdomain
In there: 
(1) fix of domain double count problems where if a flow contains both google.com and youtube.com, then it only counts for youtube.com,
(2) stacked graph of top 5 and top 10 domains instead of them being separate, and 
(3) domains visited by manufacturer type. 

Also, I've updated the raw data chart which is also in the same svn directory: /figures/bytesperdomain/data_reduced_chart.html

I'm getting MAC address - vendor lookup using http://standards.ieee.org/develop/regauth/oui/oui.txt

-Miseon


