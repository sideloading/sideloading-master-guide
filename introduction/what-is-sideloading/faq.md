# FAQ

## Can I sideload \<xyz>.IPA

If it is an IPA, then you most likely **can** sideload it. \[guide]

## Can I sideload \<xyz> tweak

**Maybe**, it depends if the tweak requires root, and it depends if it needs `PreferenceLoader`. If the answer to those questions are yes, you are **unlikely** to be able to successfully sideload that tweak.

## Can I sideload on Windows?

Yes. See the page links below.

## Do I need to buy a developer account?

If you want to sideload without revocations and limitations, yes. Developer accounts costs $99, but instead third-party code signing services (which starts around $20 **per device**), it can be used on **all your devices (current and future)**, as well as devices of your friends or family. If you have more than 3 devices or friends, purchasing a developer account from Apple suits you best.

You can still use a free developer account, however limitation apply such as; resigning apps every 7 days & a maximum of 3 signed apps.

See the following:

{% content-ref url="../../providers/code-signing-services.md" %}
[code-signing-services.md](../../providers/code-signing-services.md)
{% endcontent-ref %}

{% content-ref url="../../providers/code-signing-services-free.md" %}
[code-signing-services-free.md](../../providers/code-signing-services-free.md)
{% endcontent-ref %}

## How to buy an Apple Developer account?

Apple has simplified process of account purchasing: Now it looks like purchasing Apple Music subscription.

- Download [Apple Developer App](https://apps.apple.com/us/app/apple-developer/id640199958)
- Login with your Apple ID
- Tap "Enroll now" and purchase Apple Membership as Individual
- Wait for activation emails

Then you can use your account with [code-signing-services.md](../../providers/code-signing-services.md)


## I get a \<App ID limit> in Xcode:

This means you have created too many provisioning profiles in 7 days using a free account. You will be able to sideload again after that time elapses.

## My apps crash on startup! Help!

This is either (1) the provisioning profile expired, or (2) the app is incompatible, or (3) the tweak has not been applied correctly.
