# PinballLabProject
This is the pinball game I designed and developed with my lab partner Amit Beltzer, for Technion course 044157.

We used an FPGA with a VGA screen and a keyboard, and programmed in Quartus using Verilog.
The task was to create a pinball game that contains a ball with balistic motion, two flippers that move horizontally, a score count and obstacles.
We programmed the flippers to move independantly, added moving obstacles with random positioning, subtracted and added to the score according to the collision and added a "life" countdown.

Opening Screen

The ball and the obstacles are in opening position, score count and lives are reset.
![image](https://user-images.githubusercontent.com/104515303/176533531-39c15997-bebc-4a89-a36a-01b06f98acca.png)

Game Board

![image](https://user-images.githubusercontent.com/104515303/176533431-9bff1464-74e3-4a8c-ad95-9213f587f500.png)

Winner Screen

If the player reaches 200 points without running out of lives.
![image](https://user-images.githubusercontent.com/104515303/176533647-4907dfb2-419b-4f90-a74d-bf7102855ffa.png)

Game Over

If the player runs out of lives, hitting certain obstacles or falling between the flippers.
![image](https://user-images.githubusercontent.com/104515303/176533874-6d6b78dd-fd9c-4866-ae08-641ce2452648.png)
