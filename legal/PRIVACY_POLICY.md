# Privacy Policy

**Effective date:** May 03, 2026

## Who We Are and What This Policy Covers

This Privacy Policy explains how **Teefs** ("Teefs", "we", "us", or "our") collects, uses, shares, and protects information in connection with the Teefs website (the "**Website**") and the study tools, dashboards, editor tools, APIs, AI features, and other functionality we make available (collectively, the "**Services**"). Teefs is a free, AI-assisted study companion designed to help dental students prepare for the **Integrated National Board Dental Examination (INBDE)** exam.

This Policy applies to your use of the Website and the Services and is incorporated into our Terms of Service. Capitalized terms not defined here have the meanings given to them in the Terms of Service.

> **Reminder.** Teefs is for **educational and study purposes only**. The Services do not constitute medical, dental, or other professional advice, diagnosis, or treatment, and must not be used for clinical decision-making. Always consult a qualified healthcare professional.

## Creative Commons Sharealike License

This Privacy Policy is adapted from the Automattic ("legalmattic") Privacy Policy, which is made available under a **Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)** license. Modifications, additions, and removals were made by Teefs to accurately describe how Teefs operates. You may reuse this Policy under the same CC BY-SA license, provided that the resulting document reflects your actual practices and credits the original source.

---

## Information We Collect

We collect information in the ways described below.

### Information You Provide to Us

- **Basic account information.** To use most of the Services, you sign in through our identity provider, Kinde. Your email address, password, and any federated-login profile (for example, from Google) are managed by Kinde, **not by Teefs**. From Kinde we receive your unique user identifier, and (where available) your email, name, picture, email-verification status, and the set of permissions assigned to your account.
- **Public Profile Information and Marketing Use.** Your **display name**,
  and eventually your **avatar/profile image**, are stored in your Teefs
  profile and may be visible to other Users in features that surface
  authorship or activity (for example, indicators of which Editor is
  currently editing a module).
  By creating an account, you grant Teefs a **non-exclusive, royalty-free,
  worldwide, perpetual, and sublicensable license** to use, reproduce,
  display, and distribute the following for marketing, promotional, and
  operational purposes:
  - (a) your **display name and or avatar** in aggregated or individual form
    (e.g., "Join 10,000+ students like [Display Name]");

  - (b) **aggregated and anonymized usage data**, including total user
    counts, active user metrics, study statistics, and performance trends,
    in marketing materials, dashboards, social media, investor
    communications, and public-facing content;

  - (c) any **testimonials, reviews, feedback, or content** you voluntarily
    submit to Teefs or post publicly about the Services, including the
    right to edit such content for length and clarity without altering
    its substantive meaning.

  You may request removal of your individual display name or avatar
  from active marketing materials through our contact page.
  Removal requests do not apply to (i) materials already distributed
  or printed, (ii) aggregated or anonymized data that no longer
  identifies you, or (iii) testimonials you have voluntarily provided,
  unless required by applicable law.

- **Payment and contact information.** _We do not currently collect or process payment information._ If we add paid features in the future, we will update this Policy and the relevant payment information will be handled by a PCI-compliant third-party processor.
- **Business profile.** _Not applicable today._ The Services are provided to individual learners and Editors.
- **Content information.** Information you submit to the Services as User Content under the Terms of Service, including:
  - For all Users: feedback you submit, prompts you enter into AI-assisted features, marked statuses you assign to questions ("learning", "needs review", "done"), and similar interactions.
  - For Editors (Users with the edit permission): modules, questions, answer choices, explanations, validation marks (`ai` or `human`), and related metadata that you create, edit, or delete.
- **Credentials.** Account credentials are handled exclusively by Kinde. **Teefs does not see, receive, or store your password.**
- **Communications with us.** When you submit our Contact form, we receive the **name, email address, topic, and message** you provide. The submission is delivered to our designated support inbox via our transactional-email provider (Resend); the message itself is not stored in the Teefs application database.
- **Consent records.** When you accept these Terms of Service and this Privacy Policy (and on subsequent material updates), we record the fact of your acceptance, the version of the document accepted, and the timestamp of acceptance, associated with your account.
- **Job applicant information.** _Not applicable today._ If we begin accepting applications, we will describe the relevant practices in an addendum or updated Policy.

### Information We Collect Automatically

- **Log information.** Our hosting and infrastructure providers (Supabase for database and authorized API access, and Kinde for authentication) generate standard server logs that may include your IP address, user-agent string, request paths, timestamps, and referring URLs. These logs are produced and retained by those providers under their own terms.
- **Security and abuse-prevention data.** To protect our public endpoints (such as the Contact form and the social-share image renderer) from automated abuse and denial-of-service, our application reads the client IP address from standard forwarded request headers (`X-Forwarded-For`, `X-Real-IP`) and sends key derived from it to our rate-limiting provider (**Upstash**) as a short-lived counter. For signed-in callers we use the account identifier instead of the IP. These counters automatically expire at the end of each rate-limit window (typically one hour).
- **Transactional information.** Records of your interactions with the Services, including question attempts, answer submissions, status changes, and content edits performed by Editors. These records are stored in our database to provide the Services to you.
- **Usage information.**
  - **Question progress.** When you answer or mark a question, we store the question identifier, the status you assigned ('done', 'learning', or 'needs-review'), the option identifier you submitted (when you completed a question), and timestamps. This data powers your dashboard, your review queues, and the radar-chart review analytics, which are computed on the fly from your stored progress.
  - **Daily completion counts.** We store a per-day count of questions you completed in order to render your activity heatmap.
  - **Editor activity.** For Users with editor permissions, we store the identifier of the Editor currently holding a lock on a module or question, the timestamp the lock was acquired, and the `validated` provenance of questions ('ai' or 'human').
- **Location information.** We do not perform geolocation in the application. Our infrastructure providers may infer general location (for example, country or region) from IP address as a normal part of operating their platforms.
- **Stored information (your device).** To support a fast, offline-friendly experience and to preserve progress before sign-in, we use your browser's **local storage** to keep:
  - your in-progress question status (`teefs_progress`);
  - your daily completion counts (`teefs_daily_completions`); and
  - your theme preference (light/dark), via the `next-themes` library.
    Once you sign in, we synchronize this data with your account so it is available across devices. You can clear this information at any time by clearing your browser's local storage for the Teefs domain.
  - your language preference (e.g. english)
- **Information from cookies and similar technologies.** See the **Cookies Policy** section below.

### Information We Collect from Other Sources

- **Third-Party Login.** When you sign in through Kinde or a provider that Kinde federates (for example, Google), we receive the identifiers and basic profile fields described above. We do not receive your password from these providers. If you're locked out of your account Teefs via Kinde can set a temporary password and share it with them via your provided email, reach out via our contact page if you have such an issue.
- **Social Sharing Services.** _We do not currently integrate with social-sharing services._
- **Financial Account Info.** _We do not currently collect financial account information._

---

## Cookies Policy

We use cookies and similar technologies to operate the Services. We are committed to using only what we need.

### Categories We Use Today

- **Strictly necessary cookies.** Cookies set by our authentication provider (Kinde) and our database client (Supabase) are required for sign-in, session continuity, and to enforce row-level security on your data. Without these cookies, the Services will not function.
- **Functional storage.** Local-storage entries used by the application include `teefs_progress`, `teefs_daily_completions`, and a theme preference set by `next-themes`. These are not "cookies" in the strict sense but serve a similar functional purpose and are stored locally on your device's browser.

### Categories We Do Not Use

- **Cross-site tracking cookies.** We do not currently use third-party cross-context behavioral-advertising cookies.

### Categories We May Collect and Use In the Future

Teefs reserves the right, to the fullest extent permitted by
applicable law, to expand the categories of data we collect,
process, and use as the Services evolve. Such future categories
may include, but are not limited to:

- **Analytics and Usage Data.** Information about how you
  interact with the Services, including pages viewed, features
  used, time spent, click patterns, device and browser
  information, IP address, referral sources, and session
  metadata, for the purposes of improving the Services,
  diagnosing technical issues, and understanding user behavior
  in aggregate.

- **Advertising and Marketing Data.** Information used to
  deliver, measure, and improve advertising and promotional
  content, including engagement metrics, conversion data,
  and attribution information. Teefs does not currently sell
  or share personal information with third-party advertisers,
  but reserves the right to introduce advertising-supported
  features in the future, subject to applicable law and
  any required notice or consent.

- **Performance and Behavioral Data.** Aggregated and
  individualized data regarding study patterns, question
  performance, time-on-task, and learning outcomes, used
  to develop adaptive features, personalize the Services,
  and improve content quality.

- **Third-Party Integrations.** Data received from third-party
  services you elect to connect to your Teefs account
  (e.g., authentication providers, calendar integrations,
  or institutional single sign-on), limited to information
  reasonably necessary to provide the integrated functionality.

### Notice of Material Changes

If Teefs begins collecting or using a category of data in a
manner that constitutes a material change to this Privacy
Policy, Teefs will provide notice to affected Users through
reasonable means, which may include in-app notifications,
email, or a prominent notice on the Services, prior to or
contemporaneously with such change taking effect. Where
required by applicable law, Teefs will obtain any necessary
consent before such collection or use begins.

Your continued use of the Services following such notice
constitutes acceptance of the updated terms, except where
applicable law requires affirmative opt-in consent.

### Browser Controls

Most browsers let you view, manage, block, or delete cookies and clear local storage through their settings. Disabling strictly necessary cookies will prevent you from signing in or using authenticated features.

### Do Not Track

Because there is no industry consensus on how to interpret the "Do Not Track" signal and because we do not engage in cross-site tracking, our Services do not currently respond differently to a Do Not Track signal.

---

## How and Why We Use Information
- **Rate-limit and protect public endpoints.** We use the client IP address (or, for signed-in users, the account identifier) as a short-lived key in our rate-limiting provider to throttle anonymous traffic to the Contact form, the social-share image renderer, and similar public endpoints, and to mitigate automated abuse, scraping, and denial-of-service.

### Purposes for Using Information

We use the information we collect to:

- **Provide, operate, and maintain the Services**, including authenticating you, syncing your progress across devices, rendering modules and questions, enforcing access controls, and detecting and preventing abuse.
- **Personalize your study experience**, including your dashboard, review queues, activity heatmap, and radar-chart analytics. Where these features describe areas to revisit, the framing relates exclusively to **exam readiness**, not clinical readiness or professional competency.
- **Respond to messages and support requests** that you submit through the Contact form.
- **Improve and develop the Services**, including reviewing aggregated, de-identified usage to improve content quality and the user experience.
- **Maintain security and integrity**, including row-level-security enforcement, lock-conflict detection, single-account-per-human enforcement, and abuse and fraud prevention.
- **Comply with law and enforce our agreements**, including responding to lawful requests and enforcing the Terms of Service.
- **Operate AI features.** Where AI features are enabled in the Services, we may send **non-personal prompts** (for example, the text of a draft question and instructions to revise it) to AI providers such as Anthropic. We do not send your account identity or your individual progress data to AI providers as part of question generation.
- **Operate AI features.** Where AI features are enabled in the
  Services, we may send **non-personal prompts** (for example,
  the text of a draft question and instructions to revise it)
  to AI providers such as, but not limited to, Anthropic. We do not send your account
  identity or your individual progress data to AI providers as
  part of question generation. AI providers may retain prompts
  and outputs for a limited period in accordance with their own
  terms and privacy policies, typically for abuse monitoring
  and service improvement purposes.

### Legal Bases for Collecting and Using Information

For Users residing in U.S. states with comprehensive consumer
privacy laws (including but not limited to California, Colorado,
Connecticut, Virginia, Utah, Texas, Oregon, and Montana), we rely
on the following legal bases for collecting and processing personal
information, to the extent such bases are required by applicable law:

- **Performance of a contract** with you, in order to provide,
  maintain, and support the Services you have requested.

- **Our legitimate business interests**, including securing the
  Services, preventing fraud and abuse, improving content quality
  and user experience, conducting analytics, and operating our
  business — provided that such interests are not overridden by
  your rights and freedoms under applicable law.

- **Your consent**, where consent is required by applicable law
  (for example, for non-essential cookies, targeted advertising,
  or processing of sensitive personal information, if and when
  such features are introduced).

- **Compliance with a legal obligation**, including responding to
  lawful requests from government authorities, courts, or
  regulators, and complying with applicable record-keeping,
  tax, and reporting requirements.

---

## Sharing Information

### How We Share Information

- **Personnel.** Individuals working with Teefs (whether as
  employees, contractors, or consultants) who help operate the
  Services are bound by confidentiality obligations and use
  information only as needed to perform their duties.
- **Third-party vendors (sub-processors).** We share information with the providers necessary to operate the Services. Today these include:
  - **Kinde** — authentication, identity, and permissions
  - **Supabase** — database hosting, storage, and authorized data access
  - **Any Web Hosting Platform(s)** — application hosting and edge serving
  - **Resend** — transactional email (Contact form delivery)
  - **Google Fonts** — typography
  - **Unsplash** — image delivery for certain visual assets
  -  **Upstash** — serverless Redis used for rate limiting and abuse prevention on public endpoints
  - **AI providers** (such as **Anthropic**) — only if and when AI features are enabled in production, and only with non-personal prompts as described above
    Each of these providers processes information under its own terms and privacy policy.

    We may update the list of sub-processors as the Services evolve.
    Material changes will be reflected in updates to this Policy.

- **Legal and regulatory requirements.** We may disclose information when required by law, regulation, legal process, or governmental request.
- **To protect rights, property, and others.** We may disclose information when we reasonably believe it is necessary to enforce our Terms, prevent fraud or abuse, or protect the rights, property, or safety of Teefs, our Users, or others.
- **Business transfers.** If we are involved in a merger, acquisition, financing, sale of assets, bankruptcy, or similar transaction, information may be transferred as part of that transaction.
- **With your consent.** We will share information at your direction or with your consent.
- **Aggregated or de-identified information.** We may share information that has been aggregated or de-identified such that it cannot reasonably be used to identify you.

### Information Shared Publicly

Your **display name** and **avatar** may be visible to other Users in features that surface authorship or activity (for example, the indicator of which Editor holds a content lock). Otherwise, your account and your study progress are not made public by Teefs.

### What We Do Not Do

- **We do not sell your personal information.**
- **We do not "share" personal information for cross-context behavioral advertising** as those terms are defined under California law.
- **We do not engage in personalized advertising.**

---

## How Long We Keep Information

- **Account data** (the records in your Teefs profile) is kept for as long as your account is active. However, this is subject to change if a user has been inactive for the duration of one year.
- **Study progress and daily completion counts** are kept for as long as your account is active so that you do not lose your study history. They are deleted when you delete your account, subject to the exceptions below.
- **Editor metadata** (the identifier of the Editor who last held a lock, lock timestamps, and `validated` marks on questions) is retained as part of the provenance record of the Content for as long as the Content remains in the Services.
- **Contact form messages** are retained in our designated support inbox for support follow-up. You may request deletion of past messages.
- **Consent records** (acceptance of the Terms of Service and this Privacy Policy) are retained for the period needed to demonstrate consent under applicable law.
- **Backups, server logs, and infrastructure-provider records** are retained according to the standard retention windows of the relevant provider.
- **Rate-limit counters** (IP- or user-keyed counters at our rate-limiting provider) are retained only for the duration of the applicable rate-limit window (typically one hour) and then automatically expire.
- We may retain information for longer where required by law, to resolve disputes, to enforce our agreements, or to protect our rights.

---

## Security

Teefs employs reasonable administrative, technical, and
organizational safeguards designed to protect the personal
information we collect against unauthorized access, disclosure,
alteration, loss, or destruction. The specific measures we
implement are subject to change as security best practices
evolve and are not disclosed publicly for security reasons.

### No Guarantee of Security

You acknowledge and agree that:

(a) **No method of electronic transmission, storage, or processing
is fully secure**, and Teefs cannot and does not guarantee the
absolute security of any information transmitted to or from the
Services or stored on our systems;

(b) **You provide information at your own risk**, and to the
fullest extent permitted by applicable law, Teefs disclaims
liability for unauthorized access, interception, or compromise
of information arising from circumstances beyond our reasonable
control;

(c) **You are solely responsible** for safeguarding your account
credentials, maintaining the security of the devices and networks
you use to access the Services, and promptly notifying Teefs of
any suspected unauthorized access to your account.

### Breach Notification

In the event of a data breach affecting your personal information,
Teefs will provide notice in accordance with applicable law,
including any required notifications to affected Users and
relevant regulatory authorities. The timing, content, and method
of such notice will be determined by the requirements of
applicable law and the circumstances of the incident.

**For California residents**, notification will be provided in
the most expedient time possible and without unreasonable delay,
consistent with California Civil Code § 1798.82, subject to any
legitimate needs of law enforcement or measures necessary to
determine the scope of the breach and restore the reasonable
integrity of the data systems.

### Your Security Obligations

You agree to:

(a) maintain the confidentiality of your account credentials and
not share them with any third party;

(b) use a strong, unique password and enable any multi-factor
authentication options offered by the Services;

(c) immediately notify Teefs via our contact page of any
known or suspected unauthorized access to or use of your account;
and

(d) accept responsibility for all activities that occur under your
account, except to the extent caused by Teefs' gross negligence
or willful misconduct.

---

## Choices

You have meaningful choices about your information:

- **Manage your identity.** Update your email, password, federated logins, and primary profile fields. IF you have issues, contact us via our contact page.
- **Manage your Teefs profile.** Update your display name and avatar in the Teefs profile area, when the feature(s) is/are available.
- **Clear local progress.** Clear `localStorage` for the Teefs domain in your browser to remove `teefs_progress`, `teefs_daily_completions`, and theme preferences from your device. (Server-synced data remains available to your account.) This data will be repopulated once logged in again and synced with our database.
- **Manage cookies.** Use your browser settings to view, block, or delete cookies. Disabling strictly necessary cookies will prevent sign-in.
- **Delete your account.** You may request deletion of your
  account at any time through the Contact page. We will process
  verified deletion requests within the timeframes required by
  applicable law. We are working to implement an in-app
  self-service deletion mechanism in a future update.
- **Marketing communications.** We do not currently yet send marketing email. When we begin to do so, we will provide a clear opt-out mechanism in every marketing message.

---

## Your Rights

### Users Located Outside the United States

The Services are intended solely for residents of the United
States. Teefs does not market, target, or knowingly offer the
Services to individuals located in the European Economic Area
("EEA"), the United Kingdom, Switzerland, Canada, or any other
jurisdiction outside the United States.

**If you are located outside the United States, you are not
authorized to use the Services.** We respectfully request that
you:

(a) **discontinue use** of the Services immediately;

(b) **delete your account** by contacting our Contact Page or
through the in-app account deletion feature; and

(c) **refrain from submitting** any personal information to the
Services.

### Limited Rights for Non-U.S. Users

Although Teefs does not target or knowingly serve users outside
the United States, if you nonetheless accessed the Services from
the EEA, the United Kingdom, or Switzerland and provided personal
information, you may have certain rights under applicable law,
including the rights of access, rectification, erasure,
restriction of processing, data portability, objection to
processing, and withdrawal of consent where processing is based
on consent. You may also have the right to lodge a complaint
with your local supervisory authority.

To exercise any such rights, or to request deletion of your
account and associated data, please contact us at our Contact Page.
Teefs will respond to verified requests in accordance with
applicable law.

### No Submission to Foreign Jurisdiction

By using the Services, you acknowledge that Teefs operates
exclusively within the United States and that any information
you provide will be processed and stored in the United States.
Teefs does not consent to the jurisdiction of foreign courts
or regulatory authorities, except to the extent required by
applicable law. Your continued use of the Services from outside
the United States, after notice that the Services are not
intended for such use, is at your own risk and constitutes a
breach of these Terms.

## US State Privacy Rights

If you are a resident of a U.S. state with a comprehensive consumer
privacy law — including California (CCPA/CPRA), Colorado (CPA),
Connecticut (CTDPA), Virginia (VCDPA), Utah (UCPA), Texas (TDPSA),
Oregon (OCPA), and Montana (MCDPA) — you have the rights described
in this section, to the extent provided by your state's law.

### Our Practices at a Glance

**Teefs does not, and does not intend to:**

- sell your personal information (including your email address) to
  any third party;
- share your personal information with advertisers, data brokers,
  or other third parties for cross-context behavioral advertising
  or marketing purposes;
- engage in personalized or behavioral advertising;
- conduct automated profiling that produces legal or similarly
  significant effects concerning you;
- offer financial incentives in exchange for personal information;
  or
- share personal information with third parties for those third
  parties' direct marketing purposes (Cal. Civ. Code § 1798.83,
  the "Shine the Light" law).

### Your Rights

Subject to your state's specific law and applicable exceptions,
you have the following rights with respect to your personal
information:

- **Right to Know / Access.** You may request that we disclose the
  categories and specific pieces of personal information we have
  collected about you, the categories of sources, the business or
  commercial purposes for collecting it, and the categories of
  third parties (such as service providers) with whom it is shared.

- **Right to Portability.** You may request a copy of your personal
  information in a portable, readily usable format.

- **Right to Delete.** You may request that we delete personal
  information we hold about you, subject to legal exceptions
  (such as records we are required to retain for legal,
  accounting, or fraud-prevention purposes).

- **Right to Correct.** You may request that we correct inaccurate
  personal information we hold about you.

- **Right to Limit Use of Sensitive Personal Information.** Teefs
  does not collect categories of "sensitive personal information"
  beyond account authentication credentials, which are managed by
  our authentication provider, Kinde.

- **Right to Opt Out of Sale, Sharing, and Targeted Advertising.**
  Not applicable to current Teefs practices, as we do not engage
  in any of these activities. See "Our Practices at a Glance"
  above.

- **Right to Opt Out of Profiling.** Not applicable to current
  Teefs practices, as we do not engage in automated profiling
  that produces legal or similarly significant effects.

- **Right to Non-Discrimination / Non-Retaliation.** We will not
  deny services, charge different prices, or provide a different
  level of quality of service because you exercised any of these
  rights.

- **Right to Appeal.** Where required by your state's law (such
  as in Colorado, Connecticut, Virginia, and Texas), you may
  appeal our decision regarding a privacy request by contacting
  us at our Contact Page.

### Authorized Agents

You may designate an authorized agent to submit a request on your
behalf. We may require:

(a) written, signed permission from you authorizing the agent to
act on your behalf;

(b) verification of the agent's identity; and

(c) verification of your own identity directly with us.

### If Our Practices Ever Change

In the unlikely event Teefs' practices materially change, we will:

(a) update this Privacy Policy and notify affected Users in
accordance with applicable law;

(b) obtain any consent required by applicable law before
implementing such changes; and

(c) provide a clear opt-out mechanism, including any "Do Not
Sell or Share My Personal Information" link required by law
and honoring recognized opt-out preference signals such as
Global Privacy Control ("GPC").

### How to Exercise Your Rights

To exercise any of the rights described above, please contact us through the **Contact** page on the Website. We will verify your identity (typically by confirming control of the email associated with your account or, where appropriate, additional information) and will respond within the timeframes required by applicable law.

(a) **verify your identity** before responding, to protect your
information from unauthorized requests;

(b) **respond within the timeframes required by applicable law**,
generally within 45 days, subject to extension as permitted by law;
and

(c) **respond free of charge**, except where requests are
manifestly unfounded, excessive, or repetitive, in which case we
may charge a reasonable fee or decline the request as permitted
by law.

### Appeals Process for Rights Requests Denials

If we deny your request, you may appeal by replying to our denial through the **Contact** page. We will reconsider the request and respond within the time frame required by applicable law. If you remain dissatisfied with our response, you may contact your state attorney general or the relevant supervisory authority.

---

## Controllers and Responsible Companies

Teefs is the **controller** of the personal information described in this Policy. Our sub-processors process personal information on our instructions and pursuant to their own terms and privacy policies.

---

## How to Reach Us

For privacy questions, requests, or appeals, please contact us through the **Contact** page on the Website.

---

## Other Things You Should Know

### Transferring Information

Teefs is operated in the United States and your information will be processed in the United States. If you access the Services from outside the United States, by using the Services you consent to the transfer of your information to, and the processing of your information in, the United States.

### Ads and Analytics Services Provided by Others

We do not currently use third-party advertising or analytics services. If we begin to do so, we will update this Policy and, where required, present a consent mechanism.

### Third-Party Software and Services

The Services may include links to, or integrations with, third-party websites, software, and services. Those third parties have their own terms and privacy practices, and we are not responsible for them. Please review the policies of any third-party services you use.

### Visitors to Public Pages

Visitors who view public pages without signing in are subject to the standard server logs of our hosting providers as described above. We do not build profiles of unauthenticated visitors.

### Children and Minors

The Services are intended solely for individuals **18 years of age
or older**. We do not knowingly collect personal information from
anyone under 18, including children under 13 as defined by the
Children's Online Privacy Protection Act ("COPPA"). If we learn
that we have collected personal information from a person under
18, we will promptly delete it and terminate the associated
account. If you believe a minor has provided us with personal
information, please contact us through the Contact page.

### Educational Institutions

If you access the Services through or at the direction of an
educational institution, additional terms or restrictions may
apply, including those imposed by the Family Educational Rights
and Privacy Act ("FERPA") or your institution's data agreements.
Teefs does not currently have institutional agreements with
educational institutions, but reserves the right to enter into
such agreements in the future.

---

## Privacy Policy Changes

We may update this Policy from time to time. When we do, we will post the updated Policy on the Website and revise the "Effective date" above. For material changes, we will use reasonable efforts to provide additional notice (for example, by email or by an in-product notice) and, where appropriate, request renewed acceptance. **Your continued use of the Services after the effective date of any updated Policy constitutes your acceptance of that updated Policy.**

---

**Reservation of Rights.** To the fullest extent permitted by
applicable law, any rights not expressly granted to Users under
this Agreement are reserved by Teefs. The non-exercise or delayed
exercise of any right under this Agreement shall not constitute
a waiver of such right.

---

## Other Information and Resources

- **Terms of Service** — `/legal/terms`
- **Contact** — see the Contact page on the Website

---

## Translation

This Policy was originally written in English (US). If we make a translation available and there is any conflict between the translation and the English version, **the English version controls**.

**Version History.** Prior versions of this Privacy Policy are
available at [https://github.com/BryanAM/teefs-legal]. Each version is tagged with its
effective date for reference.
