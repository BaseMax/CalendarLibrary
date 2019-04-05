# CalendarLibrary

The powerful library for display and convert calendar and handle the date units.

This library will be release for **C** / **C++**.

## Features

- Convert calendar units and dates.
- Display the current date.
- Convert date to string date, alphabet.
- Detecting the day of the date.

## Abilities

- string display(dateDisplayType type)
- string format(string format)
- date convert(dateType target)

#### Example of the future:

```c
date _date=Date(Date_Gregorian, 2019, 3, 4);
print( _date.format("Date is %y/%m/%d.\n") );
```

## Predefined constants

#### Date Type

| Constant      | Description                        |
| ------------- | ---------------------------------- |
| DATE_GREGORIAN| Gregorian calendar                 |
| DATE_JALALI   | Jalali calendar                    |
| DATE_LUNAR    | Lunar calendar                     |

#### Date Display Type

| Constant      | Description                        | Sample Output                        |
| ------------- | ---------------------------------- | ------------------------------------ |
| DATE_ATOM     | Atom                               | 2013-04-12T15:52:01+00:00            |
| DATE_COOKIE   | HTTP Cookies                       | Friday, 12-Apr-13 15:52:01 UTC       |
| DATE_RSS      | RSS                                | Fri, 12 Aug 2013 15:52:01 +0000      |
| DATE_ISO8601  | ISO-8601                           | 2013-04-12T15:52:01+0000             |
| DATE_W3C      | World Wide Web Consortium          | 2013-04-12T15:52:01+00:00            |
| DATE_RFC822   | RFC 822                            | Fri, 12 Apr 13 15:52:01 +0000        |
| DATE_RFC850   | RFC 850                            | Friday, 12-Apr-13 15:52:01 UTC       |
| DATE_RFC1036  | RFC 1036                           | Fri, 12 Apr 13 15:52:01 +0000        |
| DATE_RFC1123  | RFC 1123                           | Fri, 12 Apr 2013 15:52:01 +0000      |
| DATE_RFC2822  | RFC 2822                           | Fri, 12 Apr 2013 15:52:01 +0000      |
| DATE_RFC3339  | Same as DATE_ATOM                  | 2013-04-12T15:52:01+00:00            |

#### Format Specifies

| Constant | Description                        |
| -------- | ---------------------------------- |
| %d | The day of the month (from 01 to 31)|
| %D | A textual representation of a day (three letters)|
| %j | The day of the month without leading zeros (1 to 31)|
| %l (lowercase 'L') | A full textual representation of a day|
| %N | The ISO-8601 numeric representation of a day (1 for Monday, 7 for Sunday)|
| %S | The English ordinal suffix for the day of the month (2 characters st, nd, rd or th. Works well with j)|
| %w | A numeric representation of the day (0 for Sunday, 6 for Saturday)|
| %z | The day of the year (from 0 through 365)|
| %W | The ISO-8601 week number of year (weeks starting on Monday)|
| %F | A full textual representation of a month (January through December) |
| %m | A numeric representation of a month (from 01 to 12)|
| %M | A short textual representation of a month (three letters)|
| %n | A numeric representation of a month, without leading zeros (1 to 12)|
| %t | The number of days in the given month |
| %L | Whether it's a leap year (1 if it is a leap year, 0 otherwise) |
| %o | The ISO-8601 year number |
| %Y | A four digit representation of a year |
| %y | A two digit representation of a year |
| %a | Lowercase am or pm |
| %A | Uppercase AM or PM |
| %B | Swatch Internet time (000 to 999) |
| %g | 12-hour format of an hour (1 to 12) |
| %G | 24-hour format of an hour (0 to 23) |
| %h | 12-hour format of an hour (01 to 12) |
| %H | 24-hour format of an hour (00 to 23) |
| %i | Minutes with leading zeros (00 to 59) |
| %s | Seconds, with leading zeros (00 to 59) |
| %u | Microseconds |
| %e | The timezone identifier (Examples: UTC, GMT, Atlantic/Azores) |
| %I (capital i) | Whether the date is in daylights savings time (1 if Daylight Savings Time, 0 otherwise) |
| %O | Difference to Greenwich time (GMT) in hours (Example: +0100) |
| %P | Difference to Greenwich time (GMT) in hours:minutes |
| %T | Timezone abbreviations (Examples: EST, MDT) |
| %Z | Timezone offset in seconds. The offset for timezones west of UTC is negative (-43200 to 50400) |
| %c | The ISO-8601 date (e.g. 2013-05-05T16:34:42+00:00) |
| %r | The RFC 2822 formatted date (e.g. Fri, 12 Apr 2013 12:01:05 +0200) |
| %U | The seconds since the Unix Epoch (January 1 1970 00:00:00 GMT) |


## Supported Calendar Systems

| Name | Type | 	Group |
| ------------ | ------------ | ------------ |
| Gregorian calendar | | |
| Jalali calendar | Solar | Iranian |
| Lunar calendar | | |

View the full list at [here](https://en.wikipedia.org/wiki/List_of_calendars).

## Initial Start

According to Kambiz Asadzadeh, a CPP activist, there is a shortage of library for management and control over calendar and date, and the design of such a library can help a lot of developers in the world.

Given that I recently had a project for a company close to this, it was suggested to me to write such a library.

The developers are invited to develop this libraries in other languages such as Go, Rust, ...

## License

CalendarLibrary is licensed under the [GNU General Public License](https://github.com/BaseMax/CalendarLibrary/blob/master/LICENSE).
