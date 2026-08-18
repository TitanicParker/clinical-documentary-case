# Clinical Documentary Case

This repository contains a documentary clinical analysis built directly from the assembled clinical record.

## Evidential architecture

The repository is organised as a traceable chain:

**Clinical record -> Facts -> Tensions -> Propositions -> Expert Questions -> Clinical Argument**

Each analytical layer should be read as derived from the layer before it. The purpose is to preserve the distinction between what the documents establish and what requires expert clinical interpretation.

## Reading order

1. `complete-record.md`  
   Canonical assembled clinical record with stable `CLIN-` line identifiers.

2. `FACTS.md`  
   Documentary facts stated as discrete propositions and anchored to `CLIN-` references.

3. `TENSIONS.md`  
   Material tensions arising from the factual record, including competing or unresolved clinical explanations.

4. `PROPOSITIONS.md`  
   Clinical propositions derived from those tensions without treating expert-dependent conclusions as already proved.

5. `EXPERT-QUESTIONS.md`  
   The questions on which specialist neurological, biomechanical or podiatric opinion is required.

6. `CLINICAL-ARGUMENT.md`  
   The integrated documentary case theory. It identifies what the record establishes, what remains unresolved, and where expert evidence becomes decisive.

## Core method

The repository is evidence-first.

The source documents are not subordinated to a predetermined allegation. The analytical sequence is intended to show how the case develops from the record itself:

- documentary fact before inference;
- tension before conclusion;
- proposition before expert question;
- expert opinion before any ultimate clinical or legal conclusion.

The central clinical issue is the longitudinal relationship between Parkinsonism, structural foot pathology, pain, gait, treatment response and dopaminergic treatment strategy.

## Scope

This repository is confined to the documentary clinical case.

It does not attempt to determine negligence, legal liability, regulatory breach or data-protection issues. Where the documentary record cannot resolve causation, standard of care, treatment counterfactuals or mechanism, those matters are reserved for expert opinion.
