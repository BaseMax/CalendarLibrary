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

```
date _date=Date(Date_Gregorian, 2019, 3, 4);
print _date.format("Date is %y/%m/%d.\n");
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
