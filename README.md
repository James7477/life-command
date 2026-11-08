# Life Command — Guardian Edition

Life Command is a mobile-friendly personal attendant prototype built by James Meadows.

## Start here

Open `index.html` using a secure HTTPS website, such as GitHub Pages. The app stores its encrypted vault in this browser's local storage.

### First visit

1. A one-time "A Day With Life Command" example explains the intended experience, from the morning routine to the good-night message.
2. Select **Setup & Privacy** (or **Let's Get Started**) to continue.
3. Choose a **Life Command password** (12 characters or longer), a separate **6-digit private-history PIN**, and when the app locks after leaving the browser.
4. After unlocking, go to **Setup** to set your preferred name, work schedule, reminder lead time, and other settings.

On future visits in the same browser, the introduction is skipped. For privacy, you must still unlock the encrypted vault before the main dashboard opens. The introduction can be replayed from Setup.

The Life Command password and PIN **can be different from your phone unlock code**. This static web version does **not** support native Face ID or fingerprint sign-in. Choose unique credentials and remember them: the prototype does not offer cloud password recovery.

## Hosting with GitHub Pages

The repository includes `index.html`. To publish at `https://james7477.github.io/life-command/`, in GitHub go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, then select **main** and **/(root)**, and save.

## Important limitations

The introductory day-in-the-life story is an example, not a claim that automatic wake alarms, background notifications, GPS tracking, or spoken good-night routines are available. Reminders currently work while this prototype is open and unlocked. No online account or cloud sync is provided.

Data is stored locally in the browser and encrypted with Web Crypto. Clearing browser site storage or changing browsers can erase access to this vault. Do not use this prototype as your only copy of important records, or as a substitute for calling emergency services.
