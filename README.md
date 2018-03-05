# multitech-conduit-loramode-sample
A scriptr.io sample app that visualizes the LoRa Mote feed as sent to a MultiTech Conduit.

## Usage
After installing the app, follow the below steps to get it working:
1. Go to Settings > Channels
2. Click Add Channel to create a new channel, and call it "responseChannel"
3. Once created, click the Manage scripts button next to it
4. Select the script called "ConduitMoteDemo/buffer" and click Subscribe
5. Similarly, if you don't already have a channel called "multitech", create it and subscribed the script "ConduitMoteDemo/Transform" to it
6. Now open to the script "ConduitMoteDemo/Dashboard" and click the View button to open it in your browser and start seeing the sensor's readings on the dashboard
