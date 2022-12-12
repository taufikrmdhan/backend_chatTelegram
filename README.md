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

## Build With

<ul id="Build" dir="auto">
  <li><a href="https://www.postgresql.org/" rel="nofollow">postgre SQL (for Database Management System)</a></li>
  <li><a href="https://www.postman.com/" rel="nofollow">Postman for API documentation management</a></li>
  <li><a href="https://www.npmjs.com/" rel="nofollow">NPM for dependency management</a></li>
  <li><a href="https://github.com/motdotla/dotenv">dotenv: for using environment variabels</a></li>
  <li><a href="https://helmetjs.github.io/" rel="nofollow">helmet: for set security HTTP headers</a></li>
  <li><a href="https://www.npmjs.com/package/xss" rel="nofollow">XSS: to sanitize untrusted HTML (to prevent XSS)</a></li>
  <li><a href="https://github.com/expressjs/cors">CORS: Cross-Origin Resourece-Sharing enabled using</a></li>
  <li><a href="https://github.com/kelektiv/node.bcrypt.js">bcrypt: for hashing password</a></li>
  <li><a href="https://eslint.org/" rel="nofollow">ESLINT: for linting and prettier code formatter</a></li>
  <li><a href="https://expressjs.com/" rel="nofollow">ExpressJS: for CRUD management</a></li>
  <li><a href="https://jwt.io/" rel="nofollow">JWT: for generate JSON WEB TOKEN</a></li>
  <li><a href="https://socket.io/" rel="nofollow">Socket.io: Bidirectional and low-latency communication for every platform.</a></li>
  <li><a href="https://nodejs.org/en/" rel="nofollow">NodeJS</a></li>
  <li><a href="https://github.com/taufikrmdhan/backend_chatTelegram/blob/main/package.json">and you can see the dependencies used in the package.json</a></li>
</ul>

## Related Project
Frontend chatTelegram Application.\
[frontend-telegramApp](https://github.com/taufikrmdhan/telegramApp)
<br/>
[deployement-telegramApp](https://telegram-app-pi.vercel.app/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
