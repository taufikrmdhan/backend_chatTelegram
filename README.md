<h1 align="center">Telegram App</h1>

## Description
Telegram is a real-time chat application developed using several technologies including: PostgreSQL, Express.js, Web Sockets, and React.js. In this application, users can register and login to enter the Telegram chat page. First log in, then you will immediately enter the chat menu, where through this chat menu we can choose which user we will chat with. Through this feature, we can chat in real time with other people who both use this application. To do a CRUD profile, we can click the settings icon, then we will immediately go to the profile page. After that select the edit profile button to perform the CRUD profile process.

## Run Project
Install package : npm i

Run Project : npm start

## Project Structure

```
|── Backend
   |── public    # File image from multer
   |── src       # Project source code
       |── config        # config db
       |── controller    # Logic/controller db
       |── helper        # setting env, generateJWT and standard response
       |── middleware    # setting Authentication, jwtAuth, and config multer (delete and upload image)
       |── model         # model / db query
       |── router        # route API
       |── socket        # Config socket to get realtime chat application
   |── .env            # Setting env backend to connecting   
   |── .gitignore      # File name for not uploaded on github
|── .README.md      # For Readme In github
```

## Related Project
Frontend chatTelegram Application.\
[frontend-telegramApp](https://github.com/taufikrmdhan/telegramApp)
[deployement-telegramApp](https://telegram-app-pi.vercel.app/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
