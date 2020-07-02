# Chat-App

This is an android chat application that allow multiple users to join a room and chat. The application includes NodeJS server and uses SochetIO to send and receive data in real time with the server. 


## App Demo

<br> <p align="center"><img src="https://i.imgur.com/YBH4HYb.gif" height="500" alt="alt text" title="demo"></p>


## Usage

To run the app you can either deploy the NodeJS server to a cloud platform such as [Heroko](https://devcenter.heroku.com/articles/nodejs-support) or simply run it locally. 

If you prefer to run the server locally make sure of the following:
* Both PC and phones are connected with the same router.
* Modify `localhost` in `Constants.java` file with IP address assigned by the router.
```
public static final String CHAT_SERVER_URL = "localhost:3000/"
```


## License

MIT
