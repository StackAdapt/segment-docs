---
title: StackAdapt Destination
id: 
hide-personas-partial: true
hide-boilerplate: true
hide-dossier: false
beta: true
---

{% include content/plan-grid.md name="actions" %}

### Benefits of StackAdapt (Actions)

By setting up StackAdapt as a Segment destination, your Segment events will be forwarded to StackAdapt. This allows you to track conversions and measure return on ad spend using your Segment events - bypassing the need to install the StackAdapt pixel on your website and write code to send events to StackAdapt.

This destination is maintained by StackAdapt. For any issues with the destination, please [submit a ticket to StackAdapt's support team](https://support.stackadapt.com/hc/en-us/requests/new?ticket_form_id=360006572593).

## Getting started

### Getting Your StackAdapt Universal Pixel ID

1. Log in to your StackAdapt account and navigate to the Pixels page.
2. Above the list of pixels, click the "Install StackAdapt Pixel" link.

[!Image showing location of link to install Pixel](images/install-pixel-link.png)

3. In the instructions that appear, copy the universal pixel ID from the code snippet. Below is an example of a code snippet where the universal pixel ID is `sqHQa3Ob1hiF__2EcY3VZg1`.

[!Image showing location of universal pixel ID in code snippet](images/copy-pixel-id.png)

### Setting up the StackAdapt destination in Segment

1. From the Segment web app, click **Catalog**, then click **Destinations**.
2. Search for "StackAdapt" in the search bar, then click on the Destination "StackAdapt".
3. Click **Add Destination**.
4. Select an existing JavaScript Source to connect to TikTok Pixel.
5. Give the Destination a name.
6. On the Settings screen, provide your StackAdapt Universal Pixel ID. This can be found on the Pixels page in StackAdapt as described above.
7. Toggle on the Destination using the **Enable Destination** toggle.
8. Click **Save Change**.

## Conversion Tracking

Advanced Matching helps you optimize your TikTok ads and drive performance by matching customer information with TikTok users. Hashed customer information can be shared with any TikTok event to attribute more conversions, build bigger audiences, and improve campaign optimization.

There are two types of Advanced Matching: manual or automatic.

**Manual Advanced Matching** is the passing of customer information to TikTok from your website. With this option, you have the flexibility to configure what information and for which event you want to pass to TikTok. This will be enabled automatically if PIIs are included in the Pixel events sent from TikTok Pixel Destination.

When email and/or phone number values are sent to TikTok, TikTok will try to match users with the PII you send to TikTok. If you don't send email or phone number values, TikTok will try to match users with IP and user-agent values that are included in the Pixel event payload.

**Automatic Advanced Matching** is when advertisers instruct TikTok to automatically identify form fields on pages where Pixel is installed and to hash and collect email and phone numbers entered on those pages for ad measurement and attribution purposes. Learn more about Automatic Advanced Matching and how to turn it on in [TikTok help center](https://ads.tiktok.com/help/article/advanced-matching-web?lang=en){:target="_blank"}.

To maximize Advanced Matching's performance, TikTok recommends using both Manual and Automatic Advanced Matching at the same time.

## Data and privacy

Visit TikTok's [docs](https://ads.tiktok.com/i18n/official/policy/business-products-terms){:target="_blank"} to learn more about TikTok's privacy and data terms.
