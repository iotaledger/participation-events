# Participation Events

This repository contains the configurations for official participation events.

## How to add a ballot or staking event as a node operator?

First, you need to update your [Hornet](https://github.com/gohornet/hornet) node to the latest release version (>= v1.1.0). <br>
Make sure to enable the Participation plugin by adding `"Participation"` to `"enablePlugins"` in the `config.json` file of your node.

```json
 "node": {
   "alias": "HORNET mainnet node",
   "profile": "auto",
   "disablePlugins": [],
   "enablePlugins": [
     "Spammer",
     "Participation"
   ]
 },
```

## Add event via node dashboard

After starting your node, you can open the node dashboard and navigate to `Settings` -> `Plugins`.<br>
If the Participation plugin has been successfully enabled, you should see a new option called `Participation`.

![](./resources/hornet_1_light.png)

Click on the three dots next to `Participation` to enter the plugin settings.
![](./resources/hornet_2_light.png)

In the top right corner, click `Add Event`.<br>
Now you can paste the `raw`-link to the event configuration file.
![](./resources/hornet_3_light.png)

After clicking `OK`, the new event is shown (if everything was entered correctly).
![](./resources/hornet_4_light.png)

Your node is now ready to track the specific participation event. You can view the current status of the event by clicking on `More details`.
![](./resources/hornet_5_light.png)
