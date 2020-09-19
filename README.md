11 - note taking app 

2 packages: 


1. set up express server server.js / ./server.js 
   * justin is going to use port 3000, react is usually this so gonna have conflict in regular app
   * process.env.PORT is just for deploying 
      * develop gives us a button but the redirect is broken, we can fix this with 
      * `router.get("/notes", (req, res) => {res.sendFile(path.join(__dirname, "../public/notes.html"));});`

1.5. api routes 
	* .get("route", (req, res) => {} )
	* .post("route", (req, res) => {} )
	* .delete(("route", (req, res) => {} )


2. make the store - /db/store.js 
   * this is kind of like redux? have a `store` that contains `actions` to the db.
   * we're going to create `read, add, and remove functions for now` -- i guess extra work would be us adding an edit function 
  
