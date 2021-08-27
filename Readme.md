<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128599091/2019.2)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E108)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Reporting_how-to-convert-an-xtragrid-to-an-xtrareport-at-runtime-e108/Form1.cs) (VB: [Form1.vb](./VB/Reporting_how-to-convert-an-xtragrid-to-an-xtrareport-at-runtime-e108/Form1.vb))
* [XtraReport1.cs](./CS/Reporting_how-to-convert-an-xtragrid-to-an-xtrareport-at-runtime-e108/XtraReport1.cs) (VB: [XtraReport1.vb](./VB/Reporting_how-to-convert-an-xtragrid-to-an-xtrareport-at-runtime-e108/XtraReport1.vb))
<!-- default file list end -->
# How to convert an XtraGrid to an XtraReport at runtime

<b>NOTE:</b> Use the <b><a href="https://docs.devexpress.com/XtraReports/DevExpress.XtraReports.ReportGeneration.ReportGenerator">Report Generator</a></b> tool to convert a <a href="https://docs.devexpress.com/WindowsForms/DevExpress.XtraGrid.GridControl">Grid Control</a> to a <a href="https://docs.devexpress.com/XtraReports/DevExpress.XtraReports.UI.XtraReport">Report</a> with one line of code. See: <a href="https://docs.devexpress.com/WindowsForms/114962/controls-and-libraries/data-grid/export-and-printing/advanced-grid-printing-and-exporting">Advanced Grid Printing and Exporting</a>.


<i>Applies to older versions:</i>
<p>This example demonstrates how to dynamically create a report based upon the GridControl at runtime.  This means that all filtering and sorting conditions selected in the grid are also applied in a report. To accomplish this task, it is necessary to create a report with all the necessary bands, bind it to a data source and adjust all the necessary options.</p>


<br/>



