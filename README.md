[![Build Status][travis-badge]][travis-link]
[![Slack Room][slack-badge]][slack-link]

# Humanize_duration

Humanize a time interval for display.

## Install

With [fisherman]

```
fisher humanize_duration
```

## Usage

```fish
sleep 1
echo $CMD_DURATION | humanize_duration
1s 5ms
```

[travis-link]: https://travis-ci.org/fisherman/humanize_duration
[travis-badge]: https://img.shields.io/travis/fisherman/humanize_duration.svg?style=flat-square
[slack-link]: https://fisherman-wharf.herokuapp.com/
[slack-badge]: https://img.shields.io/badge/slack-join%20the%20chat-00B9FF.svg?style=flat-square
[fisherman]: https://github.com/fisherman/fisherman
