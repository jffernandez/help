---
layout: article
title: Import your data from Google Chrome
categories: [getting-started]
featured: true
popular: false
tags: [import, chrome, opera, vivaldi]
---

Importing your data from Google Chrome into Bitwarden is easy. 

{% note %}
You can only export passwords from the Chrome desktop application. It is not possible to export from the Chrome mobile app.

The process is exactly the same for Opera and Vivaldi browser users.
{% endnote %}

## Export your Chrome passwords

1. Open Chrome and enter `chrome://settings/passwords` into the address bar and press enter. This will open a page with all your **Saved Passwords** for Chrome.
2. Locate the **Export passwords** option at the top of the **Saved Passwords** list. It is hidden under the options icon (`...`) next to the **Saved Passwords** heading.
3. Click the **Export passwords** option in the options menu. You may be prompted to enter your computer's password for authorization.
4. You'll then be prompted to save your passwords to a [CSV][csv] file on your computer. Save this file to your desktop as `chrome_passwords.csv` (or whatever name you want to call it).

## Import your passwords into Bitwarden

1. Go to the [Bitwarden web vault][bitwarden-vault] and log in.
2. Navigate to **Tools** &rarr; **Import Data**.
3. Select **Chrome (csv)** as the file format and select your `chrome_passwords.csv` file from the desktop that you created in step 7 above.
4. Click the **Import Data** button.

Congratulations! You have just transferred all of your data from Google Chrome into Bitwarden.

[csv]: https://en.wikipedia.org/wiki/Comma-separated_values
[bitwarden-vault]: https://vault.bitwarden.com
