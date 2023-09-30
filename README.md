# awsnap.js 🫰

Navigate a website by clicking your fingers and saying the link to which you want to go.

[Try the demo](https://capjamesg.github.io/awsnap.js/audio.html)

https://github.com/capjamesg/awsnap.js/assets/37276661/c4f50da0-a2ad-4532-85e8-6f6304912952

## How to Set Up 🛠️

First, clone the project repository:

```
git clone https://github.com/capjamesg/awsnap.js
cd awsnap.js/
```

To run the project, you will need to run a web server that serves the files in the `awsnap.js` folder. You can do this in Python with the following command:

```
python -m http.server
```

Then, open up the project. By default, the command above will serve a web page at `http://localhost:8000`. The URL at which your page is served will depend on what tool you use to set up the server.

_Note: The http.server method is recommended for local testing only. It is not built for production use. In production, you can serve the project files in any way you want; the files are static and don't require additional treatment beyond being on a web server._

## How to Use 💻

When you open the project page, there are two commands you can use:

1. Click your fingers then say a word or phrase featured in a link to open the link in an `iframe`.
2. Clap your hands and an emoji will appear above the default list of links.

## License

This project is licensed under an [MIT license](LICENSE).
