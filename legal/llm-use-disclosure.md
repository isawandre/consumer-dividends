# Language Model Use and Transparency Disclosure

**Consumer Dividends Holding Corp**
Effective date: June 14, 2026
Last updated: June 14, 2026

This disclosure explains how our products use language models, what data is processed, and what the outputs are and are not. We publish it so that customers, their clients, and regulators can understand our posture in one document. Hand this to your compliance team, your broker, or your counsel.

## 1. What our products do

Our products use large language models combined with deterministic scoring and templating logic to convert structured inputs (case facts, property details) into structured outputs (risk reports, listing materials). The user provides the inputs. The system produces the output. A human reviews and decides what to do with it.

**Numidian** is a risk inventory and scoring tool used by HR consultants, employment attorneys, and HR managers. It scores organizational exposure across five dimensions using EEOC charge data, federal court timing patterns, and a state-by-state law matrix. A language model is used to express the report in readable prose. The scores come from the scoring framework, not the model.

**ListingPro** is a listing operations platform used by real estate agents, brokers, and property managers. It generates MLS-ready descriptions, social copy, deal analysis, and client packets from property details. A language model produces the marketing prose. The deal analysis numbers come from deterministic calculations on the inputs you provide, not from the model.

## 2. What our products do not do

**Our products do not make decisions about individuals.**

Numidian does not decide whether to hire, fire, promote, discipline, or take any other employment action against any person. It produces a risk score for an advisor to read. The decision sits with the employer.

ListingPro does not screen tenants, evaluate buyers, set prices, or target audiences. It produces listing copy and supporting materials for a licensed agent to review.

Neither product is an "automated employment-related decision technology" under the Connecticut Artificial Intelligence Responsibility and Transparency Act (Public Act 26-15, Section 31-57aa et seq., applying to systems deployed on or after October 1, 2027). The CART Act covers technology that processes personal data and produces output that is a "substantial factor" in an employment-related decision about an individual. Numidian's output is a structured risk inventory for the firm's own analysis. It does not direct or materially influence a decision about any individual employee.

Neither product is a "covered automated decision-making technology" under the Colorado Automated Decision-Making Technology Act (SB 26-189, effective January 1, 2027) for the same reason. The decision-maker is the employer. Numidian informs the analysis of the employer's advisors.

If a deployer of our product chooses to use the output as a substantial factor in an employment-related or consequential decision about an individual, that deployer is responsible for compliance with the laws that apply to that decision, including any disclosure, notice, bias audit, or impact assessment obligations.

## 3. What data is sent to the language model

When you submit inputs to Numidian or ListingPro, those inputs are sent to our language model provider only for the duration needed to generate your output. The provider does not retain those inputs for training purposes under our agreement with them.

Specifically:
- Numidian sends the structured case facts you enter (action, protected activity, timing, documentation status, state, company size, comparator detail, protected class).
- ListingPro sends the property details you enter (address, features, condition, price information, listing context).

Neither product sends payment information, account credentials, or content from other users to the model.

## 4. Whether your data trains models

No. We do not use the content of your Numidian inputs, ListingPro inputs, or any reports generated for you to train, fine-tune, or otherwise improve any language model. Your case facts and property details stay yours.

Aggregate, non-identifying usage statistics (such as how many reports were generated in a month) may inform product improvements. The content of your inputs is not used for this.

## 5. How outputs are produced

Numidian and ListingPro both combine deterministic logic with language model generation:

- **Numidian** uses a fixed scoring framework. Each of the 18 input fields feeds into one of five scoring dimensions through documented rules. A jurisdiction multiplier is applied based on the state entered. The language model is used to express the final report in readable prose. The scores themselves come from the framework, not the model.

- **ListingPro** uses templates and structured prompts to convert property details into marketing copy. The language model generates the prose. The deal analysis numbers come from deterministic calculations on the inputs you provide, not from the model.

In both products, the same inputs produce substantially similar outputs across runs. We are not generating creative content where the model decides on substance. The model is generating text from a structured frame.

## 6. Known limitations

- Language models can produce errors. Review every output before relying on it.
- Language models can produce content that is plausible-sounding but wrong about facts not provided in the inputs. Do not assume any factual content beyond what you input is accurate.
- Language models can produce text that, in a real estate marketing context, may raise fair housing concerns. ListingPro includes a fair housing screen on every output, but you and your broker remain responsible for the final review.
- Language models cannot replace professional judgment. Numidian outputs are not legal advice. ListingPro outputs are not approved marketing.

## 7. Bias and fairness

We have built specific scoring frameworks and review processes intended to reduce the risk of biased outputs:

**Numidian** scores against documented data sources (EEOC charge data, federal court timing patterns, 15-state law matrix). The scoring framework is fixed. The same inputs produce the same scores. The protected class field is used to apply the legal framework appropriate to the situation, not to differentiate scoring against any individual.

**ListingPro** runs every output through a fair housing language screen before delivery. The screen checks for terms HUD has identified as discriminatory, plus terms flagged by major MLS systems. Outputs that contain flagged language are revised before delivery or returned with a warning for the user to review.

We do not represent these measures as a complete or certified bias audit. We document them so that you and your counsel can evaluate them. Where regulators require formal anti-bias testing or impact assessments for the use of an automated decision tool, those obligations sit with the deployer in their specific deployment.

## 8. Transparency to end users

Because our products do not make decisions about individuals and do not interact directly with employees, applicants, tenants, or buyers, the disclosure obligations that apply to consumer-facing or employee-facing automated decision tools do not directly apply to us. The Connecticut CART Act notice requirements at Section 31-57aa (effective for systems deployed on or after October 1, 2027) apply to deployers using automated decision technology in employment contexts. We are not such a deployer.

We recommend that customers using our products document their use of the products in their own internal records and, where the output will be used in a way that touches an employee, applicant, tenant, or buyer, consider whether their own jurisdiction requires them to disclose that an automated tool informed the work.

## 9. Where the model runs

Our language model provider runs the model in their own infrastructure in the United States. Your inputs are sent over an encrypted connection (TLS). The provider's terms with us prohibit use of your inputs for training.

For customers who require local-only deployment with no third-party model provider, contact us about our IP Prospectus tracks, which include locally deployed Llama-based models running via Ollama with no cloud dependency.

## 10. Your rights and how to exercise them

You have the right to:

- Know what inputs you have submitted (kept according to the retention rules in our Privacy Policy).
- Request a copy or deletion of your inputs and outputs.
- Object to specific processing.
- Ask questions about how a specific output was produced.

Email support@consumerdividends.com from the address associated with your account.

## 11. Updates

We update this disclosure when the law changes, when we add a new product, or when our practices change. The "Last updated" date at the top reflects the most recent change.

## 12. Contact

support@consumerdividends.com
Consumer Dividends Holding Corp, Pāhoa, Hawaii, United States.
