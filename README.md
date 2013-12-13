Atlanta SeeClickFix Project - CS109 / STAT121 - Data Science - Harvard University
===========

View the website at  - www.seeclickfix-atlanta.weebly.com - for full overview of the project.

=====

About and Thank You

This project was undertaken as part of the CS109 / STAT121  Data Science course at Harvard University.  The four person team is comprised of students from three different graduate schools around the university interested in civic data and data science.

We would like to thank SeeClickFix for providing a great API and access to their data.  Additionally, we would like to thank the City of Atlanta for their interest and assistance.  Finally, thank you to the professors and teaching fellows of CS109 who taught us and supported us in carrying out this project.

The bulk of our analysis was conducted in Python using numerous libraries including matplotlib, pandas, numpy, urllib, json, scipy, datetime, and networkx.  Thank you to the developers who made those libraries possible.  Additional spatial analysis and data processing was conducted in ArcMap.

============

iPython Notebooks

We divided our process notebook into five parts representing the different aspects of our analysis:

  1)	Introduction and exploratory data analysis: “1. SeeClickFix.ipynb”
  2)	Network analysis: “2. SeeClickFix_Network.ipynb”
  3)	Classification analysis (status): “3. SeeClickFix_Classification _Status.ipynb”
  4)	Classification analysis (type): “4. SeeClickFix_Classification _Type.ipynb”
  5)	Regression analysis: “5. SeeClickFix_Regression.ipynb”

===========

Datasets

We use four datasets:

1)	“SeeClickFixData_Primary”: our primary dataset, which lists each report submission by users of SeeClickFix, as well as the incident location, user id, and description. 
2)	“SeeClickFixData_Issue_History_ATL”: all the comments made by users for each report submitted.  </t>
3)	“SeeClickFixData_Users_ATL”: for each SeeClickFix user, the number of issues they have commented on, chosen to follow, and closed, their number of “civic points,” and whether they are authorized to acknowledge other reports.
4)	“SeeClickFixData_GISExport”: this spreadsheet connects the report submissions to their geographic location, namely city and neighborhood (if in Atlanta).


===========

Image

There is one image that was the output of network analysis done in Gephi.
