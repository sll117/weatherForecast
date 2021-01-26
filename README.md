# weatherForecast
在Andorid客户端实现一个天气预报APP
1、在手机中包含主视图和细节视图，主视图显示连续多天的天气预报简讯，用户在主视图中点击某一天的天气简讯以后，跳出细节视图，显示用户选定天天气的详细信息。 
2、 在横屏模式下，当用户点击某一天的天气预览以后，直接在界面右边显示当天天气的详细信息。 
3、 主视图中包含Map Location和setting选项，通过”Map location” 选项，可以调用手机中安装的地图应用显示当前天气预报所对应的位置。
用户可以通过 setting选项可以修改天气预报的位置，温度的单位（华氏度、摄氏度）以及是否开启天气通知。如果setting选项中的天气通知选项打开，会定期发送通知消息，其中显示当天的天气简讯。
4、 利用SQLite对天气预报数据进行持久化保存，如果网络不可用的情况下，从SQLite 中提取天气预报数据。
5、 Web API请使用heweather：
https://www.heweather.com/documents/api/s6/weather-forecast

