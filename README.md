# Bluetalk

A wireless location App for finding your friends

Team members: Adi Alaluf, Yuval Ohana, Lonnie berry

The problem: When attending an event or party accompanied by friends, an Internet connection may be weak or not working at all (due to congestion), a matter of losing touch between team members. There are times when we want to stay safe, such as spending time in a club, spending time with a family at a show or wedding, etc., with an emphasis on keeping in touch in situations of distress.

The solution: The Bluetalk app allows you to communicate with your friends in real time when the internet connection is weak or non-existent, as well as view their location on the map up to 100 meters between friends.

Any user of the app can create events. When creating the event, the user will be asked to choose a name, description, location for the event as well as invite additional friends who are users of the app.

The next step, which should be done while the user has an internet connection, is to download the map of the event area and the information about the participants in the event.

During the event, participants will see the location of their friends for the event on the map, will be able to receive and send messages to the other participants as well as activate a distress button that will send a distress alert to all their friends.

To achieve the passing of information we described we use Google's Nearby Connections API. This API is a peer-to-peer networking API that allows apps to easily discover, connect to, and exchange data with nearby devices in real-time, regardless of network connectivity. It uses a high level of protocol on top of Bluetooth and WiFi that acts as a socket. Devices are able to advertise, scan, and connect to each another.

Also in the Application we use Cloud Firestore to store all the list of Events and users of the Application.
