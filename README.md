# InfluxDB 1.x role

After installing, you must create an admin user before using the system. Start
the influx console and run:

```
CREATE USER admin WITH PASSWORD '<password>' WITH ALL PRIVILEGES
```

At this point, this user needs to be created manually.

After this, you need to type `auth` and enter credentials before doing anything
in the influx console.
