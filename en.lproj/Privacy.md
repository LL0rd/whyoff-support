# Privacy in WhyOff

## Measurements on your Mac

You can run diagnostics without an account with us. WhyOff pairs with the separately started aOSnetTools program over an encrypted connection on your Mac. The app keeps the pairing code in memory and discards it when you choose Disconnect. WhyOff includes no advertising or analytics SDKs and sends us no diagnostic results.

The tool you use determines who receives a request. For a DNS query, the resolver receives the name you look up. For a connection check, the destination server sees the source address of the connection. Local discovery can send a request to several devices on the network. Mail and file tools can send content you select to the specified destination. The operators of those systems control their own logs.

## Stored data and deletion

Depending on the tool, WhyOff saves settings, target history, profiles, aliases and selected measurement totals on your Mac. A profile can include hostnames, usernames or a URL with query parameters. You can delete saved profiles in the tool’s profile manager. Exports, packet captures and invocation files may contain addresses, device identifiers or transmitted content. Delete your own files and any shared copies separately.

In the SNMP tool, you can explicitly save credentials to the local Keychain. The item does not sync through iCloud. Clearing credentials clears the input fields. To remove a saved item, select the same target details in the SNMP tool and delete the Keychain entry.

## WhyOff Pro

Apple processes purchases and restores. The app uses StoreKit on your Mac to check whether WhyOff Pro is unlocked. WhyOff sends the purchase receipt to neither the developer nor the diagnostic program. Read [Apple’s App Store privacy information](https://www.apple.com/legal/privacy/data/en/app-store/) for details.

## Support and privacy requests

If you email whyoff@d-r.dev, we receive your email address, message and any attachments you send. We use them to handle your request and answer follow-up questions. Proton Mail (Proton AG, Switzerland) hosts our support mailbox. Check attachments for credentials and private network details before sending them. [Proton Mail privacy policy](https://proton.me/mail/privacy-policy)

We keep ordinary support emails for follow-up questions for up to six months after we close your request. We delete diagnostic attachments as soon as we no longer need them to handle the case. If a legal obligation requires us to retain a particular record for longer, we keep that record for the applicable period.

Public GitHub issues and their attachments are visible to others. When you visit pages hosted there, [GitHub’s privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) also applies.

For questions about your data or to request access, correction or deletion, email [whyoff@d-r.dev](mailto:whyoff@d-r.dev) and identify the message or file concerned. Where applicable law provides for it, you can also request restriction or portability, object to processing or contact a data protection authority.

The controller is DR Development and Media LLC, Vazha Pshavela Avenue No 20, 0112 Tbilisi, Georgia. The contact person is Dimitri Roschkowski, telephone +49 721 8316699.
