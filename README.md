# Braid: Adding Synchronization to HTTP

This is the working area for the [Braid](https://braid.news) extensions to
HTTP in the [IETF HTTP Working Group](https://httpwg.org/).  These extensions
add Synchronization to HTTP.  They are authored in three documents:

### Braid HTTP — `draft-xx-httpbis-braid-00.txt`
Extends HTTP with three core features:

1. *Subscriptions* to GET requests
2. *Versioning* to resources
3. *Merge semantics* for PATCH requests


### Braid Patch — `draft-xx-httpbis-braid-patch-00.txt`

A general patch format for representing changes to state with a uniform
syntax.  This patch format can be used with any CRDT or OT merge algorithm,
and can be applied to almost any `Content-Type`.  It thus enables web
resources to mix and match which merge algorithm they want to use on which
piece of data.

### Linked JSON — `draft-xx-httpbis-linked-json-00.txt`

Linked JSON is an extension to JSON that defines a new datatype: a "Link".
This allows JSON objects to compose across websites.

## Contributing

You are welcome to edit any of these documents.  To get Github access, send
your login to [Michael](mailto:toomim@gmail.com).  Discuss edits on the
[Braid mailing list](https://groups.google.com/forum/#!forum/braid-http).
After editing, add your name to the authors list at the top and bottom of the
document.

Discussion of the finished drafts will occur on the
[IETF HTTPWG mailing list](https://lists.w3.org/Archives/Public/ietf-http-wg/)
mailing list.  You might also like to familiarize yourself with other
[HTTP working group documents](https://github.com/httpwg/http-extensions/blob/master/CONTRIBUTING.md).

All material in this repository is considered Contributions to the
([IETF](https://www.ietf.org/)) Standards Process, as defined in the
intellectual property policies of IETF currently designated as
[BCP 78](https://www.rfc-editor.org/info/bcp78),
[BCP 79](https://www.rfc-editor.org/info/bcp79) and the
[IETF Trust Legal Provisions (TLP) Relating to IETF Documents](http://trustee.ietf.org/trust-legal-provisions.html).

Any edit, commit, pull request, issue, comment or other change made to this
repository constitutes Contributions to the IETF Standards Process
(https://www.ietf.org/).

You agree to comply with all applicable IETF policies and procedures,
including, BCP 78, 79, the TLP, and the TLP rules regarding code components
(e.g. being subject to a Simplified BSD License) in Contributions.
