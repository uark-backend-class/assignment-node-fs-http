# Node modules, fs, http

1. Clone down this repository.
1. `cd` into the repository directory.
1. Create a new javascript file called `file-io.js`.
    - In this file:
      - Create a module that has:
        - a function that creates files and returns the contents of the file
        - a function that reads a file and returns the content of the file
        - a function that appends to a file and returns the contents of the file
        - a function that deletes a file and returns a successful message when completed
1. Create another file called `index.js` that imports this new module.
1. Within `index.js`, create an Http server that when opened from the browser url `http://localhost:3000/`:
    - Creates a file, appends a message of your choice to it, then returns the read result of this file when an Http request is made to the server.
    - Remember: Start your server with `node index.js`. Open `http://localhost:3000` in your browser to test your http server.
    - Feel free to experiment with the contents of the file that you create. You can try putting some HTML in the file to see what happens.
    - See [this lecture material](https://github.com/uark-backend-class/course-materials/blob/master/lectures/06-intro-to-node/lecture01-notes.md#using-modules-and-packages) if you need to review how to create an http server in node.
1. Stage, commit, and push your solution.