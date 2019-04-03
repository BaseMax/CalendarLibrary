# CalendarLibrary

The powerful library for display and convert calendar and handle the date units.

This library will be release for **C** / **C++**.

## Features

- Convert calendar units and dates.
- Display the current date.
- Convert date to string date, alphabet.
- Detecting the day of the date.

## Abilities


#### Example of the future:

```
Date _date=Date(Date_Gregorian, 2019, 3, 4);
print _date.format("Date is %y/%m/%d.\n");
```

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
