### What's this?
      
An app which alerts you when your system is down.


### Features

- mobile notifications via [urban airship](http://urbanairship.com)     
- email notifications via [mail gun](http://mailgun.net)
- endpoint for [Alert Birds](https://alertbirds.appspot.com/)      
- modular via [beanpole](https://github.com/spiceapps/beanpole)                 

### To-Do

- Twilio   
- scan directory for configs                                                   
                          

### Installation             


TODO


### Configuration

In your sysalert.cont file


````ini     

# endpoint for notifications
[endpoint:X]
email=me@email.com another@email.com
iphone=999-999-9999

[keys:sysalert.notify.part.urbanairship]
key=XXXXXXXXXX
secret=XXXXXXXXXX
masterSecret=XXXXXXXXXX  

[keys:sysalert.notify.part.mailgun]
key=XXXXXXXXXX           

[include]
directories=/etc/syslog/*.conf
   
                        

````



       
                        



