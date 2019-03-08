# polybar-weather
Display weather status in polybar.

### Dependecies
- Python3

### Settings
``` ini
[module/weather]
type = custom/script
exec = python ~/path/to/polybarWeather.py -i 745042 -a appid123goes456here789 -t Celcius
```
### Usage
Here is the parameters.

-i CityId
-a AppID
-t OutputType
-z ZipCode
-c CountryCode
