# Eternal Nexus — Privacy Policy

*Version 1.0 — November 22, 2026*

This policy explains what personal data is collected when you play Eternal Nexus, why it is collected, how long it is kept, who can access it, and what your rights are. It applies to players in all phases of the game (Alpha, Beta, early access and commercial release). It has been drafted in accordance with the General Data Protection Regulation ("GDPR"), the French "Informatique et Libertés" Act and the recommendations of the CNIL (the French data protection authority).

**Language.** This policy was written in French. This English version is provided for convenience. In case of difference, the French version prevails (see Article 22).

---

## Article 1 — Introduction and data controller

**1.1 The Studio.** Eternal Nexus is a massively multiplayer online role-playing game (MMORPG) developed and operated by SK-GAMES Studio, the public name of an independent studio currently made up of two members, located in France for indicative purposes (Paris).

**1.2 Data controller.** The data controller is the person or entity that decides the purposes and means of the processing of your data. SK-GAMES Studio is a public name. It is not registered as a company, has no SIRET number and has no declared registered office. The legal identity of the data controller is therefore distinct from this public name. It is held by the members of the Studio and may be communicated to the competent authorities, and to any person where the law requires it.

**1.3 Contact.** For any question regarding your personal data: skgames.studio.com@gmail.com. Account deletion requests: skgames.studio.com+delete@gmail.com.

**1.4 Data Protection Officer.** The Studio has not appointed a Data Protection Officer (DPO), as this is not mandatory in its current situation. Requests are handled by the Studio at the address above.

**1.5 Related documents.** This policy supplements the Eternal Nexus Terms of Use (the "Terms").

---

## Article 2 — Categories of data collected

The Studio only collects the data necessary for the operation and security of the game. The categories below correspond to features that are planned or actually present at the date of writing.

### 2.1 Account data
- email address;
- username (pseudonym);
- account identifier;
- password, only in the form of a secure hash (Article 5);
- version of the Terms accepted, and date and time of acceptance.

### 2.2 Connection and security data
- IP address;
- session tokens, stored as hashes (Article 6);
- connection dates and times;
- technical information related to the connection and the game client (for example, the game version);
- security logs.

### 2.3 Game data
- progression, characters, inventory, statistics;
- level and class;
- clan and role within the clan;
- rankings, medals and hours played.

### 2.4 In-game communications
- messages sent in the global chat, clan chat and private chat, with their technical information (date, sender, recipient).

### 2.5 Moderation data
- reports sent and received;
- sanctions (mutes, suspensions, bans) and their reasons;
- moderation history;
- information necessary to review incidents and appeals.

### 2.6 Support data
- messages sent to the Studio by email, on Discord or on GitHub;
- information necessary to handle requests.

**2.7 Data from third-party platforms.** When you buy or reserve the game through a third-party platform (Patreon, and in the future Steam or another platform), the Studio may receive certain information needed to manage your access, such as your name or username on the platform, your email address if the platform provides it, the tier or product purchased and the status of your access. The Studio does not receive or store your bank card numbers or payment data, which are processed by the platform.

**2.8 What the Studio does not collect.** The game client is not designed to collect information about your computer beyond what is described in this policy: it uses the information you enter in the game and the technical information needed for connection and security. The Studio does not ask you for sensitive data (health, opinions, origin, etc.).

**Integrity check (SoftDefender).** The anti-cheat tool SoftDefender checks the game files, at startup and during execution, to detect unauthorized modifications. It is designed to check only the game's files and is not designed to read your other files or other software.

**2.9 Sources of data.** Data comes from you (account, messages, reports), from the operation of the game (game data, logs, sanctions), or from third-party platforms (Article 2.7).

---

## Article 3 — Purposes of processing

Data is used for the following purposes, and only for these:

- **account creation and management;**
- **authentication:** verifying that you are the account holder;
- **game operation:** running the online world, characters and features;
- **saving progression;**
- **multiplayer features:** chat, clans, player-versus-player combat and authorized exchanges;
- **rankings;**
- **fraud prevention:** fraudulent purchases, prohibited resale of accounts or in-game items, account takeovers;
- **cheat detection:** prohibited software, game manipulation, bug exploitation;
- **server security:** protecting the infrastructure against attacks and intrusions, and managing incidents;
- **moderation:** handling reports, issuing sanctions and reviewing appeals;
- **support;**
- **compliance with legal obligations:** responding to lawful requests from authorities and keeping data that the law requires.

The Studio does not use your data for targeted advertising, does not sell it (Article 9) and does not take decisions based solely on automated processing that produce legal effects concerning you: a permanent ban is subject to human review.

---

## Article 4 — Legal bases

| Processing | Legal basis | Details |
|---|---|---|
| Account creation and management, authentication | Performance of a contract (Art. 6.1.b GDPR) | Without this data, the account cannot exist. |
| Game operation, saving progression, chat, clans, rankings | Performance of a contract | Part of the service requested. |
| Server security, security logs, IP addresses | Legitimate interest (Art. 6.1.f) | Protecting the game, servers and players. You may object (Article 15). |
| Cheat detection and fraud prevention | Legitimate interest | Fair play and protection of the community. |
| Moderation, reports, sanctions and appeals | Legitimate interest, and performance of a contract for enforcing the Terms | Enforcing the rules. |
| Support | Performance of a contract, or legitimate interest | Responding to requests. |
| Proof of acceptance of the Terms | Legitimate interest and legal obligation, depending on the case | Establishing proof of the commitment. |
| Response to authorities, retention obligations | Legal obligation (Art. 6.1.c) | Within what the law requires. |
| Optional communications (e.g. a newsletter), if any | Consent (Art. 6.1.a) | Can be withdrawn at any time. |
| Data of minors under 15, where processing relies on consent | Consent of the minor jointly with the holder of parental authority | See Article 18. |

Where processing relies on your consent, you may withdraw it at any time, without affecting the lawfulness of the processing carried out before the withdrawal.

---

## Article 5 — Password storage and security

**5.1 Principle.** Your password is never stored in plain text. The Studio only keeps a cryptographic hash, which does not allow the password to be recovered.

**5.2 Method.** The hash is calculated with the Argon2id algorithm, designed for password storage. Each password receives a unique random salt, and the algorithm's parameters are adapted to current security recommendations.

**5.3 No access.** No member of the Studio can view your password in plain text. If you forget it, it cannot be "retrieved": it is replaced by a new password that you choose, after verification of your identity.

**5.4 Your role.** Choose a long, unique password that you do not use elsewhere. The Studio never asks you for your password (Article 16).

**5.5 Protection of exchanges.** Exchanges between the game client and the servers are protected by encryption in transit.

**5.6 No absolute guarantee.** The Studio implements security measures appropriate to the risks, but no system is completely secure. The Studio cannot guarantee absolute security.

---

## Article 6 — Tokens and sessions

**6.1 Generation.** Session tokens are generated by a cryptographically secure random number generator.

**6.2 Storage.** As far as possible, the Studio does not store the directly usable value of a token, but its hash.

**6.3 Duration and revocation.** A token has a limited validity and is revoked upon logout, account deletion or password change.

**6.4 Access.** Technical access to tokens is strictly limited to authorized technical staff (Article 8). A token is never displayed publicly or communicated to a third party.

---

## Article 7 — IP addresses

**7.1 Nature.** An IP address is personal data, because it can indirectly identify a person.

**7.2 Why it is collected.** The Studio collects IP addresses when necessary for:
- the security of the game and of accounts;
- fraud prevention;
- the detection of suspicious activity (abnormal connections, attempts to take over an account);
- protecting the servers against attacks;
- incident management, including when an account is used to circumvent an ongoing sanction (Article 10.5 of the Terms).

The Studio does not use the IP address to automatically take collective measures against a household or a shared network: decisions affecting an account remain individualized and reviewed.

**7.3 Retention and access.** IP addresses are kept with the connection and security logs for six months (Article 13). Access is limited (Article 8). They are never public.

---

## Article 8 — Internal access and permissions

**8.1 Least privilege.** The Studio limits access to data to the people who need it for their duties. Authorized persons are bound by confidentiality.

**8.2 Planned permissions.**

| Data | Who can access it |
|---|---|
| IP address | The game's creator and expressly authorized technical staff |
| Email address | The game's creator and authorized support staff |
| Password | No plain-text access is possible |
| Tokens | Strictly authorized technical staff |
| Logs | Authorized technical staff |
| Progression | Staff, according to the functions required |
| Reports | Authorized moderation staff |

**8.3 Ordinary moderators** do not have access to sensitive data (IP address, email address, tokens, technical logs). They only access the information necessary to handle a report.

**8.4 Exceptional access.** Any exceptional access outside these permissions must be justified by a real need, limited to that need and, where possible, logged.

---

## Article 9 — No resale of data

**9.1 No sale.** SK-GAMES Studio does not sell players' personal data, does not rent it and does not transfer it for advertising or commercial purposes.

**9.2 Service providers.** Some providers may process data to provide their services to the Studio. Depending on the services actually used, this may include hosting providers, database providers, distribution platforms, payment providers, email services and support services. The Studio does not promise that no third party will ever access data; it undertakes to use providers only under the conditions of Article 12.

**9.3 Two situations to distinguish.**
- **Processors** process data on behalf of the Studio and on its instructions (for example, a hosting provider or an email service). A contract governs their involvement.
- **Platforms** such as Steam, Patreon, Discord or GitHub also process data for their own purposes, as separate controllers. Their own privacy policies apply, and the Studio does not control their processing.

---

## Article 10 — Public profile data

**10.1 What is visible, and to whom.**
- **Visible to everyone, including without an account:** only the game's global statistics (the overall number of connected or active players). They do not identify a player.
- **Visible in the game to other players:** the player's profile: username, hours played, medals, level, world ranking, character class, clan and role within the clan. Profiles are only available in the game.

**10.2 What is never public.** Your email address, IP address, password and login tokens are never made public, in the game or on the Official Spaces.

**10.3 Statistics linked to a pseudonym are personal data.** Even if you play under a pseudonym, the statistics attached to it may allow a person who knows you to recognize you. We recommend that you do not use your real name, or information that could identify you, as a username.

**10.4 Your choices.** You may ask to change your username, or object to the display of certain profile information (Article 15), where technically possible and compatible with the operation of the game.

---

## Article 11 — Disclosure to authorities

Your data may be disclosed to the competent authorities (judicial, investigative, administrative) where the law permits or requires it, in particular in response to a requisition, a court decision or a validly served legal procedure. The Studio checks that the request is valid and only discloses the data that is necessary and requested. Where the law or the authority allows it, the Studio informs you.

---

## Article 12 — Service providers and external services

**12.1 Principle.** The Studio only states that a service is used when that use is confirmed.

| Service | Use | Role regarding your data | Status |
|---|---|---|---|
| Studio's local server | Hosting of the game servers and database, on a hard drive of a server located in France, operated by the Studio | The Studio is solely responsible for this hosting | Used |
| GitHub | Official repository, tracking of technical issues | Platform, controller for its own purposes | Used |
| Discord | Official community, announcements and exchanges | Platform, controller for its own purposes | Used (server to be created) |
| Patreon | Alpha access, payment and management of subscriptions or contributions | Platform and payment provider, controller for its own purposes | Used |
| Steam | Distribution at official release | Platform, controller for its own purposes | Considered, not used to date |
| Studio mailbox (Gmail address) | Receiving requests and sending account-related messages | Email provider | Used for contacts |

**12.2 No other provider.** At the date of writing, the Studio does not use any other hosting provider, analytics tool, support tool or payment provider. This list will be updated as soon as a service is added.

**12.3 Safeguards.** Where a provider acts as a processor, the Studio ensures that a contract compliant with Article 28 GDPR governs its obligations. For platforms acting on their own behalf (Discord, GitHub, Patreon, Steam), their privacy policy applies to their own processing. We invite you to read it.

**12.4 Locally hosted data.** As the game data is hosted on a local server operated by the Studio, the Studio takes appropriate technical and organizational measures to protect it.

---

## Article 13 — Retention periods

**13.1 Principle.** The Studio keeps data only for as long as necessary for its purpose. After that, data is deleted or anonymized.

**13.2 Retention table.**

| Category | Retention period |
|---|---|
| Connection and security logs (including IP address) | 6 months from recording |
| Account data (email, username, identifier) | For the duration of the account; deletion or anonymization after closure, subject to the periods below |
| Password hash, token hashes | For the duration of the account; tokens deleted at expiry or revocation |
| Game data (progression, characters, inventory, statistics) | For the duration of the account; deleted on closure, except aggregated and anonymous statistics |
| Proof of acceptance of the Terms (date, version, identifier) | For the duration of the account, then 5 years after closure, to establish or defend rights |
| Chat messages | 6 months |
| Reports | 12 months after the report has been handled |
| Moderation files and sanctions | Duration of the sanction, then 12 months; for a permanent ban, 3 years from the sanction, to enforce it and handle appeals |
| Messages sent to support | 12 months after the request is closed |
| Data necessary for a legal obligation | The period required by law |
| Data necessary for managing a dispute | Until the end of the proceedings, then for the applicable limitation period |

**13.3 Six months for logs.** The CNIL recommends keeping logs for six months to one year (deliberation no. 2021-122 of October 14, 2021). The Studio chose six months to detect suspicious activity that only appears over time and to handle appeals. This period is reviewed regularly and reduced if no longer necessary.

---

## Article 14 — Deletion of accounts and data

**14.1 How to request deletion.** Email skgames.studio.com+delete@gmail.com from the email address associated with your account. The Studio may ask for reasonable proof of identity, never your password.

**14.2 Deadline.** The Studio responds within one (1) month of receipt. This may be extended by two months for a complex request, in which case you are informed.

**14.3 Three notions to distinguish.**
- **Account deletion:** you lose access to the account and its progression.
- **Erasure of personal data:** the Studio deletes or anonymizes the data that can lawfully be erased, in particular your email address, username and game data.
- **Data kept despite deletion:** certain data may be kept where necessary to comply with a legal obligation, ensure the security of the game, prevent fraud or manage a dispute. It is limited to what is strictly necessary (for example, proof of acceptance of the Terms or the record of a sanction) and deleted at the end of the periods in Article 13.

**14.4 What deletion does not do.** Deleting the game account does not delete your data held by third-party platforms (Patreon, Discord, GitHub, Steam) and does not automatically end a subscription or recurring payment. You must do this with each platform.

**14.5 Confirmation.** Once deletion is carried out, the Studio confirms it by email.

---

## Article 15 — Players' rights

**15.1 Your rights.** Under the GDPR and the French Informatique et Libertés Act, you have the following rights:
- **access:** to know whether the Studio processes your data and obtain a copy;
- **rectification:** to correct inaccurate or incomplete data;
- **erasure:** to request deletion of your data, in the cases provided by law;
- **restriction:** to request that processing be suspended in certain cases;
- **objection:** to object, on grounds relating to your particular situation, to processing based on legitimate interest;
- **portability:** to receive your data in a structured, commonly used format, where processing relies on contract or consent and is automated;
- **withdrawal of consent** at any time, where processing relies on it;
- **instructions** on what happens to your data after your death;
- **complaint** to a supervisory authority (Article 21).

**15.2 How to exercise them.** Write to skgames.studio.com@gmail.com, stating the right you exercise, from the email address associated with your account. For account deletion, use skgames.studio.com+delete@gmail.com (Article 14).

**15.3 Identity verification.** The Studio reasonably verifies the identity of the requester, for example by checking that the request comes from the account's email address. The Studio never asks for your password or tokens.

**15.4 Response time.** One (1) month from receipt, extendable by two months if the request is complex or numerous. Exercising your rights is free, except for manifestly unfounded or excessive requests, for which the Studio may charge a reasonable fee or refuse to act.

**15.5 Limits.** Some rights may be limited where the law provides: for example, security or moderation data necessary to ensure the security of the game or to defend rights may be kept despite an erasure request (Article 14.3). The Studio then explains the reasons for the refusal.

---

## Article 16 — Official communications and security

**16.1 Official channels.** The Studio's official communications are published on the official GitHub repository (https://github.com/SK-GAMEstudio/Eternal-Nexus), on the official Discord server (link to be added later) and by email from skgames.studio.com@gmail.com.

**16.2 What the Studio never asks.** The Studio never asks for players' passwords or tokens, whatever the reason given.

**16.3 Vigilance.** Beware of executable files and unofficial links. The Studio never sends executables by email or private message. If you receive a suspicious message claiming to be from the Studio, do not click the links, do not open the files, and report it to skgames.studio.com@gmail.com.

**16.4 Security incident.** In the event of a personal data breach likely to result in a risk to your rights, the Studio handles it without delay, documents it and informs the CNIL and the persons concerned in the cases and within the time limits provided by law.

---

## Article 17 — Communications between players

**17.1 What other players see.** Other players see the profile information in Article 10.1. They never see your email address, IP address, password or tokens.

**17.2 Communication features.**
- Global chat messages are visible to the players who have access to it.
- Clan chat messages are visible to the clan's members.
- Private chat messages are visible only to the recipients.

What you write can be copied, captured or reported by another player. Do not share personal information (name, address, phone number, social networks) with people you do not know. The Studio is not responsible for information you choose to share with other players.

**17.3 Moderation and privacy.** The Studio does not generally monitor private conversations. A message may however be examined when it is reported, when security requires it or when the law requires it, only by authorized moderation staff and to the extent necessary. Rules of conduct are in Article 14 of the Terms. Doxxing is prohibited and sanctioned.

---

## Article 18 — Minors

**18.1 Framework.** Article 45 of the French Informatique et Libertés Act sets at fifteen (15) the age from which a minor may consent alone to the processing of their data, where processing relies on consent, for online services. Below that age, consent must be given jointly by the minor and the holder of parental authority.

**18.2 No automatic exclusion.** This rule only applies to processing that relies on consent. Processing necessary for the game relies on contract or legitimate interest and is governed by Article 23 of the Terms, which requires the agreement of the legal representative for minor players.

**18.3 Minimum age.** The Game is not intended for children under thirteen (13). Players must be at least 13 years old. If the Studio learns that an Account belongs to a child under 13, it may delete it and the associated data.

**18.4 Enhanced protection.** The Studio does not carry out targeted advertising, does not sell data and does not build commercial profiles of minors. It limits its collection to what is necessary.

**18.5 Rights of minors and parents.** A minor may exercise their rights, including requesting deletion of their account, and the holder of parental authority may exercise them for them (Article 15). If the Studio learns that it has collected data from a child under 15 without the agreement required for processing based on consent, it deletes that data, unless a legal representative confirms their agreement.

---

## Article 19 — International transfers

**19.1 Game data.** At the date of writing, the game's data (accounts, progression, logs) is hosted on a local server in France, operated by the Studio. It is not transferred outside the European Union by the Studio.

**19.2 Third-party platforms.** The platforms that the Studio uses or plans to use (Discord, GitHub, Patreon, Steam, Gmail mailbox) are international organizations, some established outside the European Union, notably in the United States, and may transfer or process data there. These transfers are carried out by them, for their own purposes or as a provider, and are subject to their own privacy policies. They rely in principle on a mechanism provided by the GDPR: an adequacy decision (for example, the EU–US Data Privacy Framework for certified organizations), standard contractual clauses or another appropriate safeguard.

**19.3 New providers.** Before using a provider that would process your data outside the European Union, the Studio verifies the applicable safeguard and updates this policy.

---

## Article 20 — Changes to the policy

**20.1 Changes.** The Studio may modify this policy, in particular when the game evolves, a new provider is used or a rule changes. The date and version number appear at the bottom of the document.

**20.2 Information.** For a significant change (new purpose, new category of data, new provider, change of retention period), the Studio informs you by email and by an announcement on the official channels, before the change takes effect and within a reasonable time, unless legally required otherwise or in case of a security emergency.

**20.3 Consent.** Where the change requires your consent, it is requested again. Silence does not constitute consent.

**20.4 History.** Previous versions can be consulted on request, or on the official repository.

---

## Article 21 — Contact and complaints

**21.1 Contact the Studio.** Email: skgames.studio.com@gmail.com. Discord: link to be added later. Repository: https://github.com/SK-GAMEstudio/Eternal-Nexus.

**21.2 Complaint to a supervisory authority.** If you consider that the processing of your data does not comply with the rules, you may lodge a complaint with the **CNIL** (www.cnil.fr), the French authority competent for the Studio. Players in the EU/EEA may also complain to the data protection authority of their own country. We encourage you to contact the Studio first so that we can try to solve the issue directly, but this is not mandatory.

---

## Article 22 — Players outside France and the EU

**22.1 Same rules for all players.** The Studio is established in France. The GDPR therefore applies to the processing of the data of its players, wherever they live. The Studio handles requests from all players in the same way, under this policy.

**22.2 Data stored in France.** If you play from outside the EU, your game data is sent to and stored on a server in France, and is processed under French and EU law. By playing, you acknowledge this transfer, which is necessary to provide the Game.

**22.3 Local laws.** The Studio does not sell or share your personal data (Article 9). If a mandatory law of your country of residence gives you additional rights that cannot be waived and that apply to the Studio, you may write to the contact addresses above and the Studio will examine your request in good faith. Nothing in this policy means that the Studio submits to the law of a country other than the ones it is subject to.

**22.4 Age.** The age from which a minor can consent alone differs between countries (in the EU, between 13 and 16 depending on the country; 15 in France). Where this policy's rules for minors (Article 18) do not match the law that applies to you, the Studio applies the mandatory rule to the extent legally required.

**22.5 Language.** This policy was written in French, which is the authoritative language. This English version is provided for convenience. In case of difference, the French version prevails, except where a mandatory rule requires otherwise.

---

*Version 1.0, November 22, 2026.*
