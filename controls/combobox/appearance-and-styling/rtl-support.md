---
title: RTL Support
page_title: RTL Support | UI for ASP.NET AJAX Documentation
description: RTL Support
slug: combobox/appearance-and-styling/rtl-support
tags: rtl,support
published: True
position: 11
---

# RTL Support



## 

__RadComboBox__ provides support for locales that read right-to-left. All you need do to achieve a RTL look and feel is mark the __RadComboBox__ instance with __dir="rtl"__.

````ASPNET
	    <telerik:radcombobox 
	        id="RadComboBox1" 
	        runat="server" 
	        height="140px" 
	        skin="Default"
	        width="150px" 
	        contentfile="~/App_Data/combobox.xml" 
	        showtoggleimage="True" 
	        dir="rtl">
	    </telerik:radcombobox>
````



This definition results in the following appearance:

![ComboBox RTL](images/combobox_rtl.png)

See and online demo of the RTL support at [Right-to-Left Support](http://demos.telerik.com/aspnet-ajax/ComboBox/Examples/Functionality/Rtl/DefaultCS.aspx).