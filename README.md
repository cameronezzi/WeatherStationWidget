#Weather Station Widget

This is a custom ArcGIS Web App Builder (Developer Edition) widget. It is designed to work with a Weather Station feature service in an ArcGIS Online Web Map. The widget pulls and summarizes weather data pulled from a table related to the Weather Station feature service. Below is a sample of the widgets' user interface. This widget was created internally as part of a project to educate students on using a microcomputer (Rasberry Pi) to pull weather data  from a weather station and push it to a REST API using python. Check out the full project here:

<Change project name, add URL in brackets>
[Project Name Here]()

<Add screenshot of Widget in Action>
![Widget UI](http://placehold.it/350x150)

##Installing The Widget

###1 - Install Web App Builder (Developer Edition)

In order to install this widget you will need to install the ArcGIS Web App Builder (Developer Edition). The installation requires an ArcGIS Online Subscription account. You can start a free 60-day trial by contacting Esri [here](http://www.arcgis.com/features/free-trial.html?origin=arcgis).

Steps to [install Web App Builder (Developer Edition)](https://developers.arcgis.com/web-appbuilder/guide/getstarted.htm).

###2 - Download the Widget Code

Download a zipped copy of the source code from this repository to your Web App Builder machine. Once extracted, place the **WeatherStationWidget** folder in the appropriate location inside the Web App Builder (Developer Edition) directory:


C:\Users\\\<local user>\Documents\WebAppBuilderForArcGIS\\**client\stemapp\widgets**

###3 - Add the Widget to an Application

Follow the steps on Esri's Developer site to [create a New App](https://developers.arcgis.com/web-appbuilder/guide/build-your-first-app.htm) and [Adding a Widget](https://developers.arcgis.com/web-appbuilder/guide/widgets-tab.htm) to an application. You should see the option for the icon for Weather Station Widget in the widget list.

<Add screenshot of Widget in Widget List>
![Photo of Widget List](http://placehold.it/350x150)

###4 - Modify the Configuration

Once you select the widget from the widget list you will need to modify the configuration parameters to use the appropriate Weather Station feature service. Below is a key - value map to help you out.

<Add screenshot of Config Page>
![Photo of Config Page](/../master/README_img/Configuration.png?raw=true)







