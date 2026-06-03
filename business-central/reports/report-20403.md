---
title: Quality Management - Non-Conformance Report (report)
description: Document a failed or non-conforming quality inspection with full test results, item tracking, and inspector and director sign-off.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_20403_Primary
ms.date: 2026-06-03
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-06-03
ai.usage: ai-assisted
---

# Quality Management - Non-Conformance Report (report)

The **Quality Management - Non-Conformance Report** report prints a structured non-conformance certificate for a finished quality inspection, including the inspected item and tracking details, the inspection template and sequence, each test field with its entered value and result condition, and signature blocks for the quality inspector and director.

You can filter the report by source item number, source variant code, source lot, serial and package numbers, source document number, inspection number, re-inspection number, and template code on the header, and by test code on the inspection lines so you can produce a non-conformance report for a single inspection, a re-inspection round, or a specific set of tests.

## Use cases

[!INCLUDE [report-20403-scenario](../includes/report-20403-scenario-include.md)]

Quality inspectors and QA managers can use the report to:

* Issue a formal non-conformance report (NCR) for an inspection that failed against its template.
* Show the entered measurements, result codes, and promoted condition results for each test field.
* Capture who finished the inspection, when it was completed, and the inspector and director sign-off lines.

Compliance and customer-facing teams can use the report to:

* Share documented evidence of non-conformance with customers, suppliers, or auditors.
* Trace a non-conformance back to the exact item, variant, lot, serial, or package involved.
* Reference the re-inspection sequence and result description when following up with corrective actions (CAR).

## Try the report

Try the report here: [Quality Management - Non-Conformance Report](https://businesscentral.dynamics.com?report=20403)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Quality reports](../quality-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
