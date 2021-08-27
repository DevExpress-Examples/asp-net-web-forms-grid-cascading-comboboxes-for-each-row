<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128541045/13.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4395)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# How to implement cascading ASPxComboBox controls for each ASPxGridView row
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e4395/)**
<!-- run online end -->


<p>1) Use the technique described in the <a href="https://www.devexpress.com/Support/Center/p/K18282">K18282: The general technique of using the Init/Load event handler</a> KB Article to specify the ClientInstanceName property based on the related row's VisibleIndex;<br />2) Use the technique described in the <a href="https://www.devexpress.com/Support/Center/p/E2355">A general technique of using cascading ASPxComboBoxes</a> example to implement the "cascading" behavior between a pair of ASPxComboBox controls defined within the same row.</p>

<br/>


