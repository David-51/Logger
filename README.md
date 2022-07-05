# Logger
An easy class to write log message.

## before start

Create the folder .log and verify that your server has the permission to write files.

## how it works

This class create a log file in the folder ./log 
Just use a static class as : 

```Logger::setMessage('Your message here')```

This class create a log for every single days.

The file format is "Ymd-logger.log" for example : 20221225-logger.log

Each lines start with the current date and hour and the Ip adress.

For example if the message is "My example message" :
2022-12-25 12:25:00 - 127.0.0.1 My example message.

This format is easy to read and useful to debug.

Feel free to send me any suggestions.