# tesla_roadster

FiveM Tesla Roadster with custom handling

## Requirements
None

## tesla_roadster

- Tesla Roadster
    - Custom handling, mimicking real-life expectations
    - Best in class acceleration: 0-60 ~4sec, 0-100 ~7sec
    - Limited top end due to increased drag: ~160mph
    - Better than average handling
    - Low center of gravity, limited roll-over

## Download & Installation

This resource was developed alongside [tesla_ev], [tesla_supercharger]. This resource works without them, but you might be interested in installing them altogether.

### Using Git
```
cd resources
git clone https://github.com/boostvolt/tesla_roadster [tesla]/tesla_roadster/

git clone https://github.com/boostvolt/tesla_ev [tesla]/tesla_ev/
git clone https://github.com/boostvolt/tesla_supercharger [tesla]/tesla_supercharger/
```

### Manually
- Download https://github.com/boostvolt/tesla_roadster/archive/master.zip
- Create and place in in `[tesla]/tesla_roadster` directory

## Installation
- Add this in your `server.cfg`:

```lua
start tesla_roadster
-- if you downloaded related resources
start tesla_ev
start tesla_supercharger
```

## Screenshots

![1](https://github.com/Boostvolt/images/blob/master/Roadster_1.jpg?raw=true)

![2](https://github.com/Boostvolt/images/blob/master/Roadster_2.jpg?raw=true)


[wtf_ev]: https://github.com/boostvolt/tesla_ev
[wtf_tesla_supercharger]: https://github.com/boostvolt/tesla_supercharger
