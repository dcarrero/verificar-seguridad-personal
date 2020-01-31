[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# Privacy & Securty-Focused Software and Services
> A curated list of privacy-respecting apps, software and providers 🔐

## Intro

You can greatly increase your digital security, by switching to privacy-respecting software. 
Using open-source applications with a strong emphasis on security, will help stop
large corporations profiting from your data, through logging, storing and selling your personal details.


## Password Managers

| Provider |Description |
| --- | --- |
**[BitWarden](https://bitwarden.com)**  | Free and open source, cross-platform password manager with sync
**[1Password](https://1password.com)** | Open source, fully-featured cross-platform password manager with sync. Free for self-hosted (or $3/ month hosted)
**[KeePassXC](https://keepassxc.org)** | Open source, secure password manager, but without cloud-sync capabilities. KeePassXC is a community fork of [KeePass](https://keepass.info/)
**[LessPass](https://lesspass.com)** | LessPass is a little different, since it generates your passwords using a hash of the website name, your username and a single master-passphrase that you reuse. It ommits the need for you to ever need to store or sync your passwords. They have apps for all the common platforms and a CLI, but you can also self-host it.


## 2-Factor Authentication

| Provider |Description |
| --- | --- |
**[Aegis](https://getaegis.app)**  | Free, secure and open source app for manageing 2-step verification tokens, on Android
**[AndOTP](https://github.com/andOTP/andOTP)** | Another open source, secure authanticator app. AndOTP is well established with a strong large user base

**Note:** Don't use your password manager to also store your 2-FA tokens- use a separate application.


## File Encryption

| Provider |Description |
| --- | --- |
**[VeraCrypt](https://www.veracrypt.fr)** | VeraCrypt is open source cross-platform disk encryption software. You can use it to either encrypt a specific file or directory, or an entire disk or partition. VeraCrypt is incredibly feature-rich, with comprehnsive encryption options, yet the GUI makes it easy to use. It has a CLI version, and a portable eddition. VeraCrypt is the successor of (the now depricated) TrueCrypt.
**[Cryptomator](https://cryptomator.org)** | Open source client-side encryption for cloud files- Cryptomator is geared towards using alongside cloud-backup solutions, and hence preserves individual file structure, so that they can be uploaded. It too is easy to use, but has fewer technical customizations for how the data is encrypted, compared with VeraCrypt. Cryptomator works on Windows, Linux and Mac- but also has excellant mobile apps.

If you need to create a compressed archive, prior to encrypting your files, then [PeaZip](https://www.peazip.org/) is a great little cross-platform open source file archiver utility. It allows you to create, open, and extract RAR TAR ZIP archives.


## Virtual Private Networks

VPNs are good for getting round censorship, increasing protection on public WiFi, obscuring your IP address, and reducing what data your ISP can log. But for the most anonymity, you should use [Tor](https://www.torproject.org/).

Before jumping in and signing up for a VPN, there's a couple of things to note:
- A VPN does not make you anonymous- it merely chnages your IP accress to that of your VPN provider, instead of ISP. Your browsing session can still be linked back to your real identity either through your system details (such as user agent, screen resolution even typing patterns), cookies/ session storage, or by the identifiable data that you enter. [Read more about fingerprinting](https://pixelprivacy.com/resources/browser-fingerprinting/).
- VPNs and logging- If you choose to use a VPN because you do not agree with your ISP logging your full browsing history, then it is important to keep in mind that your VPN provider will have access to these logs. Many VPNs claim not to keep logs, but you cannot be certain of this. See [this article](https://gist.github.com/joepie91/5a9909939e6ce7d09e29) for more

You could host your own VPN, which would allow you to have full visibility and control over logs. See [Streisand](https://github.com/StreisandEffect/streisand)

| Provider |Description |
| --- | --- |
**[Mullvad](http://mullvad.net/en/)** | Mullvad is one of the best for privacy, they own all their own servers and have a totally anonymous sign up process, you don't need to provide any details at all, you can choose to pay annonymously too (with Monero, BTC or cash)
**[ProtonVPN](https://protonvpn.com/)** | From the creators of ProtonMail, ProtonVPN has a solid reputation. They have a full suit of user-friendly native mobile and desktop apps. ProtonVPN is one of the few "trustworthy" providers that also offer a free plan

For a full-comparison, see: [thatoneprivacysite.net](https://thatoneprivacysite.net/).

---

**Note**: In order to stay protected, it is important to also: Use strong and unique passwords, 2-factor authentication,
adopt good networking practices and be mindful of data that is collected when browsing the web. See the full
**[personal security checklist](https://github.com/Lissy93/personal-security-checklist/blob/master/README.md)** for all the details 🔐

*Contributions are welcome, and appreciated - to propose an edit [open an issue](https://github.com/Lissy93/personal-security-checklist/issues/new/choose),
or [open a PR](https://github.com/Lissy93/personal-security-checklist/pull/new/master).
See: [`CONTRIBUTING.md`](/.github/CONTRIBUTING.md).*

*Licensed under [Creative Commons, CC BY 4.0](https://creativecommons.org/licenses/by/4.0/),© [Alicia Sykes](https://aliciasykes.com) 2020*

[![Attribution 4.0 International](https://licensebuttons.net/l/by/3.0/88x31.png)](https://github.com/Lissy93/personal-security-checklist/blob/master/LICENSE.md)