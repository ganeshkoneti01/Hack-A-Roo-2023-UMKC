# Hack-A-Roo-2023-UMKC
# LINK TO PROJECT-
https://www.dropbox.com/scl/fo/88jx7r1cualosd4wv488p/h?rlkey=rhaq4zo6du1raswxmuz5l9wzu&dl=0



ABSTRACT: Blood donation is crucial since it happens frequently that patients who need blood do not get it in a timely manner, which can result in death. Serious accidents, dengue or malaria patients, or organ transplant recipients are a few examples. With the frequency of incidents increasing, the need for blood is urgent. We frequently read articles and comments mentioning the urgent need for blood in an emergency. In order to save a life, the Blood must be accessible quickly. This project intend to make a geolocations ,and analysis of data which can provide the information about the available Blood Donors in the Same Locality. Using Flask-a backend framework , implemented a web application which involves information about the donars of the blood group. The dataset used in our study is collected based on different blood groups from different states, redefined the dataset and eliminated false information about the donors.Also located the latitude and longitude columns in the dataset using package geopy. Based on blood group, the information about the donor will be available.

Existing system: In the existing system , there are few implementations done on blood donation management system , prediction models on blood , blood donation App . where all of these gives a platform to register and give the details of the individuals so that a blood bank can be formed.

In these systems , the process of getting the details of the donars is not interactive.

Drawbacks:

In the Existing system, user need to register and gives details by thier own which may lead to reliability.

Users may not willing to get registered even though they are ready to donate blood.

proposed System:

This proposed system intend to make geolocations and analysis of data which can provide the information about the available blood donars. Using the python framework, an attempt has been made to display a web page which shows the open street maps where donars are available. This interactive maps gives a point of each donars on the maps where donars information is displayed like Blood group, address, mobile number to contact.

Advantages:

Easy and simple to use . classic way of locating the blood donars on the maps. Tranparent to all and communication with the donars makes simpler! Importantly, User can know how far the donar is present from the user's loaction.

Software requirements:

Operating system: windows coding language: Python Tool: Python Front end: HTML Back end: Python Server: Web Server-Flask

packages: Geopy folium pandas flask

Modules:

Home Page Results

Description: Home page:

Home page takes 2 inputs from the user who are looking for the blood.

Required blood group
Location where the blood is required
Results: Results page displays the geolocations which is an open street map with the plots on it where each plot indicates the required blood group with the additional details of the donors.

Conclusion:

The project BLOOD CONNECTIONS is all about connecting the people who are in need of blood in an emergency. On a daily basis , we see a lot a social media posts , stories who are looking for blood donors. Here, this idea of blood connections came from this real time problems . "A problem well stated is a problem half solved.” --John Dewey

To Sum up, The goal of this project is to create geolocations and analyze data that can provide information about blood donors who are accessible in the area.

Future Scope:

In the future, this project can be integrated with online blood banks, blood bank management system so that real time data will be availbale. For instance, Dataset will be updated with the new blood groups from the different resources. Moreover, implementing the additional features like- System can be linked by internet,so the other hospitals can use the data.System can be expanded with availability over worldwide.Reaching as close as possible of donor from emergency zone.A smart phone application of the system can be made.Providing donor an option of change his/her availability.
