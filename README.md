<img src="https://i1.wp.com/nearbyshops.org/wp-content/uploads/2018/12/Untitled-design-e1545575054544.png" width="170"> 


Nearby Shops API (JSON based REST API)
====================================

This is the server side component of the Nearby Shops e-commerce software. For more information about this project please visit https://nearbyshops.org


Screenshots
-----------

<img src="https://nearbyshops.org/wp-content/uploads/2018/12/Screenshot_20181222-181246-512x1024.png" width="208"> <img src="https://nearbyshops.org/wp-content/uploads/2018/12/Screenshot_20181222-181259-512x1024.png" width="208"> <img src="https://nearbyshops.org/wp-content/uploads/2018/12/Screenshot_20181222-181405-512x1024.png" width="208"> 

<img src="https://nearbyshops.org/wp-content/uploads/2018/12/Screenshot_20181222-181453-512x1024.png" width="208"> <img src="https://nearbyshops.org/wp-content/uploads/2018/12/Screenshot_20181222-181504-512x1024.png" width="208"> <img src="https://nearbyshops.org/wp-content/uploads/2018/12/Screenshot_20181222-181513-512x1024.png" width="208">


Installation Guide
--------------------
Installation guide is available for installing Nearby Shops API on the Could Hosting Service like Digital Ocean or AWS using Ubuntu 16.04 Server.

For the installation guide please refer the Developer Section on https://nearbyshops.org


Technology Stack
------------------------
The server side component is a JSON Based Rest API built with Java

1. Postgres DB as a Primary Database
2. Jersey Framework – (JAX-RS Implementation) for REST API Endpoints
3. Jetty Server as an Embedded HTTP Server in the app
4. HikariCP for Connection Pooling
5. Thumbnailator for Generating resized versions of Images and thumbnails


Third Party Integrations
-------------------------
SMS-OTP Integration using msg91, Open-Signal (for push notifications), Fabrio.io (crash reporting)


Download
--------

Get it from Google play store

<a href="https://play.google.com/store/apps/details?id=org.nearbyshops.enduserappnew"><img class="alignnone" src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" alt="Get it on Google Play" width="219" height="90" /></a>

Demo
-----

Download the nearby shops android app from the above link and then set a fake location. 

The nearby shops currently have shops available in only few cities. If you are living in a city where shops are not available. You need to fake your location and set it to some location where the shops are available. 

Use any location faker app which you can download from playstore and set your location to "Hyderabad, India". You will see some shops and items visible in the nearby shops app. 


Client Side Repositories
--------------------------

End-User android app : https://github.com/SumeetMoray/Nearby-Shops-End-User-Android-app
Shop-Owner android app : https://github.com/SumeetMoray/Nearby-Shops-Shop-Owner-app
Admin android app : https://github.com/SumeetMoray/Nearby-Shops-Admin-App



License
=======

    Copyright 2018-19 Bluetree Software LLP.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

