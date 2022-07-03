#Github pages only support static files (HTML, CSS and Javascript). In order to use Node.js packages the project first needs to be compiled using Harp.  

Required modules:
 - Node.js
 - Typescript
 - Harp

Host using harp (for testing):
 - Run `harp ./public`

Build using harp:
 - Clone the project containing the github page (e.g. aed3r.github.io)
 - Run `harp ./public ./aed3r.github.io`