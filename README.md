# TPLink SmartPlug poller
Another little project to learn golang

# Example Output
```shell
$ go run tpmon.go
Discovering devices...
Found 2 devices!
+------------------+------------------+-----------+---------+----------+-------+--------+---------+---------+------+-----------+
| Name             | IP               | Model     | Version | Mode     | State | Watts  | Current | Voltage | PF   | Total Kwh |
+------------------+------------------+-----------+---------+----------+-------+--------+---------+---------+------+-----------+
| Christmas Lights | 192.168.1.1:9999 | HS110(US) | 1.0     | schedule | On    | 235.92 | 2.50    | 123.00  | 0.78 | 35.28     |
| Living Room Lamp | 192.168.1.3:9999 | HS110(US) | 1.0     | schedule | Off   | 0.00   | 0.01    | 153.32  | 0.00 | 1.16      |
+------------------+------------------+-----------+---------+----------+-------+--------+---------+---------+------+-----------+
```
