---
title: Bank Account Statement (report)
description: Print a posted bank account statement with statement balances, G/L balances, and outstanding transactions for reconciliation review and archiving.
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

The **Bank Account Statement** report shows the details of a posted bank account statement, including the statement date, balance last statement, statement ending balance, and the corresponding G/L balance at the statement date. It lists each statement line with transaction date, value date, type, document number, description, applied entries, statement amount, and applied amount. Optionally, the report includes sections for outstanding bank transactions and outstanding checks that were not yet cleared at the time of posting.

You can filter the report by **Bank Account No.** and **Statement No.** to select which posted statements to print, and use the **Print Outstanding Transactions** option on the request page to include outstanding bank transactions and outstanding checks in the output.

## Use cases

[!INCLUDE [report-1407-scenario](../includes/report-1407-scenario-include.md)]

Controllers and finance teams can use the report to:

* Document a posted bank reconciliation for the audit file by printing the statement with balances and applied entries.
* Compare the statement ending balance with the G/L balance at the statement date to confirm that the bank account is reconciled.
* Review outstanding bank transactions and outstanding checks that affect the adjusted bank account balance.

Accountants and bookkeepers can use the report to:

* Print a single statement to share with auditors or management as evidence of the period's reconciliation.
* Verify that each statement line is correctly matched to the bank account ledger entries through the applied amount and applied entries columns.
* Identify outstanding payments and deposits that need follow-up before the next statement is posted.

## Try the report

Try the report here: [Bank Account Statement](https://businesscentral.dynamics.com?report=1407)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Bank reports](../bank-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
