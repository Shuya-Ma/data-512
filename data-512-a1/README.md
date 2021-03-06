# A1: Data Curation

## About the project
The goal of this project is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through August 30 2020.

## Data Source
The two API we used to collect data:
- The Legacy Pagecounts API ([documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts), [endpoint](https://wikimedia.org/api/rest_v1/#/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end)) provides access to desktop and mobile traffic data from December 2007 through July 2016.
- The Pageviews API ([documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews), [endpoint](https://wikimedia.org/api/rest_v1/#/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end)) provides access to desktop, mobile web, and mobile app traffic data from July 2015 through August 2020.

Note: For this project, we are mostly interested in organic (user) traffic. Therefore, we set agent=user for Pageviews API to exclude spiders/crawlers, while Pagecounts API does not allow us to filter the data.

## Result

### Data output
The final data output can be found in the CSV file.
Column variables and description:
- year : 2008 - 2020 
- month : January 1 2008 - August 30 2020
- pagecount_all_views : pagecount_desktop_views + pagecount_mobile_views
- pagecount_desktop_views : monthly views of the desktop site visits from December 2007 through July 2016 by the Pagecounts API
- pagecount_mobile_views : monthly views of the mobile visits from December 2007 through July 2016 by the Pagecounts API
- pageview_all_views : pageview_desktop_views + pageview_mobile_views
- pageview_desktop_views : monthly views of the desktop site visits from July 2015 through August 2020 by the Pageviews API
- pageview_mobile_views : monthly views of the mobile web + mobile app visits from July 2015 through August 2020 by the Pageviews API


### Data Visulization

![visulization](pagevies_plot.png)

## License

- Both Pagecounts API and Pageviews API are licensed under the [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) and [GFDL](https://www.gnu.org/licenses/fdl-1.3.html) licenses.

- Wikimedia Foundation REST API [Terms of Use](https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions) and [Privacy Policy](https://foundation.wikimedia.org/wiki/Privacy_policy).