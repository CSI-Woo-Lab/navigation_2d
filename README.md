# navigation_2d
2d navigation gym environment implemented by pyBox2d 

![alt text](./images/display.png?raw=true)

## Installation
~~~~
pip install navigation_2d
~~~~

## Start
~~~~
'''
observation: ['position', 'distance', 'lidar', 'energy', 'obstacle_speed', 'obstacle_position']
Action: velocity
'''
gym.make('Navi-Vel-Full-Obs-Task17-v0')
~~~~

~~~~
'''
observation: ['position', 'distance', 'lidar', 'energy', 'obstacle_speed', 'obstacle_position', 'velocity']
Action: accleration
'''
gym.make('Navi-Acc-Full-Obs-Task5-v0')
~~~~

~~~~
'''
observation: ['position', 'distance', 'lidar', 'energy', 'velocity']
Action: accleration
'''
gym.make('Navi-Acc-Lidar-Obs-Task25-v0')
~~~~

## Info
|Task|Obstacles|Goal position|
|------|------|------|
|0 ~ 7|3 circular obstacles|distance 4.24 from start position|
|8 ~ 15|1 circular obstacle, 2 horizontal obstacles|distance 4.24 from start position|
|16 ~ 23|1 circular obstacle, 2 vertical obstacles|distance 4.24 from start position|
|23 ~ 31|1 circular obstacle, 2 horizontal obstacles, 2 vertical obstacles|distance 4.24 from start position|
