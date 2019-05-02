# `today`

Set exit status according to a set of conditions for today

## Usage

```
Usage: today [OPTIONS] CONDITION [CONDITION …]

positional arguments:
  CONDITION        please see epilog

optional arguments:
  -h, --help       show this help message and exit
  -V, --version    show version information and exit
  -c, --copyright  show copying policy and exit
  -u, -z, --utc    use UTC rather than local time
  -q, --quiet      don't say a thing unless it's an error
  -v, --verbose    show result

This program tests if a set of conditions is true for today,
and exits accordingly.

Conditions include:
  · weekday
  · occurance of weekday

E.g.:
  · today is monday
  · today is the last tuesday
  · today is a wednesday or a thursday
  · today is a friday, a saturday, or a sunday.
  · today is the second or the fourth thursday

Weekdays can be abbreviated to their first three letters:
Mon, Tue, Wed, Thu, Fri, Sat, Sun.

Ordinals can be abbreviated to 1st, 2nd, 3rd, 4th, or 5th,
or even just 1, 2, 3, 4, or 5.
```

## Requirements

* Python 3.4+

## Repositories

* https://github.com/kseistrup/today.git
* ssb://%c99bvbt69xJrWtxdYMph0Pa6Z2bYMGwBSk2edtmgavo=.sha256

:smile:
