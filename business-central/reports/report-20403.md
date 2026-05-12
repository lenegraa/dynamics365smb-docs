---
title: Quality Management - Non-Conformance Report (report)
description: Document a failed quality inspection with item, tracking, test results, and sign-off details for review and corrective action.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_20403_Primary
ms.date: 2026-05-12
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-05-12
ai.usage: ai-assisted
---

# Quality Management - Non-Conformance Report (report)

The **Quality Management - Non-Conformance Report** report prints the details of a quality inspection that did not meet specification, including the inspected item, item tracking information, each test field with its entered value and result, the user who completed the inspection, and a signature block for the inspector and the quality director.

You can filter the report by source item number, source variant code, source lot number, source serial number, source package number, source document number, inspection number, re-inspection number, template code, and test code, so you can scope the output to a specific inspection, a particular lot or serial, or a single test line.

## Use cases

[!INCLUDE [report-20403-scenario](../includes/report-20403-scenario-include.md)]

Quality inspectors can use the report to:

* Issue a non-conformance report for an inspection that failed and attach it to the corrective action.
* Review the test fields, entered values, and conditions that caused the inspection to fail.
* Capture the date, inspector name, and signature line required to close out the inspection.

QA managers and quality directors can use the report to:

* Sign off non-conformance reports before they are sent to production or to the supplier.
* Trace a non-conformance back to the specific item, lot, serial, or source document involved.
* Compare results across re-inspections by filtering on inspection number and re-inspection number.

Production and operations teams can use the report to:

* Identify which lots or serial numbers are affected by a non-conformance and need to be quarantined or reworked.
* Use the documented test results to drive root-cause analysis and corrective actions.
* Share a formal record of the failed inspection with internal stakeholders or auditors.

## Try the report

Try the report here: [Quality Management - Non-Conformance Report](https://businesscentral.dynamics.com?report=20403)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Quality reports](../quality-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
