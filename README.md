# WhatsApp Chat - Client

![WhatsApp-Clone](README/WhatsApp-Clone.gif)

### Run instructions

- Make sure to clone the server first
  ```
    git clone https://github.com/vbosstech/WhatsApp-Chat-Client-React.git
  ```

- Run yarn
  ```
    yarn install
  ```

- Run codegen to generate TypeScript types
  ```  
    yarn generate
  ```

Note that the types are generated from the server! So if you clone the server project in a different path be sure to update the `codegen.yml` file.

Start the server, see run [instructions](https://github.com/vbosstech/WhatsApp-Chat-Server).

Run start

    $ yarn start

Note that the server should run on port `4000`. If you decide to change that, be sure to edit the `.env` file
