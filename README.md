## Insular

Small chat project that intentionally forgets to escape HTML. Can be used to show off your quick Javascript hijacking skills to your friends.

**Not meant for production.**

Insular was made as a personal project to implement a very basic chat example using [socket.io](https://socket.io/). After showing a friend the project (and realizing the server did not escape HTML), we quickly traded messages laced with Javascript and CSS to see whose devilish ideas were better and who could crash the other person's browser sooner. Suffice to say, the page did not end so well that afternoon, but it was a fun way to pass the time.

Now you can have the same enjoyment! Here's how to deploy it:

### Deployment

Clone: `git clone https://github.com/encadyma/insular.git && cd insular`

- **local server**: `npm install && npm run start`
- **now by ZEIT (https://zeit.co/now)**: `now`

### License
Insular is better suited towards the public domain, so Insular is licensed under The Unlicense. [Click here to read more.](https://github.com/encadyma/insular/blob/master/LICENSE)

Insular is made possible by [Bootstrap](https://getbootstrap.com/), [Express](https://expressjs.com/), and [Socket.io](https://socket.io/). Font is [Alegreya Sans](https://fonts.google.com/specimen/Alegreya+Sans).