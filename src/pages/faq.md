import { Callout } from 'nextra-theme-blinkshell'

# Frequently Asked Questions

## General Questions

### How to apply for a student license?
Starting on 2022, Blink will offer Student licenses during the Back To School period, from September 1st until November 1st. The rest of the year, you are welcome to join us in our [Community Edition.](https://community.blink.sh)

### Does Blink Shell work on all Apple devices?
We support iPhone and iPad. We are working on a new M-powered macOS version.

### Does Blink have a TestFlight version?
Yes, it has! We call it Community Edition, and you can sign up here: [https://community.blink.sh](https://community.blink.sh)

### How to file a bug report?
Fill an issue on our [GitHub](https://github.com/blinksh/blink/issues)

## Pricing

### What plans are available to buy Blink Shell?
Please see our [current plans.](https://blink.sh/#choose-package)

### Is Blink available for a one-time purchase?
No, Blink is no longer offered as a one-time purchase. Instead, we now provide Blink+ under an annual plan. This decision allows us to continuously support new operating system versions and add new functionalities. The annual plan helps avoid monthly charges and ensures a fair arrangement for both parties. It assists us in funding our costly development efforts, while you get access to the Pro app, which has been evolving for 7 years and continues to improve.

### I prefer owning my software and I'm not a fan of subscriptions.
We understand. One common concern we've heard is the fear of losing access to the app if something were to happen. But we want to remark that Blink is Open Source since its inception. This means you have the option to take control by building the app yourself. Owning the source code ensures that you'll always have access to the software, even if circumstances change. 

### I'm a user of the previous Blink, do I need to purchase the new one to continue using it?
No, you do not need to purchase the new version of Blink. You can continue using your purchased app after dismissing the initial prompt. The app you purchased should continue working seamlessly with the operating system and version you acquired it for.

To cater to our loyal customers, [we offered a special path called "Blink Classic"](/migration) that allowed users to transition into the new app. This grandfathering option was available for one and a half years, *ending on April 2023*.
Blink Classic users have access to the familiar functionality they were used to, but we cannot guarantee access to new features introduced in the updated version. If you prefer to explore the new features, you may consider upgrading to one of our packages.

### Should I wait for Black Friday deals or discounts?
We do not offer discounts. The best time to purchase is always right now. We think Blink is competitively priced, and this way you can enjoy its benefits immediately without having to wait for seasonal promotions.

### Is there a Freemium version of Blink?
We now offer a Free Trial of our complete solution with Blink+Build, providing you with a chance to explore all of Blink's features and benefits before making a decision. Our previous Freemium was phased out in 2023 as the metered paywall was perceived as a bad experience.
Blink is a professional-grade application. With the trial, we can focus on providing the best experience and support for those who are committed to making the most out of it.

### Is there a no-cost version of Blink available?
We provide a [Community version](https://community.blink.sh) for those who wish to contribute to the project in a different manner. However, it's important to know that this version has limited seats and comes with certain expectations. To participate, we kindly ask individuals to dedicate time to testing, provide feedback, and to actively engage in our Community.

## Known Issues

### Cmd key stuck while switching between apps with Cmd Tab

After switching apps with the `Cmd-Tab` shortcut, when you return to the same app, the `Cmd` key is still pressed and the shortcuts help window shown. You can then press `w`, `t`, etc without having the `Cmd` key pressed.

<Callout>
This is a known issue within iOS 13, and to get Apple to solve it we need your help. Please create a bug report within [Feedback Assistant](https://feedbackassistant.apple.com). We suggest that you use a similar title to ours: "Cmd key stuck while switching between apps with Cmd-Tab".
</Callout>

Here are two recordings that show the issue: `Cmd-tab` in [Pages.app](https://youtu.be/x0foV_ONDmk) & `Cmd-tab` in [Safari](https://youtu.be/-7LayQvtmPQ).

### Spacebar suddenly didn’t work?

Go to iOS Settings -> Accessibility -> Full Keyboard Access -> Commands -> Activate and change `Space` to `shift + space` or other shortcut.

That way you will have full keyboard access and spacebar working in Blink
