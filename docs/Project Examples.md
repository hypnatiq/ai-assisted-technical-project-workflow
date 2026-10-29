# Project Examples

## HypNO

The workflow helped organize requirements, source changes, regression testing, documentation, screenshots, and evidence limits for a Windows network investigation application.

Verified example:

- HypNO `0.83.9-dev` source candidate
- AI-assisted regression review
- 1,093 tests completed with zero failures

Limit:

The source result does not automatically prove that a packaged build was installed or that live firewall and network behavior passed on another computer.

## AstrasGZ network traffic analysis

The workflow helped turn packet captures into a documented case study using Wireshark, TShark, a Flask and SQLite log viewer, structured filtering, and sanitized screenshots.

Verified example:

- Three controlled Windows capture sessions
- 120,656 packets in the extended session
- Protocol, port, endpoint, connection-attempt, and UDP filtering

Limit:

The captures did not certify the client or remote service as safe. Process attribution, destination context, repeated testing, and current reputation evidence were still needed for stronger conclusions.

## IT support documentation

The workflow helped structure technical guides so each one identifies the evidence, controlled change, escalation point, rollback path, and validation step.

Limit:

A written guide still needs review against the real environment and permissions before another technician uses it.

## Cross-computer handoffs

The workflow uses manifests, hashes, decision records, and acceptance checks to show what was transferred and whether it matched the prepared source.

Limit:

Copying a package does not prove the receiving computer applied, tested, or accepted it.

