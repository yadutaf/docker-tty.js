Simple [tty.js](https://github.com/chjj/tty.js) Docker image that 
"just works". Sticks as much as possible to Docker's best practices.

Usage
-----

To run this image, pull the repository and run the image:

```bash
docker pull yadutaf/tty.js
docker run -t --rm -p 8080:8080 ttyjs
```

Alternatively, you may rebuild the image from sources:

```bash
git clone https://github.com/yadutaf/docker-tty.js.git
cd docker-tty.js
docker build -t ttyjs .
docker run -t --rm -p 8080:8080 yadutaf/ttyjs
```

Then visit http://localhost:8080/ and enjoy !

License
-------

MIT


