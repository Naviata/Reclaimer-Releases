# Reclaimer DayZ Tools – Privacy Policy

*Last updated: 28 October 2026*

**In short:** Reclaimer has no ads, no analytics and no tracking. It sends personal data only to sign
you in, to check your licence, to count your free hour, and to keep your account on one PC. Your
terrains, models and other files stay on your computer.

This policy covers the Reclaimer DayZ Tools desktop app ("Reclaimer") and the online service it signs
in to. Reclaimer is made by **Reclaimer Tools** ("we"), who decides how this data is used. You
can reach us at the address in section 13.

---

## 1. Data used to sign you in

You sign in in one of two ways.

**With Patreon.** Reclaimer opens Patreon's own sign-in page in your browser. You sign in there and
allow Reclaimer. Your Patreon password is never seen by Reclaimer or by us. Patreon then gives us:

- your Patreon user ID, your Patreon name and your email address, and whether Patreon has verified
  that email
- your membership of Reclaimer's Patreon page: whether you are an active patron, whether you pay
  monthly or yearly, the amount and tier you are entitled to, and the date of your next payment

Patreon also lists any memberships you have elsewhere. We keep only your membership of Reclaimer's
page.

When your membership changes (you join, pay, change tier or leave), Patreon tells our server directly,
so your access stays up to date.

**With a developer account.** You sign in with an email address and a password. The password is
stored by our hosting provider (see section 7) only in scrambled (hashed) form; we cannot read it. When
you create a developer account, our hosting provider emails you a link to confirm your address.

**Checking your licence.** While you are signed in, Reclaimer asks our server for your licence. It
does this:

- when it starts
- when you open the account button, if the last check is more than 12 hours old
- when you press **Check again**
- during the free hour, once a minute while the Reclaimer window is in front

Each check sends your sign-in token and the PC details described in section 2. A licence lets
Reclaimer run for 7 days without the internet.

## 2. One PC per account, and the free hour

An account can be used on one PC at a time. To do this, Reclaimer sends:

- **a PC code:** a one-way scrambled code (a SHA-256 hash) made from Windows' own ID for your PC. The
  Windows ID itself never leaves your computer, and the code cannot be turned back into it.
- **your PC's name** (for example *DESKTOP-4F2K1*), so you can see which PC holds your account

We keep which PC holds your account, when it was first used and when it was last seen. **Use on
another PC** in Reclaimer frees it.

An account with no paid role gets **one hour** of Reclaimer to try it. To count that hour, we keep the
minutes you have used, against your account and against the PC code. Making a new account on the same
PC therefore does not give a new hour.

## 3. Technical data

Our hosting provider (section 7) records the IP address and technical details of requests in its own
logs, as web services do. Its sign-in service also keeps the IP address and the app or browser details
of each sign-in with that sign-in, as part of how sign-ins work. We use these only to run and secure the
service. Reclaimer's own records (sections 1 and 2) hold no IP addresses.

Reclaimer also reads public information from GitHub: news of new releases, whether an update is
available, the list of bug reports, and the QGIS add-on's download. GitHub can see your IP address
when it answers these requests.

## 4. Data that stays on your computer

Reclaimer keeps these in your Windows user folder (`%LOCALAPPDATA%\ReclaimerDayZ`), and none of it is
sent anywhere by Reclaimer:

- **your settings**
- **copies of what it downloaded:** release news, the bug report list, and pictures and previews of
  models and terrain
- **your sign-in, if you tick "Remember me on this PC":** encrypted with Windows' own data protection,
  so only your Windows user on this PC can read it. **Sign out** deletes it.
- **your terrains, projects, models and other files**, where you save them

## 5. What is not collected

Reclaimer does not collect:

- the contents of your files, terrains or projects
- how you use Reclaimer, what you click, or how long you spend in each tool
- crash reports
- your contacts
- your payment details. Patreon takes payments; we only learn your membership status as described in
  section 1.

## 6. Why the data is used

We use the data above only to:

- **sign you in and give you what your membership or role includes.** This is the service you asked
  for (a contract).
- **keep each account to one PC, and the free hour to one hour.** This prevents accounts being shared
  and the free hour being repeated, which is our legitimate interest in being paid for Reclaimer.
- **meet legal obligations**, if any apply.

**Automatic decisions.** Reclaimer automatically locks when your free hour is used up, or when your
account is in use on another PC. If you think this is wrong (for example, your old PC broke before you
could free it), contact us (section 13). A person will look at it and can free your account or put it
right.

## 7. Who receives the data

- **Patreon,** for signing in with Patreon and for your membership details.
- **Supabase,** our hosting provider. It runs our database and server on our behalf, in London (United
  Kingdom), and also sends the confirmation email for developer accounts.
- **GitHub,** only as described in section 3. If you post a bug report there, it is public and covered
  by GitHub's own privacy policy.
- **Discord,** only if you choose to join Reclaimer's Discord server.
- **Authorities,** if the law requires it.

We do not sell your data or share it for advertising.

## 8. How long the data is kept

| Data | Kept |
|---|---|
| Your account: email, name, Patreon ID, roles | While your account exists. Deleted within 30 days of you asking. |
| Your Patreon membership details | While you are a member. Removed when Patreon tells us you left. |
| Patreon's membership messages to our server | 90 days. |
| Which PC holds your account | Until you free it, or your account is deleted. |
| Free-hour minutes for a PC code | Kept so the free hour is not repeated. Deleted if you ask, which also gives that PC a new hour. |
| A sign-in passing from the browser to Reclaimer | Deleted as soon as Reclaimer receives it, and within 2 minutes in any case. |
| A sign-in's IP address and app details | Until you sign out or the sign-in expires. |
| Hosting and GitHub logs | As their own policies say. |
| Data on your computer | Until you delete it or sign out. |

## 9. How the data is protected

- **Encrypted connections:** everything between Reclaimer, our server and Patreon goes over encrypted
  (HTTPS) connections.
- **Passwords:** developer passwords are stored only in hashed form.
- **Signed licences:** licences are digitally signed, so they cannot be altered or forged.
- **Database access:** Reclaimer can reach only your own account's data. Patreon details, PC records
  and the keys that sign licences are held on the server alone.
- **On your PC:** your remembered sign-in is encrypted with Windows' data protection.

## 10. Your choices and your rights

- **Your data:** you can ask to see, correct, delete or receive a copy of your data. You can also ask
  us to stop using it, or object to how we use it. Email us (section 13); we answer within one month.
- **Patreon access:** you can remove Reclaimer's access to your Patreon account at any time, in
  Patreon's settings under apps.
- **In Reclaimer:**
  - **Sign out** deletes the sign-in kept on your PC.
  - **Use on another PC** frees your PC.
  - Untick **Remember me on this PC** to keep nothing between sessions.
- **Complaints:** if you live in the EU, the EEA or the UK, you can complain to your data protection
  authority. In the Netherlands that is the *Autoriteit Persoonsgegevens*.

## 11. Children

Reclaimer is not meant for children under 16. If you believe a child under 16 has given us data,
contact us and we will delete it.

## 12. Changes to this policy

If we change what Reclaimer collects or how it is used, we update this page and its date before the
version of Reclaimer that makes the change is released.

## 13. Contact

**Reclaimer Tools**
Email: [contact@reclaimertools.com](mailto:contact@reclaimertools.com)
