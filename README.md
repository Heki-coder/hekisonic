I created an ultrasonic library. I will explain in the following text how you can use it.

To create an instance and select the pins: Hekisonic(int echoPin, int triggerPin);

To set the temperature (default is 20°C): set_temperature(int t);

To get the distance in cm (returns a float): distance();

To get the distance in mm: distance_mm();

To get the distance in µm (micrometers): distance_um();

If you want more features, feel free to write to me in the comments.
