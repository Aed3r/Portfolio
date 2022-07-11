Github Pages only support static files (HTML, CSS and Javascript). In order to take advantage of Node.js packages, the project first needs to be compiled using Harp.  

---

All required modules can be installed using `npm install`

Host using harp (for testing):
 - Run `harp ./public`

Build using harp:
 - Clone the project containing the github page (`aed3r.github.io` in this case)
 - Run `harp ./public ./aed3r.github.io`
 - Commit and push the changes made inside the github pages project