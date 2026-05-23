# KAZU — Money OS
> *You already know you should be tracking your money. You're not. That's why you're here.*

KAZU is a free, local-first budget tracker for Android. No account. No subscription. No ads watching what you spend. Your data stays on your device — period. Log expenses, track bills, set budgets, see exactly where your money goes. Nothing more. Nothing less.

**6 expense categories. 5 income categories. Recurring bills. Smart alerts. Split bill calculator. App lock. PDF export. Zero cloud.**

It started as a personal tool because every other finance app wanted a login, a monthly fee, or access to your bank. KAZU wants none of that. It just works — offline, privately, and for free.

Most people will download it, use it for a week, and quietly admit it's the only finance app that didn't get in their way.

The ones who don't try it will keep paying for apps that sell their data.
That's a choice too.

---

═══════════════════════════════════════════════════════════

---

## What KAZU Actually Does

**Dashboard — the truth, all at once**
Monthly balance, remaining budget, and a health pill — Green, Amber, or Red — so you know in one glance whether you're fine or lying to yourself. Income and expense donut charts by category. Smart insight cards that flag your burn rate, heaviest spend day, projected end-of-month total, and comparison to last month. A savings goal progress bar that doesn't lie.

**Expenses & Income**
Quick-add modal with a custom keypad — amount, category, note, date. Six expense categories: Food, Transport, Bills, Health, Fun, Other. Five income categories: Salary, Freelance, Gift, Refund, Other. Full transaction history with month filter. Tap any category to drill into individual entries.

**Recurring Bills & Subscriptions**
Add a bill once with a due day. KAZU tracks what's paid and what's overdue every month, resets automatically, and shows a *recurring shadow* on the dashboard — the money already committed before you've spent a single discretionary cent. If you log the same expense three months in a row, KAZU notices and quietly offers to make it recurring. Snooze an overdue bill and a reminder fires 2 days out.

**Reminders**
One-time money tasks with custom alarm times. Bill due alerts at 7 days, 3 days, 2 days, 1 day, and day-of. Notifications fire in calm windows — 6am, 7:30–8:15am, 12:30–1:15pm, 9:00–9:45pm. Not at 2am. Not during work hours.

**Budget Notifications**
Silent alert at 80%, 90%, and over budget — triggered on every expense entry. You always know where you stand. You might not like what it tells you. That's the point.

**Split Bill Calculator**
Tap the receipt icon on the dashboard. Enter total, number of people, optional tip. One tap adds your share directly as an expense. No mental math required.

**Month Close**
On the last two days of the month, KAZU asks how the month felt — Good, Okay, or Rough. Add a note. It saves as a private financial diary entry. Most people skip it. The ones who use it start seeing patterns they couldn't see before.

**Data & Export**
Full backup as a `.kazu` file. Import to restore, no duplicates. Monthly PDF export — dark or light theme. Everything lives on your device. Nothing leaves it.

**Appearance & Settings**
Dark mode / Light mode. Accent colors — Gold, Silver, Blue, Pink. Font size S / M / L / XL. Currency selector. Per-category budget caps. Savings goal. App lock — 4-digit PIN or pattern, triggers on open and after 2 minutes idle.

---

## Permissions — What They Are and Why

| Permission | Why |
|---|---|
| POST_NOTIFICATIONS | Budget alerts and bill due reminders |
| WAKE_LOCK | Wakes device to deliver scheduled notifications |
| INTERNET | Loads Google Fonts only — no data is sent anywhere |
| READ_MEDIA_IMAGES | Required by Capacitor on Android 13+ for file operations |
| READ / WRITE EXTERNAL_STORAGE | Export and import `.kazu` backup files (Android 12 and below) |

No network calls to any server. No analytics. No crash reporting. No tracking. Install it with WiFi off — it works completely.

---

## Why Your Antivirus Might Flag This

KAZU is not on the Google Play Store. It is a direct APK install.

Google and most antivirus tools flag sideloaded apps by default — not because they found something wrong, but because they have not seen this app before. Unknown = suspicious. That is how the system works. It does not mean dangerous.

What actually happens when you install KAZU:
- No outbound connections to any server are made
- No data leaves your device
- The only network call is loading a Google Font from Google's own CDN
- You can install it with WiFi off and it runs completely

If you want to verify — install [NetGuard](https://netguard.me/) and watch KAZU's traffic. You will see nothing.

The irony: most apps that sail through Play Store review are the ones quietly harvesting your financial behaviour in ways the automated scan was never designed to catch. KAZU fails the suspicion check because it has no company behind it, no Play Console account, and no history. That is the price of being independent and free.

---

## Honest Notes

Built with hand-written code and AI-assisted engineering (Claude by Anthropic), packaged into an APK using Android Studio and Capacitor. 60+ hours of debugging, testing, and iteration went into getting it stable.

Not a polished commercial product. No support team. No guarantees. Tested on MIUI / Android 13 — other devices should be fine but haven't all been tested individually.

If something breaks — open an issue. If it works — tell someone who needs it.

---

## Stack

- Single `index.html` — all HTML, CSS, and JS in one file
- [Capacitor 6](https://capacitorjs.com/) — Android wrapper
- [Android Studio](https://developer.android.com/studio) — APK build
- No frameworks. No build step for the web layer.

**Build it yourself:**
```bash
npm install
npx cap sync android
```
Open `android/` in Android Studio and build the APK.
Gradle `8.14.5` · AGP `8.3.0` · Min SDK `22` · Target SDK `34`

---

═══════════════════════════════════════════════════════════

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/56e257de-6875-4977-82a1-ed8f47febca5" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/bd09a88b-3b9c-4699-996e-47bf5fb6c174" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/bab8264a-5c4d-4042-9791-7174e7d850a2" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/7c198790-1eae-4b13-8bfe-320055300e9d" width="180"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/2af5e854-e8fe-40b4-bd55-d06150a0ff21" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/c9d59c2d-a482-47c7-bb0e-c5f275813698" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/7afdf008-f26d-4f30-b991-ec935c969fff" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/dd45aa8f-515f-4da7-9da4-49d996fee364" width="180"/></td>
  </tr>
</table>

---

## Get KAZU

You got this far. That means something.

**→ [Download APK](https://github.com/evencholmes/01-KAZU/releases/tag/ApkV1.1)** *(replace with your APK link)*
Direct install. No Play Store. No account. No nonsense.
**[Direct Download apk](https://github.com/evencholmes/01-KAZU/releases/download/ApkV1.1/01.Kazu.apk)**

---

**→ [Support on Patreon](https://www.patreon.com/jibunshidai81)**
KAZU is free and will stay free. If it saved you time, stress, or money — a dollar goes a long way toward keeping independent tools like this alive. A few other free apps live on that page too. Same deal, same spirit.

If money is tight, sharing costs nothing and means just as much.

---

*Built by [@Jibunshidai81](https://x.com/Jibunshidai81) — engineered with Claude by Anthropic*

---

*Do whatever you want with this. Credit appreciated, not required.*
