# Proqure: from stakeholder scenarios to platform requirements

**Context:** Proqure Retail Networks, a Nigerian food supply business connecting producers, procurement teams, and buyers. The source materials include a seed-stage pitch deck, a stakeholder scenario and feature specification, and a July–September 2022 segment plan.

**My role:** Strategy lead on the Proqure venture. This case describes the business framing and requirements work represented in the source documents; it does not claim that every proposed digital feature was built.

## The decision

A food marketplace must solve several problems at once. Farmers need dependable routes to buyers and a way to keep stock and prices current. Business buyers need quality, predictable supply, and usable transaction records. The operations team needs to match product availability, grade, price, transport cost, and delivery timing without taking avoidable inventory or payment risk.

The question was: **Which capabilities should be specified first so that the service could be operated and tested before adding more self-service features?**

## Evidence and analysis

The stakeholder document uses concrete situations rather than a feature wishlist. It describes farmers who update quantities after local sales, procurement officers who need repeat orders and transaction exports, a back-office buyer comparing supplier prices and transport costs, and finance staff concerned with payment and delivery evidence. The investor deck identifies the business's intended matching criteria as product grade, price, distance and transport cost, lead time, and supplier rating.

I read these as a set of linked operating constraints:

1. **Availability must be trustworthy.** A listing that is stale after a farmer sells locally can turn a seemingly profitable order into an expensive replacement purchase.
2. **Price must include fulfilment.** A cheap supplier is not necessarily the best option if distance, handling, or spoilage increases delivered cost.
3. **Control precedes automation.** Staff need to verify suppliers, update stock and prices, reconcile payments, and retain delivery evidence before a fully self-service marketplace is dependable.
4. **Different buyers need different workflows.** A household checkout, a recurring business order, and a credit-enabled account carry different service and payment requirements.

## Requirements and prioritization

The feature specification explicitly labels several back-office capabilities **MVP**: staff-assisted farmer registration, produce details and stock levels, transport-rate management, vendor transaction visibility, price updates, payment management, and delivery confirmation. It places farmer self-registration and scheduling in later iterations, with USSD registration later still. This sequence favors operational control first and broader self-service after the core records work.

The July–September 2022 plan then separates micro-SME and enterprise segments by need, supply approach, and resource requirement. Its revenue and gross-margin numbers are **targets**, not reported results; the important analytical point is that payment flexibility, supply consistency, and invoice support require different operating choices by segment.

## Recommended decision rule

For each proposed feature, test: (a) whose problem it solves; (b) whether it changes a critical order outcome; (c) what data and human control it requires; (d) its effect on delivered cost and payment risk; and (e) whether the team can verify it reliably. A useful supplier recommendation should state its stock freshness, product grade, total landed cost, lead time, and the uncertainty in each input before naming a preferred option.

## Result and limits

The documented output was a scenario-based requirements set with actors and release stages, plus a segment-level operating plan. The materials reviewed here do **not** verify the launch status of the listed software features or establish that the 2022 commercial targets were achieved.

This case is relevant to AI evaluation because the same discipline applies when judging an AI response: check whether it respected the user's context, relied on supported facts, surfaced missing information, and avoided a confident recommendation from incomplete cost data. That is a transfer of method, **not** a claim that this Proqure work was an AI evaluation project.

*Source basis: “Proqure Scenarios”; “Proqure Pitch Deck 011021”; “Proqure Q3 Strat.” These historical source files informed this summary and are not reproduced here.*
