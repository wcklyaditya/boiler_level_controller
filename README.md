# boiler_level_controller
The project needs to monitor the level of water in a boiler, and open/close a valve, using a servo, and not a valve controller.
1. The ball valve controller will be a home made version of this 
	1. [Aqua Scope Ball Valve servo](https://shop.zwave.eu/products/sensors/other/2567/aqua-scope-ball-valve-servo) 
	2. [video](https://youtu.be/0Z5sKuWwWZ8)
	3. [2S RC LiPO 7.4V 5200mA](https://www.amazon.com/Zeee-5200mAh-Battery-Vehicles-Airplane/dp/B07MJ9H47D/ref=sr_1_7?keywords=2S+battery+for+power+supply+6-8.4V&qid=1636903390&s=toys-and-games&sr=1-7)
		1. [Battery Monitor](https://hobbyking.com/en_us/hobby-king-battery-monitor-2s.html)
		2. [Manual](https://cdn-global-hk.hobbyking.com/media/file/454990207X350250X3.jpg)
	5. [60kg 6Nm 7.4V Servo](https://www.amazon.com/ANNIMOS-Digital-Voltage-Stainless-Waterproof/dp/B07KTSCN4)
	6. [Level Shifter](https://www.pololu.com/product-info-merged/2595) to PWM control the servo
	7. [DC-DC Converter](https://www.sparkfun.com/products/15208) for 7.4V to 5V conversion for ESP8266, and sensor
2. Water Level Detection
	1. [Capacitive Sensor](https://wiki.dfrobot.com/Non_Contact_Capacitive_Liquid_Level_Sensor_SKU_SEN0368)
2. Housing to mount
	1. Motor
	2. Battery
	3. ESP8266
	4. Couple to the pipe/somewhere else
	5. Coupler to the ball valve
