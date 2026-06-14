# Process Creation Monitoring

```spl
index=main host=DESKTOP-V0R9K7V
| rex field=_raw "<EventID>(?<EventID>\d+)</EventID>"
| search EventID=1
```

# Network Connection Monitoring

```spl
index=main host=DESKTOP-V0R9K7V
| rex field=_raw "<EventID>(?<EventID>\d+)</EventID>"
| search EventID=3
```

# DNS Query Monitoring

```spl
index=main host=DESKTOP-V0R9K7V
| rex field=_raw "<EventID>(?<EventID>\d+)</EventID>"
| search EventID=22
```
