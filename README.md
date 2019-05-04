# Indoor Admin
This is the core administrator of indoor location solution here is the architecture.

![Architecture](./images/architecture.PNG)

This is an initial proposal for an indoor location site survey open source tool and algorithm developing environment. A live demo of the React Client can be found in [indoor-manager.pelagaggi.com](https://indoor-manager.pelagaggi.com).

Firsts steps

* create these 2 files:


    * adminAuth.js
    ```JavaScript
    module.exports = {
            type: "credentials",
            users: [{
                username: "myusername@blablabla.com",
                password: "node-red-admin hash-pw",
                permissions: "*"
            },...]
        };
    ``` 
    If you are not familiar or just do not remember how to create a credential for AdminAuth you can find in [node-red-admin](https://nodered.org/docs/node-red-admin) page. (take a look at hash-pw)

    mongodbURI.js
    ```JavaScript
    module.exports = "mongodb+srv://myUser:myPassword@myDatabaseURL?retryWrites=true"
    ```


If you have any questions on this matter or indoor location, in general, you can find my contacts on my personal page pelagaggi.com or send me an e-mail at [alexandre@pelagaggi.com](mailto://alexandre@pelagaggi.com).