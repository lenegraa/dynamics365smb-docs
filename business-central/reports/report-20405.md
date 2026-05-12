---
title: Quality Management - General Purpose Inspection Report (report)
description: Print a general purpose inspection report that documents test results, item tracking, and sign-offs for a completed quality inspection.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_20405_Primary
ms.date: 2026-05-12
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-05-12
ai.usage: ai-assisted
---

# Quality Management - General Purpose Inspection Report (report)

The **Quality Management - General Purpose Inspection Report** report prints a structured inspection document that includes company and contact details, the inspected item with variant and tracking information, the inspection sequence and result, each test field with its entered value and last-modified user, and signature blocks for the inspector and approver.

You can filter the report by source item number, source variant code, source lot number, source serial number, source package number, source document number, inspection number, re-inspection number, and template code on the header, and by test code on the lines, so you can produce a certificate for a specific lot, serial, or inspection iteration.

## Use cases

[!INCLUDE [report-20405-scenario](../includes/report-20405-scenario-include.md)]

Quality inspectors can use the report to:

* Print the finished inspection for a specific lot or serial number to attach to a shipment.
* Produce a re-inspection document by filtering on the re-inspection number to show the latest results.
* Capture entered test values, results, and the user and timestamp of each measurement for the inspection record.,Quality managers and approvers can use the report to:

* Review a completed inspection with signature blocks for the inspector and the configured certificate approver before release.
* Filter by template code to print all inspections that used a given test template for audit review.
* Share a consistent certificate of analysis layout that includes company information, contact details, and promoted result conditions.,Customer service and shipping teams can use the report to:

* Generate a certificate of analysis to send to customers who request inspection evidence with their order.
* Filter by source document number to print the inspection tied to a specific sales or warehouse document.
* Include item description, variant, lot, and serial information so the document matches what the customer receives.

## Try the report

Try the report here: [Quality Management - General Purpose Inspection Report](https://businesscentral.dynamics.com?report=20405)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Quality reports](../quality-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
