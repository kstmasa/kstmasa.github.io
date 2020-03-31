---
title: 'ASP.NET : SQL Server Data Types 對應到 C# ASP.NET'
layout: post
author: Masa
tags: SQL Server Data Types, SQL Server資料型態, C# 資料型態
comments: true
date: '2020-03-31 11:37:00'
---

下列紀錄常用到的SQL Server資料型態以及對應到C#寫法的型態

|SQL Server資料型態|C# 資料型態|
|---------|------|
|binary|byte[]|
|bit|bool|
|char<br />nchar<br/>ntext<br />nvarchar<br />text<br />varchar|string<br />char[]|
|date|DateTime|
|datetime|DateTime|
|float|double|
|int|int|
|smallint|short|
|tinyint|byte|
|uniqueidentifier|Guid|

[來源網站](https://docs.microsoft.com/zh-tw/dotnet/framework/data/adonet/sql-server-data-type-mappings)
