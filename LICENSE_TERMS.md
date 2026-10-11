# Zombie Foundry — License Terms

Plain-language terms for what you get when you buy a Zombie Foundry license.
Last updated: 11 October 2026.

Store: <https://smallsoftwarehouse.gumroad.com/>

These terms describe how the license works. They are written to be read, not to
be impressive. If anything here is unclear, ask before buying:
**SmallSoftwareHouse@gmail.com**

---

## 1. What you are buying

A **perpetual license** to use Zombie Foundry on **one computer**.

Perpetual means what it says: the license does not expire, and there is no
subscription. The app you have keeps working, with the features your plan
grants, for as long as you want to use it.

Your license is identified by your **license key plus the email address you
used at checkout**. Keep both.

There are four plans. Every plan runs on one computer; what changes is below.

### Plans and features

| | Lite | Standard | Pro | Max |
|---|---|---|---|---|
| Servers you can manage | 1 | 1 | up to 3 | unlimited |
| Downloads at the same time | 1 | 1 | 2 | your choice (starts at 3) |
| Guided setup (Mega Wizard) | — | ✓ | ✓ | ✓ |
| Automatic restart after a crash (watchdog) | — | ✓ | ✓ | ✓ |
| Install folder of your choice | — | ✓ | ✓ | ✓ |
| Manual refresh of the public IP | — | ✓ | ✓ | ✓ |
| Players: bulk actions, admin filters | — | ✓ | ✓ | ✓ |
| `[ZF]` tag in the server name | yes | yes | no | no |

### MOTD and banner

The **MOTD** is the panel players see when they join; the **banner** is the
strip above it.

| | Lite | Standard | Pro | Max |
|---|---|---|---|---|
| Text MOTD | ✓, with our two lines on top | ✓, all yours | ✓, all yours | ✓, all yours |
| MOTD drawn with the editor | — | ✓ | ✓ | ✓ |
| A page longer than one screen | — | ✓ | ✓ | ✓ |
| Several pages joined by links (multi-page) | — | — | ✓ | ✓ |
| Ready-made templates | — | 2 | 5 | 10 |
| Banner | ours, fixed | ours, or one you draw | ours, one you draw, or a page of yours at an address | as Pro |

The editor is a page that opens in your browser from the app. It works only
together with Zombie Foundry, which saves your project and publishes it.

### Branding on your server

Servers you run with Zombie Foundry carry some Zombie Foundry branding,
depending on your plan. This is part of the price of the lower plans, so it is
stated here rather than discovered later:

- **Lite** — the server name
  starts with a short fixed tag, `[ZF] `; the banner is ours and cannot be
  changed; our two lines open your text MOTD, which the app writes, so do not
  hand-edit it.
- **Standard** — the server name keeps the `[ZF] ` tag. The MOTD is yours,
  text or drawn. The banner is ours, **unless you draw your own**: then the
  banner is yours, and in exchange a Zombie Foundry strip appears at the bottom
  of your drawn MOTD. It stays put while the page scrolls and covers what is
  under it. Switch back to our banner and the strip goes away.
- **Pro and Max** — no branding anywhere: name, MOTD and banner are yours.

The **trial** has the Standard's features and branding, with one difference:
its text MOTD keeps our two lines on top, as on Lite.

### What the drawn MOTD needs from you

A drawn MOTD and banner are web pages, and the player's game has to download
them. **Zombie Foundry serves them from your own computer, through a small web
server built into the app**, so:

1. **A port must be open on your router** towards the computer running Zombie
   Foundry. The app tells you which one, tests whether it can be reached from
   the internet, and has a step-by-step guide. Without it, players do not see
   the drawn pages.
2. The pages travel over **your home connection**: the app shows how heavy
   they are and lets you set a bandwidth limit, shared by all players.
3. A **text MOTD needs none of this**: it is a plain file the game reads
   directly.

Two things worth knowing about **our** banner, because they are not obvious:

1. It is **loaded from our website by the player's game** each time they
   connect. That means we can change what it shows without you updating
   anything — and that if our site is unreachable, players may briefly see a
   browser error in that panel instead of the banner. It never affects the game
   server itself.
2. Using **a page of yours at an address** as the banner (Pro and Max) means
   you need somewhere to put it — we do not host pages or images for customers.
   That address must be a plain `http://` one: the game's built-in browser does
   not load `https://` addresses, which is a limitation of the game, not of the
   app. The app refuses an `https://` address rather than saving one that would
   silently never appear.

None of this collects anything about you or your players.

## 2. Updates

This is the part worth reading carefully, because it is where most software
gets vague.

**Your license is tied to a major version** (1.x, 2.x, 3.x...), not to a
window of time. Buying a license gives you every update released inside that
major version — 1.0.0, 1.1.0, 1.9.3, however many come out — **for as long as
that major version keeps being updated, with no expiry date.**

What is not included is the *next* major version. When 2.0.0 comes out, it is
a separate purchase (see "Major version upgrades" below).

**Nothing is ever taken away from you.** The app keeps working. Every feature
you already have keeps working, forever, on the major version you bought.

## 3. Major version upgrades

When a new major version is released, moving to it is a paid upgrade — your
existing license does not carry forward automatically, the same way buying
one edition of a game does not give you the next one for free.

There is no subscription and no automatic billing: upgrading is always a
one-time, optional purchase you choose to make when the next major version is
out and you want what it adds.

## 4. Upgrades between plans

You can move up at any time by paying the price difference: from Lite to
Standard, Pro or Max; from Standard to Pro or Max; from Pro to Max. Buy the matching upgrade in our store and enter your existing
license key at checkout: the upgrade is applied to that key, which stays the
same. If anything goes wrong, write to **SmallSoftwareHouse@gmail.com**.

An upgrade between plans buys **features, not versions**: your license key and
your computer stay the same, and the major version you are entitled to is
unchanged. Moving to a newer major version is a separate purchase (see
"Major version upgrades" above).

## 5. Updates: optional and required

**Most updates are optional.** When a new version exists, Zombie Foundry tells
you and you decide when to install it.

**Some updates are required.** We mark an update as required when staying on
the older version would cause problems: for example when it can no longer work
correctly with the online services the app relies on (the license check, the
plugin catalogue, the update system), when it fixes a security issue, or when
it fixes a defect that could damage your servers or your data. We decide this
case by case.

When an update is required, the app tells you, gives you a short grace period,
and then asks you to update before you continue. A required update is always
free, never changes your plan, and keeps your servers and settings as they are.

Previous releases stay available for download at
[github.com/SmallSoftwareHouse/zombie-foundry/releases](https://github.com/SmallSoftwareHouse/zombie-foundry/releases).
A version older than the required one may no longer start normally: it will
ask you to update.

## 6. Internet connection and our commitment to you

Zombie Foundry checks your license online when it starts. This is how the one-computer
limit works.

That means your license depends on our servers being reachable. We think you
are owed a commitment in return:

**If Zombie Foundry is ever discontinued, we will publish a final build
that does not require online validation**, so that the perpetual license you
bought stays usable regardless of what happens to us.

## 7. Moving to another computer

One license, one computer. If you change machine, open Zombie Foundry on the
new computer and enter your license key together with the email address you
used at checkout: the app detects that the key is tied to a different device
and offers a self-service transfer (press F2). We then send a confirmation
link to that email address — clicking it completes the transfer. This
confirms you actually own that inbox, and it takes effect as soon as you
click. There is no charge for this.

If self-service transfer is ever unavailable for some reason, write to
**SmallSoftwareHouse@gmail.com** and we will sort it out manually.

## 8. Trial

A 15-day trial of the Standard, on one server, is available before you buy. One
trial per email address and per computer.

When you decide to buy, enter your trial license key in the optional
"License Key" field at checkout: your trial converts to the plan you bought,
**keeping the same key** — no new key, nothing to re-enter in the app. Leave
the field blank and you get a separate new key instead.

Servers you created during the trial are not deleted if you then buy a smaller
plan. Note that Lite uses a fixed install folder: servers created in a custom
folder (from the Standard up) cannot be managed with Lite.

During the trial, servers carry the Standard's branding, and a text MOTD keeps
our two lines on top as on Lite (see "Branding on your server" above). Buying
the Standard removes those two lines; buying Pro or Max removes all branding.

## 9. Refunds

The 15-day trial exists so you can evaluate Zombie Foundry before paying, so we
do not offer refunds as a matter of course.

Purchases go through our store on **Gumroad**, which acts as merchant of
record: Gumroad takes the payment, handles any applicable tax and issues the
receipt. Your statutory rights as a consumer are unaffected by anything
written here.

Prices are listed in EUR, but Gumroad charges everyone in **US Dollars**: the
amount is converted at checkout, and if your card is in a different currency
your bank may convert it again and charge its own fee on top. This is
Gumroad's own payment processing, not something we control.

## 10. Changes to these terms

If these terms change, the change applies to purchases made after the change.
What you bought under the terms in force on the day you bought it stays as it
was.

---

Zombie Foundry is developed by Small Software House.
Questions: **SmallSoftwareHouse@gmail.com**
