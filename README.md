OpenWeatherMap-Api-Net
======================

This project is a fully asynchronous .NET Portable Class Library for interacting with the great [OpenWeatherMap API](http://openweathermap.org/API).

Documentation on [http://projects.joancaron.net/openweathermap/](http://projects.joancaron.net/openweathermap/).

###Usage examples

```c#
var client = new OpenWeatherMapClient("optionalAppId");
var currentWeather = await client.CurrentWeather.GetByName("London");
Console.WriteLine(currentWeather.Weather.Value);
```

###Supported Platforms

* .Net 4 and higher
* Windows Store Apps 8 and higher
* Silverlight 5
* Windows Phone 8
* Xamarin.Android
* Xamarin.Mac

###Dependencies

* Microsoft.Bcl
* Microsoft.Bcl.Build
* Microsoft.Bcl.Async
* Microsoft.Net.Http

###Copyright and License

Copyright 2014 Joan Caron

Licensed under the MIT License
