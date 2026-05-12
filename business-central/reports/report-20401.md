---
title: Quality Inspection - Certificate of Analysis (report)
description: Generate a signed certificate of analysis that documents inspection results, test values, and approvals for a finished quality inspection.
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

The **Quality Inspection - Certificate of Analysis** report prints a formal certificate for a finished quality inspection, listing the inspected item, item tracking details, each test with its value and result, prompted result conditions, and the signatures of the inspector who finished the inspection and the approver. It includes company contact details, the inspection number and re-inspection sequence, status, overall result, and the date and user who finished the inspection.

You can filter the report by source item number, source variant code, source lot number, source serial number, source package number, source document number, inspection number, re-inspection number, and template code, so you can produce a certificate for a specific shipment, batch, or tracked unit and limit the printed lines to selected test codes.

## Use cases

[!INCLUDE [report-20401-scenario](../includes/report-20401-scenario-include.md)]

Quality managers and inspectors can use the report to:

* Issue a certificate of analysis for a finished inspection to confirm that a lot or serial meets specification.
* Reprint a certificate for a specific re-inspection sequence when a sample was retested.
* Provide signed documentation of who finished the inspection and who approved the result.,Sales and customer service teams can use the report to:

* Send a certificate to a customer together with a shipment to evidence quality of the delivered item.
* Respond to customer requests for proof of testing on a specific lot, serial, or package number.
* Attach the certificate to a sales document by filtering on the source document number.,Compliance and audit teams can use the report to:

* Archive a record of test results, conditions, and approvals for regulated products.
* Demonstrate during audits that inspections were finished, reviewed, and signed off.
* Trace tested values back to the inspector and the date the inspection was finished.

## Try the report

Try the report here: [Quality Inspection - Certificate of Analysis](https://businesscentral.dynamics.com?report=20401)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Built-in key finance reports](../finance-reports.md)
[Ad-hoc analysis on finance data](../ad-hoc-analysis-finance.md)
[Financial analytics overview](../bi.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
