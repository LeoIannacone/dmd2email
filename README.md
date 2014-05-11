#dmd2email
Debian Maintainer Dashboard to email

Look for new incoming objects in the TODO list of a Debian Maintainer Dashboard and send out emails about.

## Usage
```
usage: dmd2email [-h] [-D DEBUG] maintainer email

positional arguments:
  maintainer            the maintainer email to check over udd
  email                 the email address to send info

optional arguments:
  -h, --help            show this help message and exit
  -D DEBUG, --debug DEBUG
                        set debug level
```

## Example
```
python3 dmd2mail python-apps-team@lists.alioth.debian.org l3on@ubuntu.com
```

## Tips
Designed to be added into a cronjob.
