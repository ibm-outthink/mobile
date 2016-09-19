# Mobile

The IBM Bluemix cloud ewnvironment provides several mobile technologies and services that can be used for creating mobile apps. This short guide will help mobile app developers select the products that best fit their needs.

# Developer Journey

##Title: How do I make my enterprise data available as an API to my mobile application
Guidance: What business problem does this solve.  It is a generalized use case, and should be technology agnostic. It should be descriptive so that developers can associate it with the problem they are addressing.  similar to a use case but more generalized, for example, 

##Audience: Intermediate NodeJS developers
Guidance: Assumptions about the knowledge of the developers that would be undertaking this developer journey

##Time: 4 hours
Guidance: Time to complete the journey

Journey description: Step by step instructions to lead a developer through the journey. 
Guidance: Each step could be a tutorial or a youtube video or a tutorial or similar that describes that portion of the journey.  Each journey could be a single step or more then one step.  Each step should lead the developer onto the next step.  Clear instructions with links. 

##Pre-requisites (Journeys): 
Guidance: Describes other learnings and journeys that are recommended prior to undertaking this journey. 

##Sample code: location on github with sample code snippets
Guidance: Snippets should preferable be contained in a simple example that highlights the journey and nothing else.  Complete applications will be a nightmare to maintain. 

##Target utilization: is it going to be used for workshop, blast, meetups, hackathon, etc.





# What Use Case are you interested in?

<ol>
<li>Offline First
<ol>
<li><a href="https://blog.fogcreek.com/eight-fallacies-of-distributed-computing-tech-talk/">The 8 Fallacies of distributede computing</a>
<li><a href="https://developer.ibm.com/clouddataservices/offline-first/">Offline First</a>
<li><a href="https://youtu.be/yZuGCrJbIJs">Offline-first apps with PouchDB - Fluent 2016</a>
<li><a href="https://developer.ibm.com/clouddataservices/offline-first/">Offline First 2</a>
<li><a href="https://www.ibm.com/developerworks/cloud/library/cl-bluemix-famous-mobile/">Automate Famo.us mobile apps with Cloudant on Bluemix</a>
</ol>
<li>Cognitive apps using Watson serviuces on Bluemix
<ol>
<li><a href="https://github.com/watson-developer-cloud/ios-sdk">Watson Developer Cloud iOS SDK</a>
<li><a href="https://github.com/watson-developer-cloud/speech-android-sdk">Watson Developer Cloud Android SDK</a>
</ol>
<li>Mobile and Wearables
<ol>
<li><a href="https://developer.ibm.com/bluemix/2016/07/06/you-exercise-and-bluemix-will-count/">You do the exercise, Bluemix will do the counting</a>
</ol>
</ol>

#How do you want to create your mobile app?
## Option 1) For coders: Use Bluemix Mobile (Bluemix Services Starter) to create Mobile apps with Bluemix services
 
 <a data-flickr-embed="true"  href="https://www.flickr.com/photos/dpu/29385313710/in/dateposted-public/" title="MobileFirstServicvesStarter"><img src="https://c7.staticflickr.com/9/8095/29385313710_63671ff7d3_z.jpg" width="640" height="239" alt="MobileFirstServicvesStarter"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>
 
 <a href="https://console.ng.bluemix.net/catalog/starters/mobilefirst-services-starter/">Mobile First Services Starter</a> allows you to develop, deploy, and scale server-side JavaScript® apps with ease. The IBM SDK for Node.js™ provides enhanced performance, security, and serviceability.
 
 ###Services included:
 <ol>
 <li><a href="">SDK for Node.js</a>
 <li><a href="https://console.ng.bluemix.net/catalog/services/mobile-client-access/">Mobile Client Access</a>
 <li><a href="https://console.ng.bluemix.net/catalog/services/push-notifications/">Push Notifications</a>
 <li><a href="https://console.ng.bluemix.net/catalog/services/cloudant-nosql-db/">Cloudant NoSQL DB</a>
 </ol>
 
### Sample applications: 

## Option 2) For non-coders: Use the <a href="https://appbuilder.ibmcloud.com/">Mobile App Builder </a> to create catalog apps. 
The Mobile App Builder makes it super easy to quickly create mobile GUIs without coding. You can then connect the user interface to backend data sources, again without coding.  

For a tutorial on using the Mobile App Builder, please check <a href="https://console.ng.bluemix.net/docs/services/apiconnect/apic_tutorial.html#apic_tutorial">this linke<a>
<p>
<img src="https://developer.ibm.com/bluemix/wp-content/uploads/sites/20/2016/04/1-2.png">

Launch <a href="https://new-console.ng.bluemix.net/mobile/"> Mobile App Builder</a>

Step 1) Create the GUI from templates<p>
Step 2) Use the <a href="https://github.com/ibm-bluemix-mobile-services">IBM Mobile Dashboard Store Catalog Backend</a> 
    It uses an API Connect and Node.js runtime with the Cloudant NoSQL DB, Object Storage, Mobile 
    Client Access, Push Notifications, and Mobile Analytics services on Bluemix. 

   The template exhibits common architectural design patterns that developers can use to model their backend    
   on Bluemix for mobile applications. 
 
   This backend has been created to support the new IBM Mobile Dashboard Store Catalog template. It has 
   the ability to browse a list of products and supports the viewing of images for each item in the product list

A step by step description on this link: https://github.com/ibm-bluemix-mobile-services/mobile


dW articles on this process:
<table>
<tr><td>https://developer.ibm.com/bluemix/2016/07/13/bluemix-mobile-creating-store-catalog-app-part1/<td>
<tr><td>https://developer.ibm.com/bluemix/2016/07/14/bluemix-mobile-integrating-custom-backend-part2/<td>
<tr><td>https://github.com/ibm-bluemix-mobile-services/mobiledashboard-storecatalog-backend<td>
<tr><td>https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-swift-core<td>
</table>



### Additional mobile services on Bluemix:
 
 <ol>
 <li><a href="https://console.ng.bluemix.net/catalog/services/mobile-analytics/">Mobile Analytics</a>
 <li><a href="https://console.ng.bluemix.net/catalog/services/mobile-application-content-manager/">Mobile Application Content Manager</a>
 <li><a href="https://console.ng.bluemix.net/catalog/services/mobile-foundation/">Mobile Foundation </a> For more on the Mobile Foundation see under Enterprise Development. 
 </ol>
 
## Option 3a) Use <a href="https://github.com/watson-developer-cloud/ios-sdk">Watson Developer cloud iOS SDK</a> to create Swift mobile apps with IBM Watson Services
 
 <a data-flickr-embed="true"  href="https://www.flickr.com/photos/dpu/29385375310/in/dateposted-public/" title="Watson Developer Cloud iOS SDK"><img src="https://c7.staticflickr.com/9/8077/29385375310_d21e6e7840_z.jpg" width="640" height="125" alt="Watson Developer Cloud iOS SDK"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>
 
 
## Option 3b) Use <a href="https://github.com/watson-developer-cloud/android-sdk">Watson Developer Cloud Android SDK</a> to create Java mobile apps with IBM Watson Services

<a data-flickr-embed="true"  href="https://www.flickr.com/photos/dpu/29565094272/in/dateposted-public/" title="Watson Developer Cloud Android SDK"><img src="https://c1.staticflickr.com/9/8815/29565094272_bb9f27e775_z.jpg" width="640" height="109" alt="Watson Developer Cloud Android SDK"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>


## Option 4) Mobile Foundation and <a href="enterprise.md">Enterprise Mobile Development</a>

# Additional knowledge sources
<a href="https://www.ibm.com/developerworks/learn/mobile/index.html">IBM developerWorks Mobile development</a>
