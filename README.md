# Participation Events

This repository contains the configurations for official participation events.

## Event `raw`-links

### Assembly Round 3

Link: https://raw.githubusercontent.com/iotaledger/participation-events/master/events/staking/assembly_03.json<br>
ID: `79958d5ccaaa81cea1dc8b589655d369b16c72f27a44433ba22c5b0a7dc89356`

### Shimmer Ecosystem Funding Proposal

Link: https://raw.githubusercontent.com/iotaledger/participation-events/master/events/vote/shimmer_funding.json<br>
ID: `9e8e1a15c831441797912a86022f5a78fcb70e151e43fe84812d4c7f6eb79a7b`


## How to add a ballot or staking event as a node operator?

First, you need to update your [Hornet](https://github.com/gohornet/hornet) node to the latest release version (>= v1.2.0). <br>
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


## Previous Events

### Assembly Round 2

Link: https://raw.githubusercontent.com/iotaledger/participation-events/master/events/staking/assembly_02.json<br>
ID: `90ab02d8f700fcb3b31ff577416ecb105697a664738bec45b626920337a280e0`

### IOTA Community Governance Vote

Link: https://raw.githubusercontent.com/iotaledger/participation-events/master/events/vote/governance_01.json<br>
ID: `c8529ff64ea191b437cd625af8b02fd0173bc94aae380ea4cc3367a651536cba`

### Assembly Round 1

Link: https://raw.githubusercontent.com/iotaledger/participation-events/master/events/staking/assembly_01.json<br>
ID: `57607d9f8cefc366c3ead71f5b1d76cef1b36a07eb775158c541107951d4aecb`

### Shimmer
Link: https://raw.githubusercontent.com/iotaledger/participation-events/master/events/staking/shimmer.json<br>
ID: `f6dbdad416e0470042d3fe429eb0e91683ba171279bce01be6d1d35a9909a981`