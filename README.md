# api
常用的api接口
接口名称
1) 请求地址
https://www.blackcatw.com/api/?name=WZPDF&url=需要生成的URL地址

2) 调用方式：HTTP get
3) 接口描述：
网页转PDF接口，本服务器是海外服务器
查看更多关于 服务器 的文章
，如果请求的目标网站屏蔽了海外访问，将无法生成PDF文件！文件只会保留当天，每天0：10系统自动清理前一日的PDF文件！！！ 生成时间大概需要5到10秒左右
4) 请求参数:
GET参数:
字段名称	字段说明	类型	必填	备注
name	接口名称	string	Y	WZPDF
url	目标地址	string	Y	URL地址
5) 请求返回结果:
{
    "status": "success",
    "pdf": "https://www.blackcatw.com/api/PDF-20230323/73574b80d03cadfa2f1ce9eb4e0b47d98771e93327.pdf",
    "timeconsuming": 6.89
}
6) 请求返回结果参数说明:
字段名称	字段说明	类型	必填	备注
status	状态	string	Y	成功：success 失败：fail
pdf	在线预览地址	string	Y	生成成功请立即下载，文件在本服务器只会保留当日，每天0：10清理前一天的PDF
timeconsuming	生成耗时（秒）	string	Y

请求地址：https://blackcatw.com/api

请求方式：GET

参数                   说明

name         ADDRESS

（建议海外服务器请求，无延迟！）

例如：https://www.blackcatw.com/api/?name=ADDRESS

返回信息：

地址信息api接口 其他接口 第1张
