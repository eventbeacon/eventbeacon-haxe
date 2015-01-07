# eventbeacon

Eventbeacon in HaXe

## How to use it
```
import eventbeacon.Beacon;

// ...

var beacon = new Beacon();
beacon.on('test', function(data) {
	trace(data);
});

beacon.trigger('test', 'Triggered that test event. Super cool.');
```

## License
Eventbeacon is public domain. If that does not work for you, feel free to use it under terms of the MIT license instead.