// ==UserScript==
// @name			Microsoft sayfalarını otomatik olarak Türkçe sürümüyle aç
// @namespace		klavyelibey
// @description		Tüm Microsoft sayfalarını otomatik olarak Türkçe sürümüyle açar
// @include			http://*.microsoft.com/*
// @include			https://*.microsoft.com/*
// @run-at			document-start
// @grant			none
// @version			1.0
// ==/UserScript==

var abc = window.location.href.split("/");
if (abc[3] !== "tr-tr")
{
	window.location = "https://www.microsoft.com/tr-tr/" + abc[3] + "/" + abc[4];
}
