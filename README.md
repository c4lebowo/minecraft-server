# minecraft-server
An approach to host my own Bedrock Minecraft Server and share it with my friends :)
## Installation instructions
- Download the [latest server software either for Linux or Windows](https://learn.microsoft.com/en-us/minecraft/creator/documents/bedrockserver/getting-started?view=minecraft-bedrock-stable)
- Create a directory in your personal computer and unzip the downloaded file to the directory to work on
- In my case I used an Ubuntu container, so I used this commands inside the directory where the main file was located to start it
  ```Bash
  sudo chmod+x ./bedrock_server
    sudo ./bedrock_server
  ```
  Once it starts, you should see something like this:
  ![Minecraft Bedrock Server Starting](attachments/startss.png)

  If you wanna turn it off just type stop
- And that's it!

## Other settings
I installed [playit](playit.gg) on the machine so it can be accessible everywhere, the documentation is [here](https://playit.gg/support/run-on-linux/).

I will add some automation commands in the future so it can be updating itself.
