---
title: TTM Week 4 Notes
date: 2023-08-21 12:00:00 -500
categories: [notes]
tags: [ttm]
resource: true
---

## Lecture 2: AI
 - AI: technique enabling machines to mimic human intelligence
 - ML: statistical methods used to create predictive models with (supervised) and without (unsupervised) human intervention
 - DL: ML method to process data in a similar way that human brains do via neural networks
 
The FDA classifies medical software as "locked" if all rules are hard coded into the program and "adaptive" if the input-output relationship is adaptive (i.e. via machine learning).

The data used to train AI models include EHR, wearables, and data originally gathered for other purposes. AI models can provide classifications such as **risk stratification** or **diagnostics**. They can also provide continuous outputs such as **risk probabilities** or **estimated likelihoods**.

### Ethical Issues

Training dataset quality (clean, complete, comprehensive, credible. relevant, and calculable data) determines utility and accuracy of end model. Furthermore, patients may not know their data is being included in model training or that models are being used in their treatment.

Model explainability is very important for physician and patient trust in models.

Major sources of bias include training data, context specificity and model choice for validation, and real world implementation.

We also contribute to bias as users. Algorithmic appreciation or aversion and social/cultural norms can affect how we prompt and interpret AI tools.

## Lecture 5: Funding Systems in US Healthcare

### Payers
 - Patients: Self-pay
    - No money = No care (with the exception of emergency care under EMTALA)
 - Government
    - Model 1: Government owned (VA, IHS... Physicians are government employees)
    - Model 2: Government Insurance (Medicare/Medicaid... Government reimburses private physicians/systems for services)

### Medicare and Medicaid

Medicare is largely a program for the elderly (65+) run through CMS (federal government). It also provides coverage for end-stage renal disease and ALS for legal reasons. However, this has been partially privatized via government subcontracting out to private insurasnce companies.

Medicaid and CHIP (Children's Healthcare Insurance Program) are state-federal partnerships that are dually funded. Eligibility is determined on a state level but generally provides coverage for the (very) poor. 

Texas did not choose to expand medicaid with the ACA (to all individuals within 138% of federal poverty line). Thus, in Texas you do not qualify on income alone - you must also be pregnant, blind, disabled, have a dependent, or > 65yo.

The monthly income levels in texas are startlingly low:

![Dependents](/img/Medicaid_texas.png)

### Private Insurance

For in-network and on-formulary medications, you pay your **premium** every month to have insurance. You pay the **allowed amount** for all your care until you reach your **deductible**.  Then you pay either **copay** (always the same for each service) or **coinsurance** (percentage of charge for service) until you reach your **out of pocket maximum**. Then the insurance pays for everything.

If you are out-of-network you may be charged additional amounts regardless of what you may have paid already due to differences between negotiated and actual charges

 - Model 1 - Employment Benefit
   - Employers pay for a portion (often large portion) of insurance policies purchased via the private market.
 - Model 2 - Government Marketplace (Healthcare.gov)

#### Fee for service

- RVU (relative value unit) - standard measure of value to compare different types of healthcare
- CPT - code assigned to each healthcare service with corresponding amount of RVUs.

These are both set by the CMS and used by most private insurers to value services. Then insurance companies negotiate with hospitals or private systems to set the end price charged for service.

_How do payments reach physicians?_
 - Capitation: you get a set amount of money to care for a specific patient/condition, regardless of what course the illness takes. 
 - Bundled payments: payment to team of healthcare professionals to achieve patient centered goals regardless of specific treatments and interventions.

### Maximizing Value

Value is defined as the _quality_ (outcomes and patient experience) of service divided by the _cost_ (both direct and indirect). 

Quality is measured via:
1. Outcomes (control of BP...)
2. Process (patient cancer screenings...)
3. Structure (staff to patient ratios, EHR...)
4. Patient reported (satisfaction...)
5. Resource Management (antibiotic stewardship...)

### Structuring Payment Models

 - Accountable care organizations (ACOs) are "neighborhoods" of care including hospitals, pharmacies, clinics, services, and payments that handle everything concerning the patient and thus are self-motivated to provide good care.
 - Patient-centered medical home is an attempt to center as many aspects of care within one clinic to keep you healthy.
 - Government organized healthcare (VA, IHS) is the broadest solution and spreads cost among the entire population. 

 ## Lecture 6: Imperative to think

 Thought errors cause significant morbidity and mortality. Vulnerable populations in particular have increased risk of cognitive bias
  - Metacognition is key to reducing thought errors - understanding how we think and what our biases are allow us to fix errors in the thought process when given post-hoc data
  - High risk situations require a _cognitive pause_
      - Am I confident?
      - What are the facts?
      - Is there additional data to consider?
      - Have I planned for uncertainty

