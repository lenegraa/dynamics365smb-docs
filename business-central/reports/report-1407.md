---
title: Bank Account Statement (report)
description: Print a posted bank account statement with reconciled balances, statement lines, and outstanding bank transactions and checks.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1407_Primary
ms.date: 2026-05-13
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-05-13
ai.usage: ai-assisted
---

# Bank Account Statement (report)

The **Bank Account Statement** report shows the details of a posted bank account statement, including the statement date, balance last statement, statement ending balance, and the related G/L balance at the posting date. It lists each statement line with transaction date, value date, type, document number, description, applied entries, statement amount, and applied amount, and can include sections for outstanding bank transactions and outstanding checks so you can reconcile the statement balance to the bank account balance.

You can filter the report by **Bank Account No.** and **Statement No.** to select the posted statements to print, and use the **Print Outstanding Transactions** option on the request page to include lines for outstanding bank transactions and outstanding checks at the statement date.

## Use cases

[!INCLUDE [report-1407-scenario](../includes/report-1407-scenario-include.md)]

Controllers and finance teams can use the report to:

* Verify that the statement ending balance plus outstanding items reconciles to the bank account balance in the G/L.
* Document posted bank reconciliations for internal review and audit trails.
* Review outstanding bank transactions and outstanding checks that have not yet cleared at the statement date.

Accountants and bookkeepers can use the report to:

* Print a posted bank statement to compare statement lines with the bank's records.
* Check applied entries and applied amounts on each statement line to confirm matching against bank account ledger entries.
* Archive a copy of each posted statement together with its supporting outstanding items.

External auditors can use the report to:

* Trace the statement ending balance to the related G/L balance at the posting date.
* Review outstanding checks and transactions to validate cut-off and completeness of bank reconciliations.
* Use the filtered output by bank account and statement number as supporting documentation.

## Try the report

Try the report here: [Bank Account Statement](https://businesscentral.dynamics.com?report=1407)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Bank reports](../bank-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
