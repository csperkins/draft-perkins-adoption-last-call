---
title: "Consistent Phrasing for Working Group Adoption and Last Call Notices"
abbrev: "Adoption and Last Call"
category: info

docname: draft-perkins-adoption-last-call-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: GEN
workgroup: PROCON Working Group
keyword:
 - next generation
 - unicorn
 - sparkling distributed ledger
venue:
#  group: WG
#  type: Working Group
#  mail: WG@example.com
#  arch: https://example.com/WG
  github: "csperkins/draft-perkins-adoption-last-call"
  latest: "https://csperkins.github.io/draft-perkins-adoption-last-call/draft-perkins-adoption-last-call.html"

author:
 -
    fullname: "Colin Perkins"
    organization: University of Glasgow
    email: "csp@csperkins.org"

normative:
  RFC2119:

  RFC2418:

  RFC7221:

  RFC8174:

informative:

...

--- abstract

This memo suggests that the IETF would benefit if working group chairs used
consistent phrasing, that has been checked for accuracy and conformance
with the IETF process documents, for working group adoption and working
group last call actions.


--- middle

# Introduction

There are two important steps in the life-cycle of a draft that is
intended for publication as an RFC on the IETF stream: adoption by a
working group and working group last call.

Working group adoption is the process whereby a working group decides to
take ownership of a draft and work further on the topic.  Adoption does not
guarantee eventual publication of the draft as an RFC, but rather indicates
that the working group believes the draft is an appropriate starting point
for discuss. Working group adoption is discussed in detail in {{RFC7221}}.

Working group last call, described in {{Section 7.4 of RFC2418}}, is the
final review step in the working group process, before a draft is submitted
to the IESG for consideration.

Working group adoption and last call are formal steps in the IETF process.
They have implications around IPR disclosure and ownership of the draft. As
such, it is important that both the draft authors and the working group
participants clearly understand what is meant by draft adoption and last
call, and what are the implications of these actions for the draft in
question.

To date, however, working group chairs have tended to use ad-hoc and
phrasing for working group adoption call and working group last call
announcements, and to indicate the results of such calls, with different
phrasing being used for different drafts and in different working groups.
This is problematic, because such phrasing:

* might not clearly and accurately describe the process implications of the
  action (adoption, last call) being undertaken, and might not link to the
  relevant process documents for details;

* might not clearly describe the IPR implications of the action; and

* might not clearly describe how decisions are made, how responses should
  be submitted, deadlines, etc.

It is suggested that the operation of the IETF will be improved if working
group chairs use consistent phrasing, that has been previously agreed to
accurately describe the process they are following and the implications of
that process, to describe their activities.

The IESG recently partially recognised this issue, and requested that
automated emails be added, as an option, to the Datatracker to describe the
IPR implications of working group adoption and last call, but the suggested
wording does not address the other concerns.

# Consistent Phrasing for Adoption and Last Call Notices

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT",
"SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and
"OPTIONAL" in this document are to be interpreted as described in BCP 14
{{RFC2119}} {{RFC8174}} when, and only when, they appear in all capitals,
as shown here.


The IETF needs to define consistent phrasing that working group chairs
SHOULD use when making working group adoption calls and working last call
announcements. This phrasing needs to be checked for consistency with the
relevant RFCs and must indicate the action being taken and the possible
outcomes of that action, what response is expected from participants, how
that response should be made, the deadline for responses, and the authority
under which the action is taken (with links to relevant process documents).


The IETF also needs to define consistent phrasing that working group chairs
SHOULD use when concluding a call for adoption or working group last call.

For a call for adoption, that phrasing must be clear whether the decision
was to adopt the document in question, whether the decision was to decline
to adopt the document (and, if so, under what conditions, if any, that
decision may be revisited), or whether the decision was deferred (and, if
so, why it was not possible to make a decision and what must happen before
a decision can be made).

For a working group last call, it must be clear whether the decision was
to forward the document to the IESG for consideration as-is, whether the
decision was to conditionally forward the document to the IESG for
consideration once some set of conditions have been met; whether the
decision was to not sent the document to the IESG (and, if so, under what
conditions the decision might be revisited); or whether the last call is
being extended (and if so, for what reason, and until what deadline).

For both adoption and last call, the phrasing must be clear about what
decision was made, why that decision was made and under what authority and
following what process, what are the next steps to be taken, and what to do
if there is disagreement.


This memo does not attempt to define such consistent wording at this time.
Rather, it is a call for input on whether such wording is a good idea in
principle. If there is such agreement, appropriate phrasing can be
prepared, and checked with the IESG and Counsel, and confirmed by IETF
consensus.


# Security Considerations

This document has no direct implications for Internet security.


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
