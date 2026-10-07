# Creditor worksheet reading guide

This public workbook is an anonymized copy of the **standalone V6 creditor view** delivered in September 2026. It contains the original two tabs and retains numerical inputs and 243 formulas. Identifying title and source labels were replaced. The source file was a frozen snapshot, so this copy is also a snapshot; it is not the full integrated model and does not refresh from that private file.

## How to review

1. Open **Creditor Summary** for the annual cash/funding bridge, principal drawn and repaid, outstanding capitalised interest and illustrative cash capacity.
2. Open **Monthly Cash Bridge** for all 38 months, September 2026–October 2029.
3. Read the formula columns: **I** cash sources plus opening cash; **N** cash before senior principal; **P** closing cash; **R** variance versus the V6 funding cash reference; **W** variance versus the V6 cash-flow reference.
4. Trace first, middle and final periods. Opening cash rolls from the preceding period; receipts and funding add cash; project spend, supplier settlements and senior principal consume it.
5. Review senior closing debt and capitalised interest independently of principal payments. The NGN 443.7m residual interest is an unresolved settlement obligation, not a zero debt balance.
6. A small input change can test the local arithmetic. Restore it afterwards: the V6 reference cash columns are frozen benchmarks and will not change alongside the inputs.

## Verification on the public copy

- Numeric inputs and every source formula were compared with the delivered standalone worksheet.
- Recalculated cached outputs agreed with source values within NGN 0.0000001m; text checks agreed exactly.
- The formula-error scan returned no matched errors.
- Workbook XML was checked for the removed project/sponsor/counterparty identifiers.

## Interpretation limits

Annual source values are forecasts. Supplier drawings are temporary timing bridges, not permanent funding. No cash payment of capitalised senior interest is scheduled in the snapshot. Closing cash after an illustrative interest payment assumes cash is available and no other obligations intervene. The model's tax basis requires professional validation.

**Source:** Standalone creditor cash flow and repayment view V6, submitted 25 September 2026. Original private filenames and correspondence are not published.
