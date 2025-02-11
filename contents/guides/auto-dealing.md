# 🪄 Auto dealing

To make creating deals even more easy, FEATURE allows organizations to manage special wallets that can be used to automatically sign the blockchain transaction that is required to create a new deal.

Using auto dealing, you will simply have to label an issue with a [Feature label](../create-a-deal-using-labels.md) and the deal will be created automatically without further action.

{% hint style="warning" %}
Auto dealing only works with issue labelling as of now. Learn how to use Feature labels [here](../create-a-deal-using-labels.md)
{% endhint %}

1\) Enable auto dealing in your [organization settings](https://dashboard.feature.sh/settings/installations) as shown below:

![](../.gitbook/assets/enable\_auto\_dealing.png)

2\) Manage your organization wallets and set the one you want to use for auto dealing by selecting it as the default.

![](../.gitbook/assets/select\_organization\_wallet.png)

3\) Label an issue with a Feature label and let the magic happen 🪄.The transaction can take up to a few minutes to be processed, but fortunately the Bot will keep you updated about the progress!

![](../.gitbook/assets/auto\_deal\_success.png)

{% hint style="warning" %}
The selected wallet should have the necessary funds to create the deal, otherwise an error message will be thrown by the bot.
{% endhint %}

![](../.gitbook/assets/auto\_deal\_failure.png)
