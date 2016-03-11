humanize_time(1) -- Humanize a time interval for display
========================================================

## SYNOPSIS

echo <milliseconds elapsed> | humanize_time<br>
humanize_time [--help]<br>

## OPTIONS

* -h, --help:
    Show usage help.

## EXAMPLES

```fish
sleep 1
echo $CMD_DURATION | humanize_time
1s 5ms
```
