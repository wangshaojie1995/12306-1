# 12306-Python
一个使用Python编写的12306高铁爬虫项目，并通过Flask框架提供Web服务
## 当前实现的功能:
### 登录
- [x] 扫码登录
- [ ] 账号密码登录(即将上线)
### 个人行程
- [x] 本人车票查询(需扫码验证)
- [x] 获取全部车票
### 车站
- [x] 车站大屏
- [x] 获取并更新站点
### 车票(查票、抢票)
- [x] 查询火车票、高铁票
- [ ] 定时抢火车票、高铁票

## 计划实现功能
### UI
- [ ] 添加UI页面
### 行程提醒
- [ ] 接入第三方推送,实现检票发车提醒
- [ ] 添加列车时刻表,发车前检测是否延误

## 特性
- **实时查票**：用户可以通过Web界面查询指定日期和路线的火车票信息。
- **个人车票查询**：输入用户信息后，可以查询到个人已购车票详情。
- **车站大屏信息**：获取车站大屏，实时展示车站检票口、列车到站、离站信息。
- **车站信息获取**：提供接口获取中国铁路车站的基本信息。

## 技术栈
- **Python**: 使用Python进行爬虫开发，利用其丰富的库支持。
- **Flask**: 基于Flask框架搭建Web服务，提供友好的用户交互界面(UI界面火速添加中)。
- **Requests**: 用于发起网络请求，获取12306网站数据。

## 安装与使用
1. 克隆本项目到本地, Windows可以直接使用`TrainAssistant.exe`。
   ```bash
   git clone https://github.com/2375137/12306.git
   ```
2. 安装依赖。
   ```bash
   pip install -r requirements.txt
   ```
3. 运行Flask服务。
   ```bash
   python app.py
   ```
4. 访问 `http://localhost:5000` 开始使用。
5. 接口请参照 `router\router.py` 进行查询

## 注意事项
- 本项目仅供学习和研究使用，请遵守相关法律法规，不得用于商业用途。
- 为减轻12306服务器压力，请合理使用爬虫功能。

## 许可证
本项目遵循Apache2.0许可证。
---
