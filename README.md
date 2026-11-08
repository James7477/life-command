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

## V0.4: calendar backup and private spoken history

- In **Setup**, choose your calendar: Google, Outlook, the phone's calendar (a downloadable **.ics** file), or Life Command only.
- You can say or type **“Remind me I have an appointment Friday at 10 AM.”** Life Command saves the appointment in its encrypted vault and shows an **Add to Calendar** action. External calendar saving requires opening or importing an event and confirming it. There is **no silent two-way sync** in this static GitHub Pages version.
- You can ask **“What all did I do last week?”** or **“How many hours did I work last week?”**. The app asks for the separate private-history PIN, summarizes entries or logged shifts, and can read answers aloud if **Read responses aloud** is enabled.
- Spoken or typed commands and the attendant's answers are kept in the encrypted journal while the vault is unlocked. The current local preview retains up to 1,000 recent journal entries and is **not an unlimited permanent transcript or cloud backup**.
- Work-hour answers include clock-in/clock-out sessions **recorded in this app**; they do not automatically import employer timesheets.
- Password/PIN setup remains mandatory before the personal dashboard is available. The example welcome story can be viewed first.

## Important limitations

The introductory day-in-the-life story is an example, not a claim that automatic wake alarms, background notifications, GPS tracking, or spoken good-night routines are available. Reminders currently work while this prototype is open and unlocked. No online account or cloud sync is provided.

Data is stored locally in the browser and encrypted with Web Crypto. Clearing browser site storage or changing browsers can erase access to this vault. Do not use this prototype as your only copy of important records, or as a substitute for calling emergency services.
