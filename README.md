# opsec-startup

This is a quick guide for setting up a casual pseudonym for ethical hacking activities such as: bug bounty or VDP, or Capture the Flag events, etc.

## 1. Keep your lives separate

Even though you are working on ethical hacking activities, it's still a very good idea to keep this and your real (personal and professional) life separate.

- You will be connecting to potentially dangerous networks for CTF's.
- You will be running potentially dangerous scripts.
- You could get entangled with a not-so-ethical hacker.

There is unbounded upside and NO downside to keeping this persona separate from your real life. What this might mean practically:

1. Use a physically separate computer.
2. Never log in as your alter-ego from your personal machines / never log in as your real self on your alter-ego machine.
3. Don't cross your two lives.

## 2. Start with a Kali/Parrot laptop

[Kali Linux](https:/www.kali.org) is the de facto pen testing and red team Linux distribution, but there is [ParrotOS](https://www.parrotsec.org/) and [others](https://www.makeuseof.com/best-linux-distros-for-penetration-testing/). Ideally, start from an extra, low-cost laptop. If you want good and very cheap, go get a "Lenovo Thinkpad" on eBay. If you want a step up and have a little bit more money, get a "Thinkpad X1 Carbon" or "Thinkpad X1 Yoga". Those are the thin-and-light / ultrabook form factor. They are all great machines, very reliable, great specs, and are generally indestructible.

## 3. Establish a "hacker alias", or pseudonym

Think of a name that is unique and where that name will be available on many platforms. If you choose a name that is common in geek culture, it will likely already be taken. Instead, you should ideally come up with a name that is uncommon and will likely be available.

## 4. Establish Core Services (mail, VPN, and password manager)

The foundation of this persona will be a combination of an email address and a password manager. These are the only ONLY passwords you'll need to remember. ALL other passwords will be managed by your password manager.

### 4a. Email + VPN

One common solution here is to use [Proton Mail](https://proton.me/mail). This is an end-to-end encrypted e-mail provider that also gives you basic VPN via it's [Proton VPN](https://protonvpn.com/) and some cloud storage via [Proton Drive](https://proton.me/drive/download), all for free. So, it's a secure, one-stop-shopping platform.

There is also [TutaNota](https://tutanota.com/) and [other services](https://reclaimthenet.org/end-to-end-encryption-email) too.

> **TURN ON 2FA for your email provider.** Your e-mail is how you get into and recover your password manager.

### 4b. Why VPN?

When you are doing Capture The Flag (CTF) type events, you are usually VPN'ed into a private network, which is not a problem for you. However, if you intend to do bug hunting (bug bounty or VDP), then you will be doing "hacking activities" from your home Internet Service Provider (ISP) presumably. It is possible / likely, you will get a "Cease and Desist" letter from your ISP warning that if you continue doing hacking activities, they will cancel your internet access. So, starting with this reason alone:

> **ALWAYS be connected to a VPN while doing hacking activities.**

If you don't use Proton Mail and Proton VPN, but go with TutaNota for example, use a reasonably-trusted VPN provider. There are many that are free - but understand they will likely capture anything you send over the wire, which means your alter-ego identity is always at risk.

### 4c. Password Manager

In present day, they are all about the same: trustworthy. Even though it's a trade-off, if you have a really good Master Password and multi-factor authentication, then password managers are worth the risk. I'll spike-out LastPass as an example to use. Install the LastPass extension in your browser(s). Create an account, but don't create one using your core e-mail address. Most platforms (e.g. Gmail, Outlook, ProtonMail, etc) support the idea of injecting arbitrary `+aliaswords` in your e-mail address. This gives you a unique e-mail address to use on websites, but the mail still comes to your mailbox. 

For example, you might give Wells Fargo the address of `jdoe+wellsfargo@pm.me` and Spectrum `jdoe+spectrum@pm.me`. Well, for your password manager, consider using something like `jdoe+passman@proton.me`.

> **TURN ON 2FA for your password manager.**

## 5. Establish Hacking Services

At this point, we have an e-mail address with 2FA turned on. We used that to set up a password manager, which also has 2FA turned on, and we're connected to the internet via a VPN. Next, let's go set up our online identity across some key sites:

### 5a. Setup: [`github.com`](https://www.github.com/)

This is my first stop because via some private repositories, I can organize my tools, write-ups, cheatsheets, etc. Create an account using your same hacker alias, or pseudonym.

### 5b. Setup: [`bugcrowd.com`](https://www.bugcrowd.com/)

There are two main platforms for Bug Bounty Programs and Vulnerability Disclosure Programs. Create an account using your same hacker alias, or pseudonym.

### 5c. Setup: [`hackerone.com`](https://www.hackerone.com/)

This is the other main platforms for Bug Bounty Programs and Vulnerability Disclosure Programs. Create an account using your same hacker alias, or pseudonym.

### 5d. Setup: [`tryhackme.com`](https://www.tryhackme.com/)

This is a site for CTF's and learning. Create an account using your same hacker alias, or pseudonym.

### 5e. Setup: [`hackthebox.com`](https://www.hackthebox.com/)

This is a site for CTF's and learning. Create an account using your same hacker alias, or pseudonym.

### 5f. Setup: [`twitter.com`](https://www.twitter.com/)

Twitter is known for being a toxic cesspool, but it is the most vibrant place to get current cybersecurity news. So, it's good to have an account there. As of this writing, it's been re-branded as "X" and is transitioning to another purpose. However, at the moment, this platform is still the best place to get up-to-the-minute infosec news. Create an account using your same hacker alias, or pseudonym.

### 6. Conclusion

That's pretty much it. You now have a secure email address with 2FA, which gives you access to your password manager (which also has 2FA), and that password manager gives you access to all of these sites, using very strong passwords. All of this is under your pseudonym, or hacker alias. You now have an "identity" to work from, which is separate from your personal and professional persona.
