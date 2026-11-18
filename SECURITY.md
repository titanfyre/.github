# Reporting a security concern

If a behavior may expose data, cross a privilege boundary or allow unauthorized control, avoid posting sensitive reproduction details or dumps in a public issue.

## Private reporting

Use the affected repository's **Security → Advisories → Report a vulnerability** button when available. That opens GitHub's private reporting channel to the repository maintainers. Check the repository and account name before submitting.

If the button is unavailable, contact the maintainer through the documented Discord username **titancsa** to arrange a private channel. Do not send passwords, customer licence keys, signing keys or a full memory dump in an initial message.

Include the affected product and exact version, the relevant Windows build/architecture, a concise impact statement and the minimum steps needed to understand the issue. Distinguish an observed result from a suspected consequence. Share large or sensitive diagnostic files only after agreeing on an appropriate private transfer.

## Scope and handling

Reports about a published release or public source are useful even if support status needs to be assessed. The maintainer will determine the affected versions and remediation path; this policy does not promise a response time, bounty, certification or guaranteed fix.

Ordinary installation questions, feature requests and non-sensitive reproducible bugs belong in the affected repository's Issues tab. Known public stability findings should remain visible; reporting privately is not a reason to conceal already documented limitations.

Applications, SDK clients and signed drivers have separate release and qualification processes. A driver fix is not ready for distribution merely because user-mode tests pass. Do not bypass evaluation mechanisms or disable host protections when investigating.
