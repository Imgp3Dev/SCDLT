![screenshot_2018-09-15-01-04-05 2](https://user-images.githubusercontent.com/42507604/45583236-c9c29800-b883-11e8-9853-07058b34d429.png)

# SCDLT
SCDLT(Server Connector Data Logger Tool) Is used for Logging server Data. It works By Sending custom requests as an Application.

# Example Description:
Let's say A person sniffed a traffic from an Application, etc As we all know An application, Program and whatever else that requires a Server will always end up communicating to the server. And the hence is that The Server will always expect a response from that particular Application, etc So If you wanted to Log the Server internally that's what SCDLT will be Used for, Pretty much Sending a request as the Application tricking the Server into thinking it came from the particular Application, etc And then eventually you will end up Logging the server traffic.

# Diagram:

Server -> Network traffic -> Sends Data -> SCDLT Intercepts -> SCDLT Acts as a Response from the application -> Gets sent to the server -> Logs the server internally.

# How will it work:

Once It Intercepts the Traffic(For both Server & Application) It will Record How the responses are organized, Specific keywords, etc And will use it as a way of processing it's own Logger Via response.

Features:
Traffic Logging, 
Intercepting

# Commands: 

Log `<filename>` (Logs a particular File Data)


Send `<Text> <Filename>` (Send Text to a particular File in the Server)

# Note:

If you're wondering how You will Log the Server, SCDLT has a built-in logger which all the Traffic that gets logged within the Server will be sent to a generated File that SCDLT will create.
