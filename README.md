# better-vivaldi

My recommendations for the ultimate configuration of the Vivaldi Browser :)

**NOTE:** This project can be found on both [Codeberg](https://codeberg.org/Magnesium1062/better-vivaldi), which will act as the main & preferred way to contribute, and [GitHub](https://github.com/Retold3202/better-vivaldi).

# General

Startup -> Default Browser -> **Check on Startup** -> ❌

Startup -> **Homepage** -> `Start Page` ✅

Startup -> **Startup with** -> `Start Page` ✅

Updates -> **Automatically Download and Install Updates** -> ✅

Productivity Features -> **Enable Mail, Calendar, and Feeds** -> ❌ *(if you don't use)*

# Appearance

Website Appearance -> **Force dark theme on all websites** -> ✅

Window Appearance -> **Open Popups in Tabs** -> ✅ *(Why are Firefox and Vivaldi the only browsers with this feature?? Should be default everywhere)*

Window Appearance -> **Use Animation** -> ❌ *(Optional but recommended for lower-end or older devices to improve performance and battery)*

**Menu** -> You can go through here and customize it to your heart's content. I usually delete sections for functionality I don't use, such as `Mail`.

# Tabs

Tab Display -> Tab Bar -> **Display Synced Tabs Button** -> ❌ *(if you don't use Sync)*

# Address bar

Address Field Options -> **Show Full Address** -> ✅

Address Auto-Complete -> **Enabled** -> ❌

Address Auto-Complete -> **Auto-Complete On Item Title** -> ❌

Address Auto-Complete -> **Auto-Complete On Domain First** -> ❌

Drop-Down Menu -> **Show Search Queries in Typed History** -> ❌

Drop-Down Menu Priority -> **Search Suggestions** -> ❌

Drop-Down Menu Priority -> **Direct Match** -> ❌

Drop-Down Menu Priority -> **Frequently Visited Pages** -> ❌

Drop-Down Menu Priority -> **Typed History** -> ❌

Drop-Down Menu Priority -> **Browser History** -> ❌

Drop-Down Menu Priority -> **Sync Tabs** -> ❌ *(if you don't use Sync)*

Drop-Down Menu Priority -> **Vivaldi Pages** -> ❌

**Extension Visiblity** -> `Toggle All Extensions` ✅

Security Features -> **Always Use Secure Connection (HTTPS)** -> ✅

Security Features -> **Strip JavaScript from Pasted Text** -> ✅

Security Features -> **Highlight Base Domain in Address** -> ✅

# Bookmarks

**Open Bookmarks in New Tab** -> ✅

# Search

**Default Search Engine** -> `DuckDuckGo`

**Private Window Search Engine** -> `DuckDuckGo`

Search Field Display -> **Always Search in New Tab** -> ✅

Search Options -> Search in Address Field -> **Allow Control by Extensions** -> ❌ *(Should be default)*

Search Options -> **Keep Typed Text After Searching** -> ❌ *(Should be default)*

Allow Search Suggestions -> **In Address Field** -> ❌

Allow Search Suggestions -> **In Search Field** -> ❌

Allow Search Suggestions -> **Enable Direct Match** -> ❌

**Search Engines** -> Go through here and delete any search engines you don't need/use

# Quick Commands

Search Types and Priority -> **Notes** -> ❌ *(if you don't use)*

Search Types and Priority -> **Browsing History** -> ❌

Quick Command Options -> **Open Links in New Tab** -> ✅

# Privacy and Security

Tracking Prevention -> **Block Ads on Abusive Sites** -> ❌ *(Use [uBlock Origin](https://github.com/gorhill/uBlock) instead, see recommended configuration [here](https://codeberg.org/Magnesium1062/ublock-origin-settings))*

Tracking Prevention -> **Block Hyperlink Audit Tracking** -> ✅

Tracking Prevention -> **Broadcast IP for Best WebRTC Performance** -> ❌ *(Don't set this if you have to call on the web through services like Discord & Zoom)*

Google Services -> **Phishing and Malware Protection** -> ✅ *(Harmless, should be default)*

Google Services -> **DNS to Help Resolve Navigation Errors** -> ❌

Google Services -> **Form Autofill Assist** -> ❌

Google Extensions -> **Meet (was Hangouts)** -> ❌ *(Don't set this if you use screen sharing in the browser)*

Search -> **Suggestions in Address Field** -> ❌

Search -> **Suggestions in Search Field** -> ❌

Show Typed History -> **In Address Field** -> ❌

Show Typed History -> **In Search Field** -> ❌

**Save Browsing History** -> `Session Only`

Autofill -> **Form Autofill** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

Autofill -> **Credit Card Autofill** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

Private Windows -> **Show Introduction** -> ❌

Crash Reporting -> **Allow Vivaldi to Send Automatic Crash Reports** -> ❌

Apple Events -> **Allow Javascript from Apple Events** -> ❌

Tracker and Ad Blocking -> **Blocking Level** -> `No Blocking` *(Use [uBlock Origin](https://github.com/gorhill/uBlock) instead, see recommended configuration [here](https://codeberg.org/Magnesium1062/ublock-origin-settings))*

Tracker and Ad Blocking -> Manage Sources *(This section is only applicable if you do use the built-in content blocking for whatever reason even though not recommended)*:

* Tracker Blocking Sources -> **DuckDuckGo Tracker Radar** -> ✅

* Tracker Blocking Sources -> **EasyPrivacy** -> ✅

* Ad Blocking Sources -> **ABP anti-circumvention list** -> ✅

* Ad Blocking Sources -> **Adblock Warning Removal List** -> ✅

* Ad Blocking Sources -> **Allow ads from our partners (support Vivaldi)** -> ❌

* Ad Blocking Sources -> **EasyList** -> ✅

* Ad Blocking Sources -> **Remove annoyances, can break sites (Fanboy's Annoyance List)** -> ✅

* Ad Blocking Sources -> **Remove cookie warnings (Easylist Cookie List)** -> ✅

<br>

Passwords -> **Save Webpage Passwords** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

Website Permissions -> Global Website Permissions:

* **Autoplay** -> `Block`

* **Geolocation** -> `Block`

* **Camera** -> `Block` *(Obviously don't set if you use sites that need camera access, but you can still set exceptions for sites if needed)*

* **Microphone** -> `Block` *(Obviously don't set if you use sites that need microphone access, but you can still set exceptions for sites if needed)*

* **Motion Sensors** -> `Block`

* **Notifications** -> `Block`

* **Popups** -> `Block`

* **Intrusive Ads** -> `Allow` *(Use [uBlock Origin](https://github.com/gorhill/uBlock) instead, see recommended configuration [here](https://codeberg.org/Magnesium1062/ublock-origin-settings))*

* **Bluetooth Devices** -> `Block`

* **MIDI Devices** -> `Block`

* **Idle Detection** -> `Block`

* **Background Synchronization** -> `Block`

* **USB Devices** -> `Block`

* **Serial Ports** -> `Block`

* **File Editing** -> `Block`

* **HID Devices** -> `Block`

* **Clipboard** -> `Block`

* **Payment Handlers** -> `Block`

* **Augmented Reality** -> `Block`

* **Virtual Reality** -> `Block`

* **Third-Party Sign-in** -> `Block`

* **Window Management** -> `Block`

* **Fonts** -> `Block`

<br>

Cookies -> **Third-Party Cookies** -> `Block All` 

# Downloads

**Save Files to Default Location Without Asking** -> ❌ *(Should be default)*

**Display Downloads Automatically** -> ✅ *(Should be default)*

**Notify on Completed Downloads** -> ✅ *(Should be default)*

# Webpages

Webpages -> **Allow Text Selection in Links** -> ✅ *(Should be default, another feature other browsers need to adopt)*

Webpages -> **Show Selected Text Translate Button** -> ✅

**Play Image Animation** -> ❌ *(Optional but recommended for lower-end or older devices to improve performance and battery)*

Prefetch -> **Prefetch Resources** -> ❌

Plugins -> **Enable Widevine Plugin** -> ❌ - https://www.eff.org/deeplinks/2017/10/drms-dead-canary-how-we-just-lost-web-what-we-learned-it-and-what-we-need-do-next

# Network

User Agent Brand Masking -> **Report Browser Brand as** -> `Google Chrome` *(Should be default)*

User Agent Brand Masking -> **Append Vivaldi Brand** -> ❌ *(Should be default)*

# Start Page

On Vivaldi's Start Page/Speed Dial, feel free to remove the built-in sponsored links.

# Bookmarks

Similarly, I'd also recommend deleting the built-in sponsored bookmarks, as well as the `Vivaldi` folder.

# Sidebar

I usually also remove the links to `Vivaldi Social` & `Vivaldi's Help Center` from the sidebar here as well.

# vivaldi://flags

**#block-insecure-private-network-requests** -> `Enabled`

**#content-settings-partitioning** -> `Enabled`

**#enable-parallel-downloading** -> `Enabled`

**#private-network-access-permission-prompt** -> `Enabled`

**#reduce-accept-language** -> `Enabled`

**#strict-origin-isolation** -> `Enabled`

**#third-party-storage-partitioning** -> `Enabled`

# Additional recommendations

* Keep extensions to a minimum and only install what you actually need. Having unnecessary extensions reduces performance, increases attack surface, increases fingerprintability, etc.

* Similarly, [please don't use more than one content blocking extension](https://x.com/gorhill/status/1033706103782170625).

* Use a private, secure, & reputable DNS provider of your choice. I would recommend setting up your own [NextDNS](https://nextdns.io) configuration if you are able to *(See my recommendations for NextDNS [here](https://codeberg.org/Magnesium1062/nextdns-settings))*, otherwise I would recommend [Quad9](https://quad9.net/).

* Use a (reputable) VPN. I would recommend either [Mullvad](https://mullvad.net/) or [ProtonVPN](https://protonvpn.com/).

* Use a (reputable) anti-virus if possible. On Windows, you can use the built-in [Microsoft Defender Antivirus](https://en.wikipedia.org/wiki/Microsoft_Defender_Antivirus), on macOS, you can stick to the built-in [XProtect](https://support.apple.com/guide/security/protecting-against-malware-sec469d47bd8/web), and on Linux, you can use [ClamAV](https://www.clamav.net/).