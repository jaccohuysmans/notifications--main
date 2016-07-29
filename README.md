
#Notifications

<sub>Note: This main repository contains only a readme to explain the project, links to the actual sources are found further down.</sub>

##Why?
The Notifications project is a project that grew out of a technical assessment I went through during a job interview once.  I decided to put up it's own repositories for it and expand it using different technologies each time. Hopefully this way it will be of some use to someone in the future and maybe inspire others to add more technology variants in the future.

##What?
The technical assesment consisted, among other things, out of an evaluation of the following assignment:
Build a mobile client that can store a users location together with some text to a backend system which persists it in some form. Also develop a management tool that administrators can use to see on a map which notifactions were stored at what location.

##How?
I decided to developed an Android app, a  Play-Java based backend, and for managemnt a web app using ExtJs. Since I was being interviewd for a job as a (java) backend developer I focused on functionality rather then user experience optimisation. The apps are therefore pretty basic. I also opted to persist the data using ElasticSearch for no other reason then that I realy like it. :smile:
The backend provides a REST based API that exchanges data with its clients using Json. Both the Android app and the management app use this API.

####Current available implementations
Like mentioned before, there are three different components for this project, the mobile client, the backend and the management tool. Current avaliable implementations (click the links to visit the corresponding repositories) :

#####Mobile client 
- Android app, [notifications-android](https://github.com/jaccohuysmans/notifications-android)

#####Backend
- Java (using Play & ElasticSearch), [notifications-backend-java](https://github.com/jaccohuysmans/notifications-backend-java)
- Scala (using Play & ElasticSearch), [notifications-backend-scala](https://github.com/jaccohuysmans/notifications-backend-scala)  Not implemented yet
- (Ruby on) Rails, [notifications-backend-rails](https://github.com/jaccohuysmans/notifications-backend-rails)  Not implemented yet

#####Management 
- Web app (using Extjs), [notifications-management](https://github.com/jaccohuysmans/notifications-management)


