# Contributing

Small, reproducible improvements are welcome: a clear bug report, a corrected first-run instruction, an example that builds, or a focused code fix. Start with the affected repository's own documentation; repository-specific instructions take precedence over these defaults.

## Before a change

Check existing issues and the current release. For a substantial API or architecture change, open a short issue describing the use case before doing a large rewrite. A documentation correction usually needs only a focused pull request.

Keep physical input interception, virtual device creation, SDK bindings and product installation distinct. Preserve upstream attribution and file-level licences. A source licence does not change the rights for a prebuilt driver or commercial redistribution.

## A useful pull request

Explain the problem, the resulting behavior and the validation performed. Include an example when it helps a reviewer. Keep changes focused and avoid unrelated formatting or generated build output.

State the Windows build, toolchain, architecture and relevant product/SDK version for executed tests. Distinguish offline checks, virtual fixtures and physical hardware. If a check was not run, say so; do not describe an unexecuted command as a passed test.

Driver changes need their own signing and qualification process. Do not alter evaluation limits, activation, signatures or Windows protection settings to make a test pass. Kernel experiments belong in a dedicated, disposable lab rather than an ordinary workstation.

## Documentation and examples

Give prerequisites, exact commands, expected output and a way to stop or remove the example. Keep preview limitations and known issues visible. Do not claim universal performance, leak freedom, certification or compatibility from a narrower test.

If AI tools assisted a contribution, explain the assistance where it matters and take responsibility for checking the result. Do not submit invented references, fabricated test results or code whose behavior you cannot explain.

## Keep private information private

Do not commit credentials, customer keys, signing material, commercial driver bundles, personal input traces or full crash dumps. Follow [SECURITY.md](SECURITY.md) for suspected vulnerabilities and [SUPPORT.md](SUPPORT.md) for ordinary questions.

Be specific, courteous and open to correction. Feedback should address the implementation and evidence rather than the person.
