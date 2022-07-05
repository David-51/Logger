# Logger
Une simple class qui permet de logger des événements

## how its work

This class create a log file in the folder ./log 
Just use a statis calss as ```Logger::setMessage('Your message here')```

This class create a log for every single day

The file format is "Ymd-logger.log" for example : 20221225-logger.log

Each lines start with the current date and hour and the Ip adress.
for example if the message is "My example message" :
2022-12-25 12:25:00 - 127.0.0.1 My example message.

This format is easy to read and useful to debug.
