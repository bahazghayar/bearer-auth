# bearer-auth

## Links:

[Heroku link](https://bz-bearer-auth.herokuapp.com/) <br>

#### MongoDB URI

MONGODB_URI=mongodb+srv://bahazghayar:0000@cluster0.gylwg.mongodb.net/bearer-auth?retryWrites=true&w=majority <br>

[GitHub action link](https://github.com/bahazghayar/bearer-auth/actions) <br>

[Pull request link](https://github.com/bahazghayar/bearer-auth/pull/1) <br>

### For working on the same project:

1. clone the repo
2. install the dependencies `npm i express dotenv cors mongoose morgan jest base-64 bcrypt jsonwebtoken`
3. change the package.json file to
                        "scripts": {
                        "start": "node index.js",
                        "watch": "nodemon",
                        "test-watch": "jest --watchAll",
                        "test": "jest",
                        "lint": "eslint '\*_/_.js'"
                        }

# UML

![bearer-auth](assets/bearer-auth.png)