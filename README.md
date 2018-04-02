| Component              | Name               | Entity ID                                       | Friendly Name | HomeBridge Name | Hue Name   |
| ---------------------- |--------------------| ------------------------------------------------|---------------|-----------------|------------|
| <b>yr</b>              | temp_min           | sensor.<br>yweather_temperature_min                 | 最低温度       | 最低温度         |            |
|                        | temp_max           | sensor.<br>yweather_temperature_max                 | 最高温度       | 最高温度         |            |
|                        | wind_speed         | sensor.<br>yweather_wind_speed                      | 风速           | 风速            |            |
|                        | pressure           | sensor.<br>yweather_pressure                        | 气压           | 气压            |            |
|                        | visibility         | sensor.<br>yweather_visibility                      | 能见度         | 能见度          |              |
|                        | humidity           | sensor.<br>yweather_humidity                        | 湿度           | 湿度            |            |
|                        | temperature        | sensor.<br>yweather_temperature                     | 当前温度       | 当前温度        |              |
|                        |                    |                                                     |                |                |            |
| <b>broadlink<b>        | tv                 |                                                    | 客厅电视(TV)    |                 |            |
|                        | av                 |                                                    | 客厅电视(TV)    |                 |            |
|                        | switch slot        | switch.slot1                                       | slot1鱼缸灯     |                 |   switch 2 |
|                        | switch slot        | switch.slot2                                       | slot2鱼缸过滤器  |                 |   switch 3 |
|                        | switch slot        | switch.slot3                                       | slot3鱼缸加热棒  |                 |   switch 4 |
|                        | switch slot        | switch.slot4                                       | slot4其他        |                 |   switch 5 |
|                        |                    |                                                     |                |                 |            |
| <b>xiaomi_aqara<b>     | gateway            | light.<br>gateway_light_7811dcb38873                | 小米网关灯      | 小米网关灯       | light 1  |
|                        | socket             | switch.<br>plug_158d0001b8a062                      | 小米插座        | 小米插座         | socket 1 |
|                        | motion sensor      | binary_sensor.<br>motion_sensor_158d0001c1d36a      | 人体传感器      | 人体传感器       |            |
|                        | wireless switch    | light.<br>gateway_light_7811dcb38873                | 无线开关        | 无线开关         | switch 1 |
|                        | door window sensor | binary_sensor.<br>door_window_sensor_158d0001bf930f | 门窗传感器      | 门窗传感器       |            |
|                        | illumination       | sensor.<br>illumination_7811dcb38873                | 照明            | 照明            |            | 
|                        |                    |                                                     |                 |                 |          |
| <b>emulated_hue<b>     | Amazon Echo        |                                                    |                 |                 |           |
|                        |                    |                                                    |                 |                 |           |
| <b>google_assistant<b> | Google Assistant   |                                                    |                 |                 |           |
