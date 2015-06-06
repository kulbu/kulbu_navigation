# mybot_moveit_config

Copy pre-compiled description file into config.

`rosrun xacro xacro.py `rospack find mybot_description`/urdf/mybot.xacro -o `rospack find mybot_moveit_config`/config/mybot.urdf`
