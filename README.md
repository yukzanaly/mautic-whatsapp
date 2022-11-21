# Mautic Whatsapp Plugin
This plugin replaces the SMS channel and allows you to send messages to Whatsapp
using the Wo-Wa Whatsapp Web application.
Intended for >= Mautic 4.0

Read more:
https://joeykeller.com/weekend-project-a-mautic-whatsapp-plugin

## Installation by console
1. Download the plugin, unzip in your plugins folder
2. Rename the folder to MauticWhatsappBundle
3. `nano plugins/MauticWhatsappBundle/Transport/WhatsappTransport.php
4. paste your starsender apikey in  $apikey="Your apikey" (line 120)
5. Clear cache
6. `php bin/console mautic:plugins:reload`

## Usage
1. Go to your **Plugins** in Mautic
2. You should see new Whatsapp plugin in the list, click and publish it.
3. Go to https://joeykeller.com/weekend-project-a-mautic-whatsapp-plugin, and see how you can get your credentials.
4. This plugin overrides your SMS transport. In your **Configuration > Text message settings** select Whatsapp as default transport

Check my blog for updates and Mautic guides:
Joeykeller.com

## Send with starsender wa api
1. Go to your plugin and input the starsender apikey
