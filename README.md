# pom

Very simply cli for pomodoro.

## Usage

* `pom start` - to start timer.
* `pom abort` - to abort timer.
* `pom status` - to get current status.

Logs to `$HOME/.pom.dat`.

## Dependencies

* libnotify

## Integration with i3

To use `pom` with [i3](https://i3wm.org/), change `status_command` to
[i3status-pom](https://github.com/brb/dotfiles/blob/master/bin/i3status-pom) in
`~/.i3/config`.

![pom with i3](i3.png)
