# Project Examples

## HypNO

The workflow helped organize requirements, source changes, regression testing, documentation, screenshots, and evidence limits for a Windows network investigation application.

Limit:

Source testing, interface screenshots, packaging, installation, and live firewall behavior are separate results. One does not automatically prove the next.

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

## Enterprise home network virtual lab

The workflow helped define an isolated Hyper-V architecture, test AD and DNS, review OPNsense segmentation, preserve accepted and denied paths, document EAP-TLS results, and keep failed tests in the final record.

Verified example:

- Seven private Hyper-V switches with no household-network binding
- Accepted and denied segmentation paths
- FreeRADIUS EAP-TLS accept and reject results
- Diskless PXE DHCP and WDS service response

Limit:

The evidence supports a virtual learning environment. It does not prove physical NAC, household-network deployment, Windows image deployment, or independent production administration.

## Cross-computer handoffs

The workflow uses manifests, hashes, decision records, and acceptance checks to show what was transferred and whether it matched the prepared source.

Limit:

Copying a package does not prove the receiving computer applied, tested, or accepted it.
