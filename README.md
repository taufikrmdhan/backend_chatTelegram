<h1 align="center">Telegram App</h1>

## Description
Telegram adalah sebuah aplikasi chat realtime yang dikembangkan menggunakan beberapa teknologi diantaranya : PostgreSQL, Express.js, Web Socket, dan React.js. Pada aplikasi ini, user bisa register dan login untuk masuk ke halaman chat telegram. Pertama login , nanti akan langsung masuk ke menu chat, yang dimana melalui menu chat ini kita bisa memilih user mana yang akan kita chat. Melalui fitur ini, kita bisa chat secara realtime dengan orang lain yang sama-sama menggunakana app ini. Untuk melakukan CRUD profile, kita bisa klik icon setting, lalu nanti akan langsung masuk ke halaman profile. Setelah itu pilih button edit profile untuk melakukan proses CRUD profile.

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
[frontend-telegramApp](https://github.com/taufikrmdhan/backend_chatTelegram)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.