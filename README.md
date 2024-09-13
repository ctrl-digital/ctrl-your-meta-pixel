# ctrl-your-meta-pixel
This repository contains a script developed by Ctrl Digital that checks how the Meta (Facebook) Pixel is implemented on a website. The script specifically verifies if the Advanced Matching and Automatic Events features are enabled, which could inadvertently lead to the sharing of Personally Identifiable Information (PII).

# How It Works
The Meta Pixel can be used to track user behavior on websites for marketing purposes. While these tracking features can be useful, they also pose potential privacy risks if misconfigured, particularly with the sharing of PII. The two features our script checks are:

Advanced Matching: This feature allows websites to share user information such as email addresses or phone numbers with Meta for enhanced targeting.
Automatic Events: This feature enables the Meta Pixel to automatically track specific actions on a website, potentially sharing unintended data with Meta.
If these features are activated, there's a risk that PII could be shared without your awareness or consent.

# How to Use the Script
To check if your site is using these features, follow the steps below:

- Download the script from this repository
- Open your website in a web browser.
- Open the browser’s Developer Console.
- On most browsers, you can do this by right-clicking the page and selecting Inspect or by pressing Ctrl + Shift + I (Windows/Linux) or Cmd + Option + I (Mac).
- In the Console tab, paste the script you downloaded from the repository.
- Hit Enter.
The script will run and check whether Advanced Matching and Automatic Events are enabled on the site. If either of these features is found to be active, you may want to review your Meta Pixel configuration to ensure compliance with privacy regulations and avoid unintentionally sharing PII.

# Disclaimer
This tool is intended to help website owners or administrators assess potential privacy risks associated with their Meta Pixel implementation. It is not a substitute for a comprehensive privacy audit or legal advice. Please ensure that you comply with local privacy regulations and Meta’s terms of service.

For more information or support, please contact Ctrl Digital.
