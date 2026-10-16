# Changelog

## 0.2.3 - 2026-10-16

- Preserve the complete 0.2.2 SDK source, including billet due-date updates, in a new patch release with tracked release metadata.

## 0.2.2

- Add `BillingBilletUpdateRequest` and `Client::billing_charge_update_billet` to update an unpaid boleto's due date through `PUT /v1/charge/{id}/billet`.
