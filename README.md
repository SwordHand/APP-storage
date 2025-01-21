# Open-API 文档

## 简介

Open-API 是一个强大的工具，允许用户自定义 API 请求并以美观的方式展示返回的内容，包括图片、视频、语音和文本。通过简单的配置，用户可以解析 API 返回的 JSON 数据，并根据需要显示特定的字段。Open-API 提供了友好的用户界面，支持多种媒体格式的展示和下载。

## 特性

- **自定义 API 请求**：用户可以根据需求自定义 API 请求，灵活获取数据。
- **多媒体支持**：支持展示图片、视频、语音和文本，满足多样化的展示需求。
- **JSON 解析**：轻松解析 API 返回的 JSON 数据，指定需要展示的字段。
- **美观的 UI**：提供友好的用户界面，确保良好的用户体验。
- **下载功能**：支持下载展示的图片和视频，方便用户保存内容。

## 安装

要使用 Open-API，请按照以下步骤进行安装：

[点击前往下载](https://github.com/SwordHand/Open-API/releases)


## 使用教程


**图片示例**

在你需要填写图片API部分

1.填写你的配置名称如"图片".

2.填写你的API配置，API自己在网上找，列如https://<域名>/image.php.

3.json解析配置，在浏览器输入你的API会返回json列如：

```json
{
   "code": 200,
   "image": "https://<域名>/image.png"
}
```
你现在要获取image中的图片url，json字段就填写"image"字段保存配置即可

**多字段**

例如：
```json
{
   "code": 200,
   "data": {
        "image": "https://<域名>/image.png"
}
```
填写data,image字段即可


## 列表模式

返回的json如：
```json
{
   "code": 200,
   "images": [
   "https://<域名>/image.png",
   "https://<域名>/image.png",
   "https://<域名>/image.png",
   "https://<域名>/image.png"
   ]
}
```
即可开启列表模式
