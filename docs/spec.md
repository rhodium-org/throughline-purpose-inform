# Purpose — Inform — throughline source

This document is **generated from the graph** by `tl docs`; `tl docs --check` gates
it in CI. The prose headings are hand-owned — everything between `tl:*` markers is
injected from the YAML items, so the published spec can never drift from the graph.

This source is the **genre / purpose axis** for one purpose: **inform**. It governs
what the writing is *for* — conveying facts so the reader knows, with no action
demanded — not readability, spelling, punctuation, tone/register, medium or brand
voice, each of which is its own throughline source. Purpose variants are mutually
exclusive: **inform**, **instruct** and **persuade** are sibling sources and a
consumer composes exactly one under the `purpose` namespace. Every principle is a
`user_requirement`; every rule is a `system_requirement` that `implements` its
principle. The throughline UIDs are this source's own and immutable — a consumer cites
a rule as `purpose:SR-0001`.

It carries
<!-- tl:count type == 'user_requirement' -->
5
<!-- tl:end --> principles and
<!-- tl:count type == 'system_requirement' -->
10
<!-- tl:end --> rules.

## Purpose

<!-- tl:item INT-0001 -->
**INT-0001 — Text informs the reader accurately and completely** — `intent`, status `approved`

> Informing means conveying facts or state so the reader is accurately and fully in the picture, with no action demanded of them. It suits notices, explanations, status updates and reference material, where the reader needs to know rather than to do. This axis governs the communicative purpose — what to include and how to frame it — not readability, spelling, punctuation or register, each of which is a separate source. Purpose variants are mutually exclusive: a consumer composes exactly one of the inform, instruct or persuade sibling sources.

**source_ref**: TBS Purpose — Inform
<!-- tl:end -->

## 1. State only what can be substantiated

<!-- tl:item UR-0001 -->
**UR-0001 — State only what can be substantiated** — `user_requirement`, status `approved`

> Present verified facts and match certainty to the evidence.

*Derives from:* INT-0001

**source_ref**: TBS Purpose — Inform — Accuracy
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0001' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0001 | system_requirement | approved | State only facts you can substantiate |
| SR-0002 | system_requirement | approved | Match the claim to the strength of the evidence |
<!-- tl:end -->

## 2. Give the whole picture the reader needs

<!-- tl:item UR-0002 -->
**UR-0002 — Give the whole picture the reader needs** — `user_requirement`, status `approved`

> Cover the exceptions and limits, and mark the boundary of what is covered.

*Derives from:* INT-0001

**source_ref**: TBS Purpose — Inform — Completeness
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0002' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0003 | system_requirement | approved | Include the exceptions and limits, not only the general case |
| SR-0004 | system_requirement | approved | State what the content does not cover |
<!-- tl:end -->

## 3. Inform without persuading

<!-- tl:item UR-0003 -->
**UR-0003 — Inform without persuading** — `user_requirement`, status `approved`

> Present the facts and leave the reader free to draw their own conclusion.

*Derives from:* INT-0001

**source_ref**: TBS Purpose — Inform — Neutrality
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0003' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0005 | system_requirement | approved | Present facts without steering the reader |
| SR-0006 | system_requirement | approved | Give differing positions fairly |
<!-- tl:end -->

## 4. Show where the facts come from

<!-- tl:item UR-0004 -->
**UR-0004 — Show where the facts come from** — `user_requirement`, status `approved`

> Attribute claims and separate fact from interpretation.

*Derives from:* INT-0001

**source_ref**: TBS Purpose — Inform — Attribution and evidence
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0004' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0007 | system_requirement | approved | Attribute each non-obvious claim to its source |
| SR-0008 | system_requirement | approved | Distinguish established fact from interpretation |
<!-- tl:end -->

## 5. Make the information's time-validity explicit

<!-- tl:item UR-0005 -->
**UR-0005 — Make the information's time-validity explicit** — `user_requirement`, status `approved`

> Say what the information applies to and when it will change.

*Derives from:* INT-0001

**source_ref**: TBS Purpose — Inform — Currency
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0005' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0009 | system_requirement | approved | State the date the information applies to |
| SR-0010 | system_requirement | approved | Flag facts that will change and when they are next reviewed |
<!-- tl:end -->
