<strong>AWS CloudWatch</strong>

Amazon CloudWatch is a monitoring and logging service provided by Amazon Web Services. It helps you monitor AWS resources, applications, and system performance in real time.

What CloudWatch Does:-

CloudWatch collects metrics, logs, and events from AWS services.

It monitors things like:

CPU usage

Memory usage

Network traffic

Disk activity

Application logs

Example:

If your server CPU reaches 90%, CloudWatch can send an alert.


Main Components of CloudWatch:-
1. Metrics

Metrics are numerical data about system performance.

Examples:

CPU utilization of EC2

Disk read/write

Network traffic

Example metric:

CPU Utilization = 75%
2. Logs

CloudWatch can store application and system logs.

Examples:

Server logs

Application error logs

API request logs

Example log:

ERROR: Database connection failed
3. Alarms

Alarms notify you when something goes wrong.

Example rule:

If CPU > 80% for 5 minutes → send alert

Alerts can be sent through:

Email

SMS

Slack

Notifications

4. Dashboards

CloudWatch dashboards show graphs and monitoring panels.

You can see:

CPU graph

Network graph

Error rates

Request count


Why Companies Use CloudWatch:-

✔ Detect server failures
✔ Monitor application health
✔ Reduce downtime
✔ Automate alerts
✔ Analyze system performance