# Privacy Policy

!!! info "Last Updated: 25 April 2026"

This Privacy Policy explains how Nexirift (the "Service") collects, uses, and protects your personal information when you use our federated social network instance.

## Information We Collect

### Account Information

- Username and display name
- Email address (for account verification and essential communications)
- Profile information you choose to share (bio, avatar, header image)
- Account preferences and settings

### Content and Activity

- Posts, messages, and media you share
- Interactions (likes, shares, follows, blocks)
- Public activity visible through federation
- Direct messages

### Technical Information

This is standard information collected by all platforms.

- IP address and browser information (for security and authentication)
- Device information and user agent
- Login timestamps and activity logs
- Essential cookies for authentication and functionality
- Reverse proxy and service logs needed for operations and security (for example nginx, container, and related service logs), which may include IP addresses and request metadata

### Federated Data

- Public posts and profile information shared across the Fediverse
- Follower/following relationships with users on other instances
- Public interactions with federated content

## How We Use Information

### Service Operation

- Provide and maintain the social networking service
- Enable federation with other Fediverse instances
- Authenticate users and prevent unauthorized access
- Display your content according to your privacy settings

### Communication

- Send essential service notifications
- Respond to support requests and legal inquiries
- Notify about policy changes or service updates

### Security and Moderation

- Detect and prevent spam, abuse, and security threats
- Enforce our Terms of Service and Server Rules
- Maintain logs for security and debugging purposes
- Apply network and abuse protections, including IP-based controls where required (for example access lists, geo-based filtering, and automated block lists)

### Automated Moderation (NEXA)

We employ an automated moderation system called **NEXA** ([learn more](https://code.nexirift.com/Nexirift/nexa)) to help maintain a safe and welcoming environment. NEXA runs exclusively on our servers and provides the following protections:

- **Virus detection** with ClamAV
- **Spam and scam detection** using machine learning classifiers
- **Phishing detection**
- **NSFW content detection** with the nsfwjs model

All moderation processes are performed locally, no user data is shared with third parties for moderation purposes. Your data is **never** used to train moderation models, ensuring your privacy is protected.

## Data Protection

### Security Measures

- Encrypted data transmission (HTTPS)
- Secure password storage using industry-standard hashing
- Regular security updates and monitoring
- Limited access to personal data by administrators

### Data Retention

- Account data retained while your account is active
- Deleted accounts: data removed from our servers within 30 days
- Security logs retained for up to 12 months
- Backup data may persist for up to 90 days after deletion
- Access and error logs are rotated approximately every 25 hours and deleted according to configured retention limits
- Aggregated traffic/security statistics derived from logs are retained on disk for a configurable period
- Where retention is configurable, data is kept only for as long as reasonably necessary for security, operational, and legal purposes, then deleted or de-identified

### Federation Implications

Once public (or shared private - by you) content is federated, it may be stored or redistributed by other Fediverse servers beyond our control. Deleting or modifying your content on our instance does not guarantee removal from other servers. Please consider this before sharing publicly or with specific users, as we cannot enforce deletion or privacy on remote instances.

## Your Rights

### Access, Correction, and Control

- View and export your data through account settings
- Request correction of inaccurate, out-of-date, incomplete, irrelevant, or misleading personal information
- Delete your account and associated data at any time
- Migrate to another Fediverse instance
- Control privacy settings for your content

For access or correction requests that cannot be completed directly in product settings, contact us at [privacy@nexirift.com](mailto:privacy@nexirift.com). We may request information necessary to verify your identity before processing your request.

### Data Portability

- Export your posts, media, and follower lists
- Import data when migrating from other instances
- Account migration assistance available upon request

### Privacy Complaints

If you believe we have breached applicable privacy law or mishandled your personal information, contact us at [privacy@nexirift.com](mailto:privacy@nexirift.com) with details of your complaint.

- We will acknowledge complaints within a reasonable time.
- We may request additional information to investigate and verify the complaint.
- We will provide a written outcome after completing our review.

If you are not satisfied with our response, you may contact the Office of the Australian Information Commissioner (OAIC): <https://www.oaic.gov.au>.

## Third-Party Services

### Federation

Your public data is shared with other Fediverse instances according to ActivityPub protocol standards. We cannot control how other instances handle your public data.

### Cloudflare Insights

Other than the usage of Cloudflare Insights for speed and security metrics, we do not use any third-party analytics, mainstream advertising networks, or tracking services. Errors may be tracked and stored on-site.

### Reverse Proxy and Infrastructure Components

Our infrastructure includes reverse proxy, traffic filtering, and security components. These components process IP addresses, request paths, user-agent strings, timestamps, and related metadata for security, routing, and reliability.

- Error logging: reverse proxy and related services write warning-level (and higher) error events to container logs and rotated disk logs.
- Access logging: HTTP and stream traffic logs are stored and rotated according to operational retention settings.
- IP filtering and blocking: access lists, geo-based filtering, and automated threat feeds/block lists are used to prevent abuse.
- Shared threat intelligence: relevant security signals are shared with external threat-intelligence services used for abuse prevention.
- Security alert and decision logs: alerts and security decisions that may include IP addresses, user-agent strings, and related request metadata are shared with open-appsec and CrowdSec for threat detection and enforcement.
- Log-derived reporting: access/security logs are processed into statistical reports retained for a configurable period.
- Additional security and traffic modules: custom and advanced traffic/security modules process log and request data required for routing, filtering, and protection.

Where data is forwarded to your configured backend services as part of reverse proxy operation, that transfer is required to deliver the service.

### Overseas Disclosure

Some third-party infrastructure and security providers may process or store relevant data outside Australia. Where this occurs, we take reasonable steps to work with providers that implement appropriate security and privacy controls.

### External Network and Client-Side Requests

Some network requests are initiated directly by user software or external infrastructure providers rather than by our application logic. For example, browser OCSP checks (where applicable) are performed directly between the client and certificate authority. DNS resolution is handled by DNS providers/resolvers and may involve their own data processing policies.

## Legal Basis (Australian Privacy Principles)

We process your personal information based on:

- Legitimate interests in providing the service
- Consent for optional features and communications
- Legal obligations for security and law enforcement requests

## Contact Information

For privacy-related questions, data requests, or concerns:

- **Privacy**: [privacy@nexirift.com](mailto:privacy@nexirift.com)
- **Data Protection Officer**: [dpo@nexirift.com](mailto:dpo@nexirift.com)
- **General Support**: [support@nexirift.com](mailto:support@nexirift.com)

## Changes to This Policy

We may update this Privacy Policy periodically. Material changes will be posted on the Service with an updated "Last Updated" date. Where required by law, we will seek consent for material changes.

---

_By using Nexirift, you acknowledge that you have read, understood, and agree to be bound by this Privacy Policy._
