current implementations:
1. main1.py: directly accesses the wheels of the bot and calls .run_angle() on them based on the direction and the divisions of the grid of the field
2. main2.py: directly accesses the wheels of the bot and calls .dc() on them based on the direction
3. main3.py: directly accesses the wheels of the bot and calls .run() on them based on the direction
4. main4.py: creates two DriveBases during movement and switches between these based on some granularity, moving a bit with each step
5. main5.py: creates two DriveBases during movement and runs them one ofer the other to move the bot

scrapped ideas:
1. create one DriveBase during movement with two motors based on the direction of travel