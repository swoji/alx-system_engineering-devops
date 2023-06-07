# Webstack monitoring

This project invovled setting up Datadog account to monitor server traffic
on my web-01 server.

## Tasks :page_with_curl:

* **0. Sign up for Datadog and install datadog-agent**
  * For this task I created [Datadog](https://www.datadoghq.com/) account.
   * Install `datadog-agent` on `web-01`.
   * Create an `application key`

* **1. Monitor some metrics**
 * Set up a monitor that checks the number of read requests issued to the
 device per second.
 * Set up a monitor that checks the number of write requests issued to the 
 device per second.

* **2. Create a dashboard**
 * [2-setup_datadog](./2-setup_datadog) create a dashboard with different 
 metrics displayed in order to get a few different visualizations.
* Add at least 4 widgets to your dashboard.
* Add `dashboard_id` on the first line.

