# AssetAssistant

Asset Assistant includes three distinct components, a web app, web API and a mobile app developed as a cross-platform application for IOS and Android. This application is developed for an energy company in New Zealand. The main aim of this application is to assist workers of the company on how to use different machinery (assets) as well as provide information about the assets. The technology stack used in developing this application is Xamarin.Forms for developing the cross-platform mobile app for IOS and Android. HTML, Bootstrap, .Net Core and C# for the web app and .Net Cor, C# and SQL Server for the web API.

The idea for this app comes for a similar concept’s used in the Gym’s, that is when a person is new to the gym, there are multiple machines used to train different body parts. Each machine in the gym has a QR code if you do not know how to use a machine or require more information you scan the QR code via your phone and there you have detailed information about that particular machine. Similarly, The Energy company wanted to develop a system where they would have QR codes on different assets throughout the company and anyone with the Asset Assistant mobile app will be able to scan the QR code and get the information about the asset on their phone. By developing this system, the company would have a single point to manage their asset’s documentation. As well as they can update or publish new documentation rapidly as there is no physical effort required as in they would simply replace the document associated with the QR code with the updated document and that’s it, next time the user of the asset scan’s the QR Code the user would have the lasted copy of the documentation. Below I have provided a brief description of each component of the system.

### Web App for Managing Asset Documentation:
The Web App is a lightweight web application frontend used for CRUD operations of assets documentation. This web app is for administrative use. To associate documentation with an asset, the administrator accesses the web portal, create a new entry for the asset documentation. The asset documentation will be stored in the database and a QR code for that asset documentation will be generated. The administrator can now print the QR code and place it on the asset.

* Below image shows the dashboard view. Here we can see the multiple documents associated with different assets. You can quickly manage each document by hovering over the three-dot icon and additional options will be displayed. Additional you can also click on individual row to navigate to individual asset page.

![](ReadMeImages/WebApp1.png)

* For adding a new asset documentation, simply click on the “Add Asset” button on the top right corner of the dashboard view. You will see a dialog box pop-up, fill in the details and click “Add” button.

![](ReadMeImages/WebApp2.png)

* Your asset documentation will be saved in the database and you will be navigated to uploaded asset page as shown in the image below.

![](ReadMeImages/WebApp3.png)
