# socklog
A [socklog] instance that outputs UDP syslog message to stdout

This image can be used to catch and record log messages from applications, such
as [HAProxy], that only support logging to syslog. It listens for UDP syslog
messages on port 8514.

[socklog]: http://smarden.org/socklog/
[HAProxy]: https://www.haproxy.org/
