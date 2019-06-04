# Retargeting & Tracking Pixels

You can use third-party retargeting pixels with Linkly.

For example, you may wish to track users who have clicked on a link, and then serve them retargeted ads via Google Display Network, Facebook Ads or any other ad system that supports retargeting.

## What is Retargeting?

Have you ever noticed how when you visit a product page on the internet, somehow ads seem to show up for the product for weeks afterwards, on other unrelated sites? 

This is because of retargeting. 

When you visited the original product page, you were recorded as showing interest in that product. The owner of that site can now buy ads across the internet, and target you specifically, reminding you this product exists.

Retargeting is extremely effective, and is generally an order of magnitude cheaper per conversion than conventional ad targeting.

## Using retargeting pixels with Linkly

In order to use retargeting pixels, you'll need to obtain retargeting code from the ad network you are using.
* Instructions for [Google Ads](https://support.google.com/google-.ads/answer/3210317?co=ADWORDS.IsAWNCustomer=false&hl=en).
* Instructions for [Facebook]([https://www.facebook.com/business/help/952192354843755#](https://www.facebook.com/business/help/952192354843755#)).
* Linkly supports all other standard pixels as well.

With your code ready:
1. Click **Create New Link** from the menu.
2. Set up the **Nickname**, **Destination** and any other link settings you would like to use.
3. Click **Retargeting & tracking pixels**.
4. Paste your code in the box here. Make sure you include any `<script>` tags.
5. Click **Save Link**.

Now, when a user clicks on a link, they should be automatically tagged by the ad network, and added to your retargeting list.

## Things to Note
* The process of adding users to retargeting lists is invisible.
* Users will be served the pixel before being redirected. This process is instant.
