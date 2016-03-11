[![Build Status][travis-badge]][travis-link]
[![Slack Room][slack-badge]][slack-link]

# humanize_time

Humanize a time interval for display.

## Install

With [Fisherman]

```
fisher i humanize_time
```

## Usage

```fish
sleep 1
echo $CMD_DURATION | humanize_time
1s 5ms
```

[travis-link]: https://travis-ci.org/fishery/humanize_time
[travis-badge]: https://img.shields.io/travis/fishery/humanize_time.svg?style=flat-square
[slack-link]: https://fisherman-wharf.herokuapp.com/
[slack-badge]: https://img.shields.io/badge/slack-join%20the%20chat-00B9FF.svg?style=flat-square
[Fisherman]: https://github.com/fisherman/fisherman
