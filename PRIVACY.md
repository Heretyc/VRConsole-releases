# VRConsole Privacy Policy

Effective January 25, 2026

(© 2026 Lexi. All rights reserved.)

## TL;DR (Summary)

### Scope:
This Privacy Policy explains what personal data VRConsole collects and how it’s used. VRConsole is built by a solo developer (Lexi) and respects your privacy. The policy is meant to comply with GDPR (EU law), US privacy laws (like CCPA/CPRA in California), and other relevant regulations.

### Data Collected:
VRConsole only collects the minimal data needed to function. This includes things like your VRChat login credentials (which you provide to log in through the tool), your Patreon username and subscription tier/status (to verify feature access), and possibly some basic technical info (like your VRChat account ID and the fact that you’re using VRConsole, or your VRConsole version for update checks). VRConsole does NOT collect things like your real name, address, or other personal details unrelated to its functionality.

### Use of Data:
Your data is used only to provide the VRConsole service – for example, using your VRChat credentials to log you into VRChat, or checking your Patreon status to enable features. We do not use your data for marketing, and we do not sell or share your personal data with third parties for their own use. There are no ads or trackers in VRConsole.

### Third-Party Services:
VRConsole interacts with a few external services: VRChat (for core features), Patreon (for authentication and tier verification), and GitHub (to check for software updates). These services have their own privacy policies. VRConsole only communicates with them as needed (e.g., logging in, verifying subscription, checking for updates). No other third parties get your data from VRConsole.

### Credentials & Security:
VRConsole never permanently stores your passwords. When you enter your VRChat or Patreon credentials, they are used to get a login token or authenticate the session, and that’s it. Credentials aren’t sent anywhere except to the respective service (VRChat or Patreon) over an encrypted connection. VRConsole does not send your credentials to Lexi or any unknown servers. We take reasonable measures to secure any data in transit. Ultimately, you should safeguard your own login info – don’t share it and be careful if using VRConsole on public machines.

### No Data Selling/Sharing:
We do not sell, trade, or rent your personal information. We also don’t share it with third parties, except as necessary for providing the service (for instance, obviously VRChat gets your login data to log you in, and Patreon gets your ID to verify you). There’s no analytics or advertising built into VRConsole.

### Data Storage & Retention:
As a client-side tool, most personal data is handled on your own device and by the services you connect to (VRChat/Patreon). Lexi does not operate a server that is hoarding your data. VRConsole might cache certain tokens or settings locally on your computer to make your experience smoother (e.g., keeping a session token so you don’t have to log in every time, if such a feature exists), but this stays on your machine. We don’t retain your personal data on our side beyond what’s necessary for support or legal compliance.

### GDPR & Rights:
If you’re in the EU (or similar jurisdictions), you have rights over your data: access it, correct it, delete it, restrict or object to processing, etc. Because we barely keep data (and mostly none on our servers), there’s limited data we can actually give or erase – but whatever we have, you can ask. We will also inform you if any breach occurs that affects your data.

### California/US Privacy:
We comply with applicable US laws like the California Consumer Privacy Act (CCPA). We don’t sell personal info (so no need for an opt-out of sale). California users can request to know what personal info we have (if any) and request deletion. Again, we have minimal info, but we will honor such requests. We won’t discriminate against you for exercising privacy rights.

### Children:
VRConsole is not intended for children under 13. We do not knowingly collect personal information from anyone under 13. If you’re under 13, you should not use VRConsole. If we learn that we’ve inadvertently collected info from a child under 13, we’ll delete it. VRConsole also does not make any special checks on age or content – it relies on VRChat’s systems. So if a minor uses VRConsole and accesses mature content in VRChat, that’s beyond VRConsole’s control (it’s the user’s responsibility to follow VRChat’s age rules). Parents should supervise any minor (13+) who uses VRChat/VRConsole.

### Jurisdiction & Enforcement:
This policy is intended to be globally applicable. Depending on where you live, you might have specific privacy rights (we’ve tried to cover the main ones). Any disputes regarding privacy are handled per the Terms of Service (usually via arbitration and under Lexi’s jurisdiction law).

### Contact:
If you have questions or want to exercise any rights (like getting a copy of your data or deleting it), you can contact Lexi through the official channels (such as the contact email or Patreon messaging). We’ll do our best to help, but remember this is a small operation.

Please read the full Privacy Policy below for more details and specifics. If anything is unclear, feel free to reach out for clarification. Using VRConsole means you agree to this Privacy Policy and the Terms of Service.

---

# VRConsole Privacy Policy (Full Agreement)

# 1. Introduction and Scope

This Privacy Policy describes how VRConsole (the “software” or “tool”), developed and operated by Lexi (“we” or “us”), collects, uses, discloses, and protects your personal information. It applies to all users of VRConsole worldwide, and is designed to meet requirements under global data protection laws, including the European Union’s General Data Protection Regulation (GDPR) and relevant United States privacy laws (such as the California Consumer Privacy Act, “CCPA”, as amended by CPRA). Our goal is to be transparent about data practices and ensure you understand that we take a minimalist approach to data collection. We only gather what we truly need to make VRConsole work.

By using VRConsole, you consent to the practices described in this Privacy Policy. If you do not agree with this policy or the Terms of Service, you should not use VRConsole. This Privacy Policy is incorporated into and is subject to the VRConsole Terms of Service.

# 2. Who Is the Data Controller?

For purposes of data protection law (like GDPR), Lexi (the creator of VRConsole) is the “data controller” of your personal information processed via VRConsole. This means Lexi determines how and why your personal data is processed in the context of providing VRConsole. We are committed to protecting your data. Contact information is provided at the end of this policy for any inquiries or requests regarding your personal data.

If Lexi is located outside your country (for example, if you are in the EU and Lexi is in the U.S.), your data will be transferred to that country (see “International Data Transfers” below).

# 3. What Data We Collect

We strive to collect only the information that is necessary for VRConsole to function properly and to provide you with any support or services related to it. Here are the categories of data that VRConsole may collect or process:

## 3.1. User Credentials:

VRChat Login Credentials: When you use VRConsole to interact with VRChat’s API or network, you will need to provide your VRChat login (typically a username/email and password, or an auth token). VRConsole will collect these credentials at the time you enter them in order to log you into VRChat through the tool. Important: VRConsole does not permanently store your VRChat password. It is used in-memory to authenticate with VRChat’s servers. After logging in (and obtaining a session token from VRChat), __**the password is not retained by the software**__. The session token may be stored in memory or temporarily on your device to keep you logged in during the session, but it’s not transmitted to any third party besides VRChat itself.

Patreon Authentication: If you link your Patreon account to VRConsole (for example, to prove you are a supporter at a certain tier), VRConsole will collect your Patreon OAuth token as part of that login flow. Like with VRChat, Patreon credentials (username/password) are not stored by VRConsole. VRConsole will redirect you to Patreon’s official login page or use an API token exchange. It will receive back an access token or confirmation that you are a Patreon supporter with a certain tier. VRConsole will store basic identifying info from Patreon like your Patreon user ID, username, and current pledge level/tier, as needed to unlock features. This info is stored locally (on your device) and/or in memory. It is not sent to any third-party except Patreon (obviously) as part of verification. We do not collect your payment details from Patreon.

## 3.2. Account and Profile Data:

VRChat Account Data: Through the operation of VRConsole, we may have access to certain information from your VRChat account, such as your VRChat user ID, username, avatar information, friends list, status, or other in-game or profile data that VRChat’s APIs or systems expose to VRConsole. VRConsole uses this data to display information to you or to facilitate the tool’s features (for example, showing your online friends or sending invites, if those are features of VRConsole). This data is fetched from VRChat on the fly and is not transmitted to Lexi’s servers (since typically, VRConsole does not have a centralized server — it’s a client-side application). The data may be cached in your device’s memory while the program runs, but it’s not something we collect in a database on our side.

Patreon Supporter Data: If applicable, VRConsole may store a record on your device that you are a supporter (like “user is Tier 2 supporter until date X” or an access token to re-verify your status). The personal info from Patreon would at most include your Patreon user ID and membership status/tier. We do not receive your real name or address from Patreon unless you explicitly provide it for some reason (which the normal use of VRConsole will **never** require).

## 3.3. Technical and Usage Data:

Device/Software Info: VRConsole might collect basic technical information about the environment in which it runs. For instance, it may detect your operating system version, VRConsole version number, or system architecture, mainly to ensure compatibility and to check for updates. It might also log error messages or debug information if something goes wrong. This kind of data helps Lexi troubleshoot issues. Normally, this information stays on your device (like in log files). We do not automatically send diagnostics or telemetry to a server without your knowledge. If there is an optional feature to send error reports, it will be clearly indicated and likely ask for your consent.

Usage Logs: VRConsole may keep local logs of certain actions (for example, an output console that shows what actions you’ve taken or what responses come from VRChat’s API). These logs can include timestamps, actions performed, and any messages (which might include your user ID or the IDs of other users you interact with via VRConsole). These logs are primarily for your reference and for debugging. They are not transmitted to Lexi by default. If you seek support and choose to share a log with Lexi, that is under your control (you’d manually send it, for example).

## 3.4. Support Communications:
If you contact Lexi for support (say via email or Patreon message), we will obviously receive whatever information you choose to send in that communication. That could include your name, contact info, and details about your issue. We will use that information to help resolve your support request. Support communications are kept private and are not shared except as needed to fix the problem. We might keep a record of support conversations (for instance, in an email inbox or Patreon message history) so we have context if you reach out again. These communications will be treated as confidential.

## 3.5. Sensitive Personal Data:
We do not intend to collect any sensitive personal data (such as racial or ethnic origin, political opinions, religious beliefs, health information, or biometric data). VRConsole does not need any of that information. Please do not provide any such data during support requests either. We also do not collect information about your real-world identity beyond what is described above.

### Summary: In plain terms
The data VRConsole deals with is mostly your login info and game-related data to make the tool work. It’s not grabbing unrelated personal details. The most personally identifying pieces are your account IDs and login tokens, which we handle carefully.

# 4. How We Use Your Data

We use the collected data solely for the following purposes:

## 4.1. Providing the VRConsole Service:

Authentication: We use your VRChat credentials to log you in to VRChat’s services via VRConsole, and your Patreon credentials/tokens to verify your supporter status. Without this, VRConsole’s core functions (connecting to VRChat, unlocking patron-only features) wouldn’t work.

Feature Functionality: Data from VRChat (like your friends list or avatar info) is used to power VRConsole’s features (for example, if VRConsole has a friends management UI or world traversal tools, it uses the data from VRChat to show you relevant info). Similarly, Patreon info is used to determine feature access (e.g., “if user is Tier 2, enable Feature X”).

Updates and Compatibility: Technical info like VRConsole version and OS may be used to decide when to prompt you for an update or to ensure compatibility (e.g., “User is on v1.2, current version is v1.3, show update notification”).

## 4.2. Customer Support:
If you reach out for help, we’ll use any information you provided (like error logs or descriptions) to troubleshoot and assist you. This may involve reading through portions of your log files or configuration to identify the issue. We only use that information to respond to your inquiry and improve the software if needed (for instance, fixing a bug that you reported).

## 4.3. Improvements and Development:
We might look at aggregated or anonymized data to understand how VRConsole is used and what could be improved. For example, if many users voluntarily share that a certain feature is confusing, or if crash logs (when shared) indicate a common problem, we will use that to prioritize fixes. We do not have analytics that track your usage silently; any feedback for improvements is likely via direct user communications or voluntary feedback. If we ever implement any sort of telemetry or analytics in the future to guide development, we will update this Privacy Policy and likely provide an opt-in mechanism. Currently, VRConsole does not phone home with usage stats.

## 4.4. Legal Compliance and Protection:
In the unlikely event that we need to use or disclose data to comply with a legal obligation (for example, a law enforcement request or to comply with tax laws regarding payments), we will only use the minimum necessary information and only as required by law. Also, if necessary, we may use data to protect our rights or users’ rights – for instance, investigating fraud or abuse involving VRConsole. But such scenarios are rare and would typically involve only relevant data (like identifying someone attempting to hack the software, etc.).

**We do not use your data for any marketing or advertising purposes.** We do not sell your data to advertisers or bombard you with emails. In fact, since this is not a commercial SaaS product, there’s no traditional “marketing” pipeline. You might get updates or posts via Patreon if you are a subscriber, but those are part of the service you signed up for (and you can manage notifications on Patreon). We won’t share or use your info to try to sell you unrelated products.

# 5. How We Disclose or Share Your Data

Lexi understands that your data is your own, and protecting it is crucial. VRConsole’s design inherently limits data sharing, but here we outline the circumstances under which we might disclose information, and clarify that third-party “sharing” is basically limited to the services you already know about (VRChat, Patreon, GitHub).

## 5.1. Third-Party Service Providers:
VRConsole itself does not employ third-party service providers in the typical sense (like we don’t have a cloud database or analytics provider that gets your data). The main “providers” involved are:

VRChat: As explained, when you use VRConsole, your data goes to VRChat’s servers (for authentication and fetching in-game info). VRChat Inc. then processes that data under their own privacy policy. VRConsole isn’t handing your data to VRChat outside of that normal process – you are effectively logging into VRChat as if you were using the VRChat client. VRConsole is just a different interface to do so.

Patreon: VRConsole will communicate with Patreon’s API to verify you. In doing so, Patreon receives whatever info is required for that (your access token and a request for your membership status). Patreon will process that under their privacy policy. VRConsole doesn’t give Patreon any info beyond what Patreon already has (since you log into Patreon to get the info).

GitHub: When checking for updates, VRConsole might contact GitHub (or an update server). This is generally a download request for a version file or release package. In that exchange, minimal data like your IP address and maybe the current version of VRConsole might be conveyed through user agent strings or query parameters. GitHub will log requests as any web server does, but this is standard internet usage and not a unique “data share” orchestrated by us beyond looking up if a new version exists.

### Crucially, we do not have other third-party processors where we routinely send your personal data. There’s no marketing platform, no data analytics service, no social media integration that pipes your data out.

## 5.2. Legal Requirements:
We would only disclose your data outside the above services if required to comply with a legal obligation. For example:

If a court order, subpoena, or other government demand (valid and lawful) requires us to turn over certain data, we might have to comply. Given the minimal data we have, it’s unlikely, but this is a standard clause.

If necessary to enforce our Terms of Service or to protect the rights, property, or safety of Lexi, VRConsole users, or others. For instance, if someone is using VRConsole to do something harmful and we need to provide data to law enforcement to stop it. Again, we have very limited access to user data, but if logs or user identification is relevant and legally requested, it might be disclosed.

We will strive to notify you if we are compelled to disclose your data in such a way, unless we are legally prohibited from doing so (gag order, etc.).

## 5.3. Business Transfers:
Currently, VRConsole is a personal project, not a company. If in the future Lexi decides to transfer development to someone else, or if VRConsole is sold or transitions to a different maintainer, the personal data we have (if any) might be transferred as part of that arrangement so the new maintainer can continue providing the service. Any such transfer would of course be under similar privacy commitments. We would inform users of any change in ownership or control of their personal information. If you are not comfortable with the new owner, you would have the opportunity to discontinue use.

## 5.4. Aggregate or De-Identified Data:
We may share aggregated, anonymized usage information publicly or with partners. For example, we might say “VRConsole has X number of users” or “Feature Y is used by Z% of the user base” without revealing any personal data about any individual user. This kind of information, if shared, contains no personal identifiers and is purely statistical.

## What We Don’t Do:

- We do not sell your personal information to anyone. (Under CCPA, “sell” broadly means sharing for benefit; we don’t do that either.)

- We do not share your info with advertisers or unrelated third parties.

- We do not share contact info (like your email, if we have it from support) with other companies.

- We do not trade or exchange your data for any purpose outside of what’s necessary for running VRConsole.

# 6. Data Storage and Security

## 6.1. Where Your Data Is Stored: 
Because VRConsole is primarily a client-side application, most of your personal data lives either on your own device or with the third-party services you interact with (VRChat, Patreon). For example: your VRChat login and session data resides on your PC and on VRChat’s servers; your Patreon token is on your PC and Patreon’s system. Lexi does not have a dedicated server storing user databases or cloud storage with your profile (with the possible exception of Patreon verifying tokens, but that is typically handled by Patreon’s infrastructure).

We might keep some records on our side in specific cases:

Support Data: If you email us or send logs for troubleshooting, those could be stored in our email system or a secure folder.

Patreon Records: Patreon may provide creators with a list of their patrons (like usernames, pledge amounts, and maybe email addresses if you agreed to share). As the creator, Lexi might have access to a Patreon dashboard that lists supporters. If so, that’s technically storing some of your personal data (Patreon username, pledge level, possibly your email or Discord if you linked it). That information is kept secure via Patreon’s site and any local copy (for example, if Lexi downloads a list for record-keeping) would be protected. We would use that only for managing access and thanking supporters, etc., and not share it. If you stop being a patron, your name might drop off that list over time (Patreon usually keeps records of past pledges though).

## 6.2. Security Measures: 
We take reasonable measures to protect the information we process:

Encryption: When VRConsole communicates with VRChat, Patreon, or GitHub, it uses secure, encrypted connections (HTTPS/SSL) just like a web browser would. This means your credentials and data are encrypted in transit over the internet.

Secure Storage: On your device, any sensitive information (like tokens or cached credentials) is stored as securely as the environment allows. For instance, if VRConsole uses a configuration file or Windows registry to store a token, it will do so in a way that’s not plain-text accessible to casual browsing (whenever possible). However, we rely on your device’s security – if your computer is infected with malware or someone has access to your filesystem, we can’t fully prevent them from finding saved data. We do not intentionally store your raw passwords at all, and any tokens stored are ideally encrypted or in system-protected areas.

Developer Practices: Lexi handles any data she directly accesses (like support logs or Patreon lists) with care. For example, if a support log has sensitive info, it’s kept confidential and usually deleted once the issue is resolved. Devices used to access such info are password-protected and have security measures.

No Unnecessary Collection: By minimizing what we collect, we inherently reduce risk. There’s no credit card info or social security numbers or such in our system because we never handle those. Less data stored means fewer concerns about breaches.

Despite our efforts, it’s important to understand that no system is 100% secure. We cannot guarantee absolute security of data, especially given that much of it resides on your end or with third-party platforms. You should also do your part: keep your computer secure, use strong and unique passwords for VRChat/Patreon, and don’t share your accounts.

## 6.3. Data Retention: 
We retain personal data only for as long as necessary to fulfill the purposes outlined in this policy or as required by law. Since most data is transient:

VRChat/Patreon Credentials: Not stored beyond the session (except maybe tokens cached until they expire or you log out). Once you stop using VRConsole or close it, those should no longer be accessible to us. If any token is saved to keep you logged in, it’s likely saved locally and can be cleared by you (for example, by a “logout” function in VRConsole or by deleting a config file).

Patreon Supporter Info: Patreon maintains a list of current patrons for access control, we update that list as needed. If you cancel your subscription, we’ll update our records accordingly (likely removing your access in VRConsole after your paid period ends). Historical patronage info might be kept for accounting or thank-you records, but we won’t use it for anything beyond project-related purposes.

Support Communication: We may retain emails or messages you send for reference, but if they contain sensitive info and it’s no longer needed, we can delete them upon request.

Legal Obligations: If there are any legal reasons to keep data (like tax records for payments, or records of consents), we keep those as required by law.

When we no longer need personal data, we will securely erase or anonymize it. For example, if we ever had a user database (we currently don’t), and you requested deletion or we shut down the service, we’d wipe the personal info in it.

# 7. Your Rights and Choices

Depending on your location and applicable laws, you may have some or all of the following rights regarding your personal data. VRConsole’s data practices are straightforward, so while we list these rights for completeness, note that in practice we often have minimal data to work with for fulfilling such requests.

## 7.1. Rights Under GDPR (for EU/EEA users): 
If you are in the European Union, United Kingdom, or a jurisdiction with similar laws, you have the following rights with respect to your personal data:

Right to Access: You can ask us to confirm if we are processing your personal data and request a copy of that data.

Right to Rectification: If you believe the personal data we have about you is incorrect or incomplete, you can request that we correct or update it. (For example, if your email changed and we have your old one from a support ticket.)

Right to Erasure (Right to be Forgotten): You can request that we delete the personal data we hold about you. Keep in mind, most of your data is on your side or with VRChat/Patreon. We can delete any records we might have (like support emails or your Patreon ID in our list) upon request, as long as we don’t need to keep it for legal reasons. If you want VRChat or Patreon data deleted, you’d have to request deletion from those companies, as we don’t control their data.

Right to Restrict Processing: You can ask us to limit how we use your data in certain circumstances (for example, while a complaint or request is being resolved, you could request we hold off on some processing). Given our minimal processing, this might not often apply, but the right exists.

Right to Data Portability: You can request a copy of your data in a commonly used machine-readable format, to transfer to another service. We don’t really collect profile data beyond what’s in VRChat/Patreon, but if you wanted, we could provide something like “Patreon ID X, Tier Y, as of date Z” or any other data you provided to us.

Right to Object: You can object to certain processing (like if we were doing direct marketing, which we are not). You can also object to processing based on legitimate interests. We will honor objections within the bounds of the law and the practical usage of the software. If your objection is to something essential (like using your credentials to log in), we might have to advise you not to use the tool, since we can’t provide it otherwise.

Right not to be subject to Automated Decisions: We don’t do any automated decision-making or profiling that would have legal or significant effects on you. VRConsole doesn’t approve/deny something about you automatically beyond simple feature gating by Patreon tier (which you control by subscribing). So this is not applicable in any meaningful way here.

To exercise any of these rights, please contact us (see Section 9 for contact info). We may need to verify your identity (to make sure we’re giving data to the right person or deleting the correct account). Since we often have very little identifying info, we might verify through your Patreon account or by having you prove control of your VRChat account, etc., depending on the request. We will respond to your request within a reasonable timeframe and in accordance with applicable law (GDPR usually requires within 1 month, which we will aim to meet).

Also, EU/UK users have the right to lodge a complaint with a data protection authority (DPA) if you believe we have infringed your data rights. We encourage you to contact us first to resolve any issue, but you can go to your country’s supervisory authority if needed. For example, in the UK it’s the ICO; in Ireland, the Data Protection Commission, etc.

## 7.2. Rights Under CCPA/CPRA (for California users): If you are a California resident, the CCPA (as amended by the CPRA) gives you rights regarding your personal information:

Right to Know: You can request that we disclose what personal information we have collected about you, including the categories of sources, the purpose for collecting, and any third parties we share it with. We can tell you basically what’s outlined in this Privacy Policy: we have your login credentials (transiently), Patreon tier, etc., sources are you and those platforms, purposes are to provide the service, and we share with no one except VRChat/Patreon as needed.

Right to Access: Similar to GDPR’s access right, you can request the specific pieces of personal information we have about you.

Right to Delete: You can request that we delete personal information we collected from you. Again, aside from perhaps a Patreon ID in a list or support emails, we don’t have much to delete. But if you ask, we will delete what we have that is identified with you (unless retaining is necessary for legal reasons or a “business necessity” as defined by law).

Right to Correct: If we have inaccurate personal info, you can request we correct it.

Right to Opt-Out of Sale/Sharing: We do not sell or share your personal information for cross-context behavioral advertising. Therefore, there is nothing to opt out of in that regard. We don’t have a “Do Not Sell” link because we don’t sell data.

Right to Limit Use of Sensitive Info: We do not collect sensitive personal information as defined by the CPRA (like precise geolocation, race, health, etc.) beyond what’s needed for service (and that’s not used to infer characteristics about you). So this is not applicable – we’re not using or disclosing sensitive info in a way that triggers this right.

Non-Discrimination: We will not discriminate against you for exercising your privacy rights. That means if you request deletion or access, we won’t deny you the software or provide a different quality of service just because you exercised your rights. However, note that deletion of essential data (like your Patreon ID that grants you a feature) might mean that feature no longer recognizes you – but that’s a logical consequence, not discrimination. We won’t, for instance, block you from using a free feature because you asked what info we have.

To exercise any of these California rights, you (or your authorized agent) can contact us (see Section 9). We will likely treat it similarly to a GDPR request in terms of timing and verification. California law may require certain verification steps (which we’ll follow, such as needing a signed letter if an agent makes the request on your behalf, etc.).

## 7.3. Choices and Controls:

Credentials: You always have the choice not to input your credentials into VRConsole. Of course, without them, you can’t log in and use it. But it’s your choice. Similarly, using Patreon is optional – if you choose not to link Patreon, the program simply will not function.

Opt-Out of Communications: Since we don’t really send marketing communications, this is mostly about Patreon. If you get update notifications via Patreon and want to opt out, you can unsubscribe from those notifications on Patreon’s side. If we ever send any direct emails (unlikely, except replies you initiate), you can tell us to stop.

Device Permissions: VRConsole might request certain permissions on your device (for example, if in the future it had a feature to capture your screen or something). You’re free to grant or deny such permissions. Denying might limit functionality, but it’s your choice.

Uninstall: You can always uninstall VRConsole. That’s the ultimate way to stop any data collection by this or any other software. Once uninstalled, it won’t access your data. You may also revoke VRConsole’s access to your VRChat or Patreon (e.g., change your password to invalidate tokens, or de-authorize any Patreon app tokens) if you want to be extra sure.

# 8. Children’s Privacy

## 8.1. Not for Under 13: 
VRConsole is not directed to children under the age of 13. We do not knowingly collect personal information from children under 13. If you are under 13, you are not allowed to use VRConsole or provide any personal info to us (including through support requests). VRChat itself prohibits children under 13 from using their platform, and Patreon also has age restrictions. So the entire ecosystem VRConsole operates in is not meant for young children.

## 8.2. Ages 13–17: 
If you are between 13 and 17 (or the age of majority in your jurisdiction), you should only use VRConsole with the involvement and consent of a parent or guardian. While we might collect the same minimal info from you (as described above), if you or your guardian request deletion of any such info, we will honor it. We encourage parents to supervise their teenagers’ use of VRChat and VRConsole, especially because VRChat can expose users to various content.

## 8.3. No Age Verification by Us: 
Importantly, VRConsole does not independently verify your age. We do not have mechanisms to detect if a user is a minor beyond relying on VRChat’s and Patreon’s requirements. VRConsole assumes that if you have a VRChat account and a Patreon account, you meet their age restrictions. VRConsole does not filter or restrict content based on age. For instance, VRChat might have “mature” content or worlds flagged for certain ages – VRConsole has no built-in feature to block a minor from accessing those if the minor is using VRChat. We do not make independent determinations about minor status or enforce access restrictions beyond what VRChat itself enforces. Any exposure to age-inappropriate content via VRChat while using VRConsole is the user’s (and if underage, the guardian’s) responsibility, not VRConsole’s. Users (and parents) must ensure compliance with VRChat’s age rules and content guidelines.

## 8.4. Removal of Minor’s Data: 
If you are a parent or guardian and you believe we might have any personal information from or about a child under 13, please contact us immediately. If we discover or are notified that we have inadvertently collected personal data from a child under 13, we will promptly delete such data from our files. Since we generally don’t store user data centrally, this would likely mean ensuring any support tickets or Patreon records are scrubbed for that individual, and blocking further use.

# 9. International Data Transfers

VRConsole’s operations involve data moving between different countries:

User to VRChat/Patreon: If you are outside the United States (where VRChat and Patreon are based), when you log in or use VRConsole, your data is being sent to the U.S. (because VRChat’s servers are largely in the U.S., and Patreon is a U.S. company). This is a data transfer you initiate by using the service. Those companies have their own safeguards (for example, Standard Contractual Clauses for EU data, in Patreon’s case, or Privacy Shield legacy commitments, etc.).

Lexi’s Location: Lexi may be based in the United States (or another country). If you are an international user, any data that Lexi personally handles (like an email you send for support) will be accessed in that country. By contacting us or using VRConsole, you consent to the transfer of your information to the United States or any other jurisdiction where Lexi or the relevant third parties are located. We will of course handle it according to this Privacy Policy no matter where it is, but different countries have different data protection laws. Some may not be as strict as your home country. We will take steps to ensure appropriate safeguards (GDPR users: consider Standard Contractual Clauses in spirit, although as an individual developer, formal SCCs might not be signed, we still commit to respecting your privacy).

If you are in the EU/EEA, we rely on certain legal mechanisms for these transfers, such as: your consent (by using the software and voluntarily providing info, you consent to the transfer), and the fact that the transfer is necessary for the performance of a contract (the “contract” being your agreement to use VRConsole, which requires communicating with VRChat/Patreon). We understand the importance of proper safeguards and will monitor legal developments around international data transfers. If needed, we will update practices to remain compliant (like if new frameworks or rules come into effect).

# 10. Updates to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, legal requirements, or for other operational reasons. When we do, we will change the “Effective Date” at the top. If the changes are significant, we may provide a more prominent notice or notify users through other means (for example, a post on Patreon or a notification via VRConsole if feasible). We encourage you to review this Privacy Policy periodically for any changes.

If you continue to use VRConsole after a Privacy Policy update, it means you accept the revised policy. If you do not agree with any changes, you should stop using VRConsole and contact us if you have concerns. For any substantial changes that require your consent (like if we ever decided to collect more data or use it for new purposes), we will seek that consent.

# 11. Contact Information

If you have any questions, concerns, or requests regarding this Privacy Policy or your personal data, please do not hesitate to contact us. As a solo developer operation, we don’t have a fancy privacy department, but we take inquiries seriously and will do our best to respond promptly.

Contact Methods:

Email: You can email Lexi at the contact email provided on the official VRConsole documentation or Patreon page.

Patreon: If you are a patron, you can send a direct message to Lexi via Patreon’s messaging system.

When you contact us, please provide sufficient detail about your question or request, including any relevant account info (like your Patreon username or VRChat username) so we can locate any data if needed. For privacy-specific requests (like data access or deletion), we may need to verify your identity as mentioned in Section 7. We will only use the information you provide in a request to address and respond to that request.

Final Note: We respect your privacy and are committed to keeping your personal information safe and limited. This project thrives on trust – by being transparent about how VRConsole works with your data, we hope you feel comfortable using it. If anything in this policy is unclear, let us know. Thank you for using VRConsole and for taking the time to read through this Privacy Policy. Your VR adventures should be fun and worry-free, and we’re doing our best to ensure your data isn’t something you need to worry about while you explore VRChat with the help of VRConsole.