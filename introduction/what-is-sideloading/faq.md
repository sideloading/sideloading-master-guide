# FAQ

## Can I sideload \<xyz>.IPA

If it is an IPA, then you most likely **can** sideload it. \[guide]

## Can I sideload \<xyz> tweak

**Maybe**, it depends if the tweak requires root, and it depends if it needs `PreferenceLoader`. If the answer to those questions are yes, you are **unlikely** to be able to successfully sideload that tweak.

## Can I sideload on Windows?

Yes. See the page links below.

## Do I need to buy a developer account?

If you want to sideload without revocations and as many apps as you want without computer, yes. Account costs around $99, but, instead of paid code signing services (which starts around $20 **per device**), can be used on **all your devices (current and future)** and devices of your friends or family. So, if you have more than 3 devices or friends, purchasing developer account from Apple suits you best.

You still can use a free one, however, apps will be limited to 7 days, at which point you will have to resign. You can also have only up to 3 apps.

See the following:

{% content-ref url="../../providers/code-signing-services.md" %}
[code-signing-services.md](../../providers/code-signing-services.md)
{% endcontent-ref %}

{% content-ref url="../../providers/code-signing-services-free.md" %}
[code-signing-services-free.md](../../providers/code-signing-services-free.md)
{% endcontent-ref %}

## How to buy an Apple Developer account?

Apple has simplified process of account purchasing. Now it looks like purchasing Apple Music subscription.

- Download [Apple Developer App](https://apps.apple.com/us/app/apple-developer/id640199958)
- Login with your Apple ID
- Tap "Enroll now" and purchase Apple Membership as Individual
- Wait for activation emails

Then you can use your account with [code-signing-services.md](../../providers/code-signing-services.md)


## I get a \<App ID limit> in Xcode:

This means you have created too many provisioning profiles in 7 days using a free account. You will be able to sideload again after that time elapses.

## My apps crash on startup! Help!

This is either (1) the provisioning profile expired, or (2) the app is incompatible, or (3) the tweak has not been applied correctly.
