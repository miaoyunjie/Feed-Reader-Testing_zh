## 订阅阅读器测试

### 项目说明

使用单元测试框架jasmine对项目进行单元测试

### 运行方式

* 在浏览器中打开index.html文件
* 网页打开后，用例显示在页面下方，自动运行
* 可点击指定测试用例，手动运行测试
* 测试用例运行成功，显示为绿色
* 测试用例运行失败，显示为红色，并显示失败原因

### 注意

* 实际测试过程中，存在请求https://rsstojson.udacity.com/parseFeed 接口失败情况，此时需重新刷新
* 由于https://rsstojson.udacity.com/parseFeed 接口请求响应时间超过5s，jasmine的默认等待时间为5s，所以在jasmine中修改默认等待时间20s