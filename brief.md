Version: NAFATH-V1
Track: Software

## Overview
A robust national digital login service is possible only with collaboration across many segments of IT. Software protocols allow the authority to verify users and provide them with services. Suspicious login patterns may be detected by the artificial intelligence, but prior to its deployment, its risks, accuracy, fairness, and the requirement for human oversight need to be evaluated. Mobile security ensures that our application asks for the minimum permissions and that the data stored in the citizens’ devices is safe. Networking protocols like DNS over HTTPS can enhance the privacy of DNS queries, but they don’t conceal all online activity. Cybersecurity features, such as phishing-resistant authentication, mitigate the risk of account compromise and unauthorized account access. Data protection practices ensure the citizen’s data is collected, stored and processed legally. These areas together enable a log-in service that is dependable, easy to use, privacy-conscious, and resistant to security threats.

## Software
OAuth 2.0 and OpenID Connect (OIDC) are two different things in digital identity. OAuth 2.0 is an authorization framework that enables applications to access protected resources with permission. OpenID Connect extends OAuth 2.0 with an identity layer that allows applications to verify a user's identity using an ID token. This distinction is useful for a national login service, as it allows access permissions to be kept separate from user authentication.

Reference: OpenID Foundation - How OpenID Connect Works - https://openid.net/foundation/how-connect-works/

## AI
The national login service can use artificial intelligence to identify unusual login patterns and flag potentially suspicious activity. AI predictions can be inaccurate or biased, so citizens should not be automatically blocked based on them without proper safeguards. The risk needs to be assessed by the authority, the system performance needs to be monitored, personal data needs to be secured, and human oversight needs to be retained for key decisions.

Reference: NIST - AI Risk Management Framework - https://www.nist.gov/itl/ai-risk-management-framework

## Mobile
The mobile app should only ask for device permissions that are essential to its functionality. Excessive access to contacts, location or files can increase privacy risks and decrease user trust. Developers should provide justification for each permission and make the request when the feature that requires the permission is in use. Secure storage, frequent updates and transparent privacy notices further protect citizens engaged in the service.
Resource: Android Developers - Request app permissions - https://developer.android.com/training/permissions/requesting

## Networking
DNS over HTTPS (DoH) carries DNS requests inside an encrypted HTTPS connection, making it harder for others on the same network to see or alter them. This added privacy can be useful when people use a government login service, but it does not conceal everything they do online or defend against every threat. DoH works best alongside sound network settings and other privacy measures.

Source: RFC Editor, RFC 8484, “DNS Queries over HTTPS (DoH)” — https://www.rfc-editor.org/rfc/rfc8484

## Cybersecurity
Phishing-resistant authentication prevents citizens from being phished by attackers looking to harvest passwords or login codes. National login services might consider strong authentication options, such as security keys or passkeys, in addition to monitoring and account recovery protections. Security controls need to be routinely tested and should protect accounts in a manner that does not unduly deter legitimate users from using the government services.
Resource: NIST - Digital Identity Guidelines, SP 800-63B - https://pages.nist.gov/800-63-4/sp800-63b.html

## Data
A national login service can have access to personal information including name, ID information, and logs of authentication. Data protection involves being necessary in data collection, restricting access to the data to those are authorized to do so and ensuring the data is protected while stored and in transit. Transparent retention policies and responsible management mitigate privacy risk and foster public trust. The organizations also should comply with the relevant laws, rules, and procedures for data protection.

Resource: [logy - https://www.mtcit.gov.om/](https://prod.mtcit.gov.om/ITAPortal/MediaCenter/Document_detail.aspx?NID=10154)

## Misconception in My Track

## Open Question
