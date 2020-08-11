# Power-Apps-Doc

### Description

**Power Apps** is a Microsoft tool. Its part of the Microsoft family with Power BI, Microsoft Flow, as well as Power Apps of course. It builds web-based applications that can be seen either to a native application or on a web page through things like Shared Point. It is a suite of apps, services, connectors and data platform that provides a rapid application development environment to build custom apps for your business needs. You can also store a native application called Power Apps and inside that application, you can choose your application and run those internal apps.

#### What Power Apps is

Apps built using Power Apps provide rich business logic and workflow capabilities to transform your manual business processes to digital, automated processes. They also have a responsive design, and can run seamlessly in browser or on mobile devices (phone or tablet).

It is definitely meant for internal usage. It’s a replacement for things like onboarding applications, so you might have one for Task Management, Task Inspection, etc.

#### What Power Apps is not

It is not a replacement for things like Dot Net where you’re building a massive application that has so much business logics.

It does support business logics, it does have lots of extensibilities, but not as compared to Dot Net.

### Components of Power Apps

There are four major components of Power Apps:

* Canvas apps: This provides a blank canvas (highly tailored interface) for either web, mobile and tablet applications and connect it to your choice of more than 200 data sources. Here you build from scratch.

* Model-driven apps: This starts with your data model. It builds up from the shape of your core business data and processes in the Common Data Service to model forms, views, and other components. You create a model-driven app from the Power Apps site. All you need do is provide the data and Power App builds up an app around the provided data.

* The others are: Portals and Common Data Service.

### Signing up And Signing into Power Apps

You sign up on Power Apps using your/an organisation’s email address. _Individual’s email address is not accepted_. Then enter your password.

Thereafter, you can login with same details.

![Power App Home Page](/images/home.png)
_Home Page_


### Building Model-Driven App

I have created a basic excel sheet (named Excellence) to hold the model (data) our app will be using. The excel sheet is uploaded to Microsoft OneDrive.

![Add new connection Page](/images/basic_excel_sheet.png)
_Excel sheet used as data source_


Click the arrow button `->` on the home screen to display the page below.

![Add new connection Page](/images/add_connection.png)
_Add new connection page_


Click `+ New Connection` and select the data source(s) of your choice. In our case, we select OneDrive. Then navigate to where the excel sheet is in your OneDrive account.

![Add new connection Page](/images/select_ondrive.png)
_Select our basic excel sheet (Excellence)_


Select the table and click on `Connect`

![Add new connection Page](/images/select_table.png)


Power App builds a basic app with a simple UI based on the above data model. It can always be edited and more features added or removed.

![Add new connection Page](/images/app_screen.png)