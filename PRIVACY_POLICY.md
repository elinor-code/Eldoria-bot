# Privacy Policy — Eldoria

**Effective Date:** July 24, 2026
**Last Revised:** July 24, 2026

---

## 1. Introduction

**1.1** This Privacy Policy ("Policy") describes how Eldoria Studio ("Developer," "we," "us," or "our") collects, uses, stores, shares, and protects personal information when you ("User," "you," or "your") interact with the Eldoria Discord bot ("Service," "Bot," or "Eldoria") on the Discord platform.

**1.2** This Policy should be read in conjunction with the Eldoria Terms of Service ("Agreement"). By using the Service, you acknowledge that you have read and understood this Policy.

**1.3** The Developer is committed to protecting your privacy and handling your data in an open, transparent, and responsible manner. This Policy explains your rights and choices regarding your personal information and how we safeguard it.

**1.4** If you do not agree with the practices described in this Policy, you should not use the Service.

---

## 2. Scope of This Policy

**2.1** This Policy applies exclusively to data collected and processed by the Eldoria Bot through its own systems. It does not apply to:

   (a) Data collected by Discord, Inc. through its platform (governed by Discord's own [Privacy Policy](https://discord.com/privacy));
   (b) Data collected by third-party websites, services, or bots linked to or from the Service;
   (c) Data collected offline or through non-Discord channels, unless explicitly referenced herein.

**2.2** The Developer does not control and is not responsible for the data collection practices of Discord or any third-party service. We encourage you to review Discord's Privacy Policy to understand how Discord handles your data.

---

## 3. Data Controller

**3.1** For the purposes of applicable data protection legislation (including the EU General Data Protection Regulation ("GDPR"), the UK GDPR, the California Consumer Privacy Act ("CCPA"), and similar laws), the Developer, Eldoria Studio, is the data controller responsible for the personal data described in this Policy.

**3.2** Data protection inquiries and exercise of rights may be directed through the contact channels specified in Section 20 of this Policy.

---

## 4. Information We Collect

The Service collects several categories of information. The nature and extent of data collected depends on your interaction with the Bot.

### 4.1 Account Identification Data

| Data Element | Description | Source | Required |
|---|---|---|---|
| Discord User ID | Your unique numerical Discord identifier | Automatically from Discord API | Yes |
| Discord Guild ID | Identifier(s) for servers where you use the Bot | Automatically from Discord API | Yes |
| Display Name | Your Discord display name at time of profile creation | Automatically from Discord API | Yes |

**Purpose:** To uniquely identify your game profile, associate your Game Progress with your Discord account, and provide the Service across multiple servers.

### 4.2 Game Profile Data

| Data Element | Description | Required |
|---|---|---|
| Selected Race | Your chosen in-game race | Yes (at setup) |
| Kingdom Name | Name of your in-game kingdom | Yes (at setup) |
| Kingdom Level | Your kingdom's current level | Automatic |
| Kingdom Experience | Experience points accumulated | Automatic |
| Prestige Level | Your prestige rank | Automatic |
| Prestige Title | Title associated with your prestige level | Automatic |
| Credit Score | In-game credit rating for loan eligibility | Automatic |
| Setup Completion Status | Whether initial setup has been completed | Automatic |

### 4.3 Resource and Economy Data

| Data Element | Description |
|---|---|
| In-Game Currencies | Balances for Gold, Crystal, Iron, Food, Wood, Mana, and Dark Essence |
| Bank and Vault Balances | Gold deposited in the in-game bank or vault |
| Bank / Vault Status | Lock state, interest timestamps, and access flags |
| Loan Records | Principal amount, outstanding balance, collateral, status, and repayment history |

**Purpose:** To operate the in-game economy, track resource flows, prevent fraud, and maintain economy integrity.

### 4.4 Transaction Ledger

| Data Element | Description |
|---|---|
| Transaction ID | Unique system-generated identifier for each transaction |
| Transaction Type | Category of transaction (e.g., daily claim, market purchase, arena reward) |
| Resource | Which resource was affected |
| Amount | Quantity gained or lost |
| Balance After | Account balance snapshot following the transaction |
| Additional Context | Optional contextual information associated with the transaction |
| Timestamp | Date and time of the transaction |

**Purpose:** To maintain a verifiable audit trail of all economic activity, support anti-cheat investigations, enable data restoration operations, and ensure economy integrity.

### 4.5 Kingdom Infrastructure Data

| Data Element | Description |
|---|---|
| Building Types and Levels | Types of buildings in your kingdom and their current upgrade levels |
| Army Composition | Composition and size of your military forces |
| Last Collection Timestamp | When you last collected taxes and production |

### 4.6 Character Data

**Heroes:**

| Data Element | Description |
|---|---|
| Hero Name | Name given to the hero |
| Hero Race and Class | Race and class designation of the hero |
| Hero Level & XP | Current level and experience points |
| Hero Stats | Combat statistics (power, defense, speed, luck) |
| Hero Rarity | Rarity tier classification |
| Equipped Item | Reference to currently equipped item |

**Pets:**

| Data Element | Description |
|---|---|
| Pet Name | Name given to the pet |
| Species and Rarity | Species type and rarity tier classification |
| Level & XP | Current level and experience points |
| Loyalty | Loyalty score |
| Combat Bonuses | Attack and defense bonus values |
| Skill | Pet's active skill |
| Active Status | Whether the pet is currently active |

### 4.7 Skill and Progression Data

| Data Element | Description |
|---|---|
| Skill Names | Skills you have engaged with |
| Skill Levels | Current level for each skill |
| Skill XP | Experience points for each skill |
| Skill Metadata | Additional skill-specific information |

### 4.8 Social and Competitive Data

| Data Element | Description |
|---|---|
| Alliance Membership | Alliance you belong to, your role, and donation history |
| Alliance Creation | Whether you created an alliance (name, tag, level, experience) |
| Arena Matches | Match history including opponents, power levels, resource deltas, rating changes, and outcomes |
| Auction Activity | Items listed for sale, items bid on, prices, and transaction status |
| Leaderboard Data | Derived from Game Progress (no additional data collected) |

### 4.9 Notification Preferences

| Data Element | Description | Default |
|---|---|---|
| Daily Reminder | Opt-in/out for daily activity reminders | On |
| War Alerts | Opt-in/out for alliance war notifications | On |
| Market Alerts | Opt-in/out for market price change alerts | Off |
| World Boss Alerts | Opt-in/out for world boss event notifications | On |

**Purpose:** To deliver notifications you have chosen to receive. These preferences are stored and processed solely to respect your notification choices.

### 4.10 Operational and Anti-Cheat Data

| Data Element | Description |
|---|---|
| Cooldown Records | Active cooldown timers and expiration timestamps per action |
| Daily Claim Records | Record of daily reward claims and streak counters |
| Command History | Record of commands executed (for anti-cheat analysis and system debugging) |
| Activity Timestamps | Last active time and session-related timestamps |
| Account Markers | Internal status fields used for account management and data removal requests |

**Purpose:** To enforce game rules, prevent abuse, detect cheating and exploitation, support debugging, and facilitate account management.

### 4.11 Global System Data

| Data Element | Description |
|---|---|
| Game Configuration | Global game settings, balance parameters, and feature flags |
| Inflation Snapshots | Periodic records of economic inflation rates |

**Note:** Global system data is not associated with individual users and is used solely for economy management.

---

## 5. How We Use Your Information

**5.1 Service Provision.** Your data is used to provide, operate, and deliver the core functionality of the Service, including but not limited to:

   (a) Creating and maintaining your Player Profile;
   (b) Processing game commands and interactions;
   (c) Managing your kingdom, economy, heroes, pets, alliances, and all Game Progress;
   (d) Enabling player-versus-player matchmaking and competitive rankings;
   (e) Delivering notifications you have opted into.

**5.2 Anti-Cheat and Integrity.** Your data is used to detect, prevent, and investigate cheating, exploitation, fraud, and abuse of the Service, including:

   (a) Monitoring transaction patterns for anomalous behavior;
   (b) Enforcing cooldowns and rate limits;
   (c) Investigating reports of exploitative activity;
   (d) Supporting data restoration operations.

**5.3 Service Improvement.** Your data may be used in aggregated or anonymized form to:

   (a) Analyze gameplay trends and player behavior;
   (b) Identify balance issues and improve game mechanics;
   (c) Optimize system performance and reliability;
   (d) Develop new features and content.

**5.4 Legal Compliance.** Your data may be processed to comply with applicable laws, regulations, legal processes, or enforceable governmental requests.

**5.5 Agreement Enforcement.** Your data may be used to enforce the Terms of Service, investigate violations, and protect the rights and safety of the Developer, Users, and the public.

---

## 6. How We Store Your Information

**6.1 Storage Infrastructure.** Your data is stored on secure, industry-standard database infrastructure hosted by the Developer's infrastructure providers. The Service utilizes secure caching technologies for session management and performance optimization.

**6.2 Geographic Location.** Your data is stored in data centers selected by the Developer's infrastructure providers. Data may be stored in jurisdictions other than your country of residence. By using the Service, you consent to the transfer and storage of your data in these locations.

**6.3 Encryption.** Data is protected using industry-standard encryption in transit and encryption at rest. Data access is governed by strict access controls limiting access to authorized personnel only.

**6.4 Backups.** The Developer maintains regular backups to support disaster recovery and data integrity. Backups are retained only for the period reasonably necessary for disaster recovery and business continuity, and are subject to the same access controls as primary data stores.

**6.5 Access Controls.** Access to production data is restricted to authorized personnel of the Developer who require such access for legitimate operational purposes. Access is governed by the principle of least privilege.

---

## 7. Data Retention

**7.1 Active Accounts.** Your data is retained for as long as your Player Profile remains active — that is, for as long as you continue to use the Service or until you request data deletion.

**7.2 Inactive Accounts.** Player Profiles that have had no recorded activity for one hundred eighty (180) consecutive days may be flagged as inactive. Inactive profiles may be archived or, after an additional one hundred eighty (180) days of continued inactivity, permanently deleted. The Developer will make reasonable efforts to notify you before permanent deletion, though prior notice is not guaranteed.

**7.3 Deleted Accounts.** When you request deletion of your account, or when an account is terminated, your personal data is permanently and irreversibly deleted within thirty (30) days, except:

   (a) Data required to be retained under applicable law may be retained for the period mandated by such law;
   (b) Anonymized or aggregated data that can no longer be attributed to you may be retained indefinitely for analytics purposes;
   (c) Transaction records required for economic integrity audits may be retained in anonymized form.

**7.4 Transaction Logs.** Transaction records are retained for the lifetime of the account to support anti-cheat investigations, audit trails, and data restoration operations. Upon account deletion, transaction records are deleted along with other account data, unless retention is required by law.

---

## 8. Data Sharing and Disclosure

**8.1 No Sale of Personal Data.** The Developer does **not** sell, rent, trade, or otherwise distribute your personal data to third parties for their marketing, advertising, or commercial purposes.

**8.2 No Sharing for Advertising.** Your data is not shared with, sold to, or made available to data brokers, advertising networks, analytics companies, or any entity for the purpose of targeted advertising or profiling.

**8.3 Service Providers.** The Developer may engage trusted third-party service providers who process data on behalf of the Developer for limited operational purposes, such as:

   (a) Cloud infrastructure and hosting providers (database and application hosting);
   (b) Logging and monitoring services (for system health and error diagnosis);
   (c) Payment processors (if and when Premium Features are offered).

All service providers are bound by contractual obligations to protect your data to standards no less protective than this Policy. The Developer performs reasonable due diligence on service providers before engagement.

**8.4 Legal Requirements.** The Developer may disclose your personal data if required to do so by law, or in good faith belief that such action is necessary to:

   (a) Comply with a legal obligation, subpoena, court order, or government request;
   (b) Protect and defend the rights, property, or safety of the Developer, its Users, or the public;
   (c) Enforce the Terms of Service;
   (d) Detect or prevent fraud, security vulnerabilities, or technical issues.

**8.5 Business Transfers.** In the event of a merger, acquisition, reorganization, bankruptcy, dissolution, or sale of all or a portion of the Developer's assets, your data may be transferred as part of that transaction. In such an event, the Developer will make reasonable efforts to notify you before your data is transferred and becomes subject to a different privacy policy.

**8.6 Discord.** Your use of the Service involves data exchange with Discord's platform. The Developer does not control Discord's data practices. Discord's collection and use of your data is governed by [Discord's Privacy Policy](https://discord.com/privacy). The Developer encourages you to review that policy.

**8.7 Aggregated and Anonymized Data.** The Developer may create aggregated, anonymized, or de-identified datasets derived from User data. Such data cannot reasonably be used to identify you and is not subject to the restrictions in this Policy. The Developer may use and share aggregated data for any lawful purpose, including analytics, research, public reporting, and Service improvement.

---

## 9. Data Security

**9.1 Technical Measures.** The Developer implements industry-standard technical safeguards to protect your data, including but not limited to:

   (a) **Encryption in Transit:** Industry-standard encryption for all data transmitted between your client, Discord's infrastructure, and the Service's servers;
   (b) **Encryption at Rest:** Data stored in our systems is encrypted at rest;
   (c) **Access Controls:** Strict access controls limiting data access to authorized personnel;
   (d) **Authentication:** Secure authentication mechanisms for all administrative and operational access;
   (e) **Monitoring:** Automated monitoring and alerting for unauthorized access attempts, anomalies, and security events;
   (f) **Infrastructure Hardening:** Systems follow security best practices and are regularly updated with security patches.

**9.2 Organizational Measures.** The Developer implements appropriate organizational measures, including:

   (a) Principle of least privilege for all data access;
   (b) Regular review of access permissions;
   (c) Security awareness and responsible handling practices;
   (d) Incident response procedures for data breach scenarios.

**9.3 No Absolute Security.** While the Developer strives to use commercially reasonable means to protect your data, no method of electronic transmission, storage, or processing is 100% secure. The Developer cannot guarantee the absolute security of your data and is not liable for unauthorized access that occurs despite reasonable safeguards, except to the extent required by applicable law.

**9.4 Breach Notification.** In the event of a data breach that is likely to result in a risk to your rights and freedoms, the Developer will notify affected Users and, where required, relevant supervisory authorities within the timeframes mandated by applicable law.

---

## 10. Your Rights and Choices

**10.1 Overview.** Depending on your jurisdiction, you may have certain rights regarding your personal data. The Developer respects these rights and will fulfill verified requests within reasonable timeframes.

**10.2 Rights Under GDPR (EU/EEA/UK Users).** If you are located in the European Economic Area, the United Kingdom, or a jurisdiction with similar data protection laws, you have the following rights:

   **(a) Right of Access (Article 15 GDPR):** You have the right to request a copy of the personal data the Developer holds about you, along with information about how it is processed.

   **(b) Right to Rectification (Article 16 GDPR):** You have the right to request correction of inaccurate personal data or completion of incomplete data.

   **(c) Right to Erasure / Right to Be Forgotten (Article 17 GDPR):** You have the right to request deletion of your personal data, subject to exceptions where the Developer has legitimate grounds for retention (e.g., compliance with legal obligations, defense of legal claims).

   **(d) Right to Restriction of Processing (Article 18 GDPR):** You have the right to request restriction of processing of your personal data in certain circumstances, such as when you contest the accuracy of the data or object to processing.

   **(e) Right to Data Portability (Article 20 GDPR):** You have the right to receive your personal data in a structured, commonly used, and machine-readable format, and to request that the data be transmitted to another controller where technically feasible.

   **(f) Right to Object (Article 21 GDPR):** You have the right to object to processing of your personal data based on legitimate interests. The Developer will cease processing unless it demonstrates compelling legitimate grounds that override your interests.

   **(g) Right to Withdraw Consent:** Where processing is based on your consent, you have the right to withdraw consent at any time, without affecting the lawfulness of processing prior to withdrawal.

   **(h) Right to Lodge a Complaint:** You have the right to lodge a complaint with a supervisory authority in your jurisdiction if you believe your data protection rights have been infringed.

**10.3 Rights Under CCPA/CPRA (California Residents).** If you are a California resident, the California Consumer Privacy Act and the California Privacy Rights Act provide you with the following rights:

   **(a) Right to Know:** You have the right to request disclosure of the categories and specific pieces of personal information collected about you, the purposes of collection, the categories of sources, and the categories of third parties with whom the information is shared.

   **(b) Right to Delete:** You have the right to request deletion of your personal information, subject to certain exceptions.

   **(c) Right to Opt Out of Sale:** The Developer does **not** sell personal information. Accordingly, no opt-out mechanism is required. If this changes in the future, a clear opt-out mechanism will be provided.

   **(d) Right to Non-Discrimination:** The Developer will not discriminate against you for exercising your privacy rights, including by denying service, charging different prices, or providing a different level of service.

**10.4 Other Jurisdictions.** The Developer aims to honor privacy rights for all Users, regardless of jurisdiction. If you reside in a jurisdiction with data protection rights not explicitly addressed above, please contact the Developer, and we will make reasonable efforts to accommodate your request in compliance with applicable law.

**10.5 Exercising Your Rights.** To exercise any of the rights described above, you may contact the Developer through the channels specified in Section 20. The Developer may require you to verify your identity before processing your request to prevent unauthorized access to your data.

**10.6 Response Timeframe.** The Developer will acknowledge your request within five (5) business days and will endeavor to substantively respond within thirty (30) calendar days. If additional time is required (e.g., due to the complexity or volume of the request), the Developer will notify you of the extension within the initial thirty-day period.

**10.7 Notification Preferences.** You may update your notification preferences at any time by using the `/notifications` command within the Service. Changes take effect immediately.

---

## 11. Children's Privacy

**11.1** The Service is not directed to children under the age of thirteen (13), or under the minimum age required to use Discord in your jurisdiction, whichever is greater.

**11.2** The Service does not knowingly collect personal information from children. If the Developer becomes aware that personal information has been collected from a child without appropriate parental consent, the Developer will take prompt steps to delete such information.

**11.3** If you are a parent or guardian and believe your child has provided personal information through the Service without your consent, please contact the Developer immediately so that the information can be deleted.

**11.4** Compliance with the Children's Online Privacy Protection Act ("COPPA") and equivalent international legislation is a priority for the Developer.

---

## 12. Cookies and Tracking

**12.1** The Service, being a Discord bot accessed through Discord's client interface, does not use cookies, pixel tags, web beacons, or similar tracking technologies directly.

**12.2** Discord's platform and any third-party services linked to the Service may use cookies and tracking technologies. The Developer does not control these technologies. Please refer to Discord's Privacy Policy and the respective third-party policies for information about their tracking practices.

---

## 13. Automated Decision-Making

**13.1** The Service employs automated systems for gameplay mechanics, matchmaking, economy management, and anti-cheat enforcement. These systems process your data to:

   (a) Calculate combat outcomes and resource production based on game rules;
   (b) Match players for competitive interactions based on ranking and power levels;
   (c) Detect and flag potentially exploitative or fraudulent behavior patterns;
   (d) Enforce cooldowns, rate limits, and economic caps.

**13.2** Anti-cheat decisions may result in automated restrictions on your account (e.g., transaction limits, cooldown extensions, or flagging for review). You have the right to contest any automated decision through the appeal process described in the Terms of Service (Section 25).

**13.3** No fully automated decision that produces legal effects or similarly significantly affects you is made without human review when a reasonable request for review is made.

---

## 14. Data Minimization

**14.1** The Developer adheres to the principle of data minimization — collecting only the data that is necessary for the purposes described in this Policy. Every data element collected by the Service serves a specific and documented purpose related to game functionality, security, or compliance.

**14.2** The Developer does not collect:

   (a) Real-world names, physical addresses, or postal addresses;
   (b) Email addresses (unless voluntarily provided for support);
   (c) Phone numbers;
   (d) Government-issued identification numbers;
   (e) Financial account information (bank accounts, credit cards);
   (f) Biometric data;
   (g) Precise geolocation data;
   (h) Health, racial, ethnic, or political data.

**14.3** The primary personal data element collected is your Discord User ID — a numerical identifier that, while not inherently revealing your real-world identity, may be used by Discord or other services to identify you.

---

## 15. Third-Party Links and Services

**15.1** The Service may contain references to, integrations with, or links to third-party websites, services, or content (including Discord support server links, developer documentation, or partner resources).

**15.2** The Developer does not control and is not responsible for the privacy practices, content, or security of any third-party service. The inclusion of any link or integration does not imply endorsement by the Developer.

**15.3** You are encouraged to review the privacy policies of any third-party service before providing them with personal information.

---

## 16. International Data Transfers

**16.1** Your data may be transferred to and processed in countries or jurisdictions outside of your country of residence. These countries may have data protection laws that differ from the laws of your jurisdiction.

**16.2** By using the Service, you consent to the transfer, storage, and processing of your data in jurisdictions where the Developer, its service providers, or their infrastructure providers operate.

**16.3** Where required by applicable law (e.g., EU Standard Contractual Clauses or equivalent transfer mechanisms), the Developer will ensure that appropriate safeguards are in place to protect your data during international transfers.

---

## 17. Data Processing Legal Bases (GDPR)

**17.1** For Users in the European Economic Area and the United Kingdom, the Developer processes personal data under the following legal bases:

| Legal Basis | Processing Activity |
|---|---|
| **Performance of Contract** (Art. 6(1)(b)) | Providing the Service, creating and maintaining Player Profiles, processing game commands, managing Economy and Game Progress |
| **Legitimate Interest** (Art. 6(1)(f)) | Anti-cheat monitoring, fraud detection, service improvement through aggregated analytics, security monitoring, enforcing Terms of Service |
| **Legal Obligation** (Art. 6(1)(c)) | Complying with applicable laws, responding to valid legal process, data retention as required by law |
| **Consent** (Art. 6(1)(a)) | Delivering optional notifications (daily reminders, war alerts, market alerts, world boss alerts) |

**17.2** You may withdraw consent for notification-related processing at any time through the `/notifications` command, without affecting the lawfulness of processing carried out prior to withdrawal.

---

## 18. Do Not Track (DNT)

**18.1** The Service does not respond to "Do Not Track" browser signals, as it does not employ cross-site tracking technologies. Your in-service activity is used solely for game functionality, anti-cheat enforcement, and Service improvement as described in this Policy.

---

## 19. Changes to This Policy

**19.1** The Developer reserves the right to update or modify this Policy at any time to reflect changes in our practices, technologies, legal requirements, or other factors.

**19.2** Material changes to this Policy will be communicated through one or more of the following methods:

   (a) Announcement in the official Eldoria Discord server;
   (b) In-bot notification upon your next interaction;
   (c) A prominent notice on the Service (if applicable web presence exists).

**19.3** The "Last Revised" date at the top of this document will be updated to reflect the date of the most recent changes.

**19.4** Your continued use of the Service after the effective date of a revised Policy constitutes your acceptance of the changes. If you do not agree with the revised Policy, you should cease use of the Service and request data deletion.

**19.5** Where required by applicable law, the Developer will obtain your affirmative consent before applying material changes to data processing practices.

---

## 20. Contact Information

**20.1** For questions, concerns, requests, or complaints regarding this Policy or the Developer's data practices, you may contact the Developer through the following channels:

   - **Service:** Eldoria Discord Bot (botzenki)
   - **Developer:** Eldoria Studio
   - **Primary Contact:** Official Eldoria Discord server — support ticket system
   - **Direct Contact:** Discord (bot owner / administrator)

**20.2** Data protection requests (access, rectification, deletion, portability, objection) should be directed through the channels above. Please clearly identify yourself by providing your Discord User ID and describing your request.

**20.3** The Developer will respond to verified data protection requests within the timeframes specified in Section 10.6.

**20.4** If you are in the European Economic Area or the United Kingdom and are not satisfied with the Developer's response to your data protection inquiry, you have the right to lodge a complaint with your local supervisory authority for data protection.

---

## 21. Definitions (Cross-Reference)

For the definitions of terms used in this Policy (including "User," "Developer," "Service," "Game Progress," "Game Resources," "Virtual Currency," "Exploit," and others), please refer to Section 2 of the Eldoria Terms of Service, which is incorporated herein by reference.

---

*© 2026 Eldoria Studio. All rights reserved.*
