# runtastic-gpx

💪 Converts runtastic exports to gpx

## Prerequisites

[Latest node and npm](https://nodejs.org)

## Instructions

1. Export entire account data and unzip:
   https://help.runtastic.com/hc/en-us/articles/360000953365-Export-Account-Data

2. Follow usage below

## Usage

```sh
$ npx runtastic-gpx <json-export> <output>
```

Example:

```sh
$ npx runtastic-gpx ~/Desktop/export-20190101-000 ~/Downloads/export
```

## Supported types

- Ride
- Road Bike
- Run
- Indoor Ride
- Indoor Run
- Elliptical
- Weight Training
- Crossfit
- Walk
- Swim
- Pilates
- Tennis
- Mountain Bike
- Other
- Hike
- Cycling ergometer
- Inline Skating

## License

MIT
