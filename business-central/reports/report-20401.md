---
title: Quality Inspection - Certificate of Analysis (report)
description: Print a signed certificate of analysis for a finished quality inspection, showing tests, results, and approver details.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_20401_Primary
ms.date: 2026-05-12
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-05-12
ai.usage: ai-assisted
---

# Quality Inspection - Certificate of Analysis (report)

The **Quality Inspection - Certificate of Analysis** report prints a customer- or audit-ready document for a finished inspection. It shows company and contact information, the inspected item and its tracking details (lot, serial, package), each test with its value and result, and signature blocks for the finishing inspector and the approver.

You can filter the report by source item number, variant code, lot number, serial number, package number, source document number, inspection number, re-inspection number, and template code, so you can target a single inspection or a batch of inspections for the same item, lot, or document.

## Use cases

[!INCLUDE [report-20401-scenario](../includes/report-20401-scenario-include.md)]

Quality managers and inspectors can use the report to:

* Issue a signed certificate that documents test values and pass/fail results for a finished inspection.
* Reprint a re-inspection certificate when an item is retested, using the re-inspection number filter.
* Verify which inspector finished each inspection and which approver signed off.,Sales and customer service teams can use the report to:

* Send customers the certificate of analysis that accompanies a shipped lot or serial number.
* Filter by source document number to produce certificates tied to a specific sales order or shipment.
* Provide proof of inspection results for items subject to regulatory or contractual requirements.,Compliance and audit teams can use the report to:

* Archive certificates that show test conditions, result descriptions, and approver names for traceability.
* Retrieve inspection records by lot, serial, or package number to support audits and complaints.
* Confirm that each inspection has a documented finisher and approver before release.

## Try the report

Try the report here: [Quality Inspection - Certificate of Analysis](https://businesscentral.dynamics.com?report=20401)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Quality reports](../quality-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
