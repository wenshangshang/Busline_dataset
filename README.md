# -
本项目为公交线路数据采集、处理、储存、可视化的合集，会定时更新！
公交信息网站：
https://www.8684.cn
公交站点、线路坐标来源于高德地图

# 文件说明
- BusLine.py 主程序，只需要在本程序上进行城市的修改即可获取对应城市的数据
- citybus.py 本程序用来获取BusLine程序传入的对应城市所有公交线路名称
- conversion_geo.py 本程序用于处理下载好的数据进行XY转点、点集转线、属性连接等工作，并完成数据储存为shp\geojson的工作
- ChineseAdminiDivisionsDict.py 本程序用于查询城市的高德编码（邮政编码）
- WGS1984.py 本程序用来进行坐标转换，只支持高德坐标（火星坐标）转换为WGS1984坐标系
