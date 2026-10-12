# Computational Dialectic Analysis of the Declaration Narrative

Under computational dialectic (CD), the relevant question is not whether a passage sounds persuasive, but what propositions it actually asserts, what premises support them, and what would defeat or qualify each conclusion. Applied to the passage at issue, CD exposes a structure in which propositions of very different evidentiary weight are compressed into a single narrative and then treated as though they carried equal evidentiary status.

## 1. The propositions are not equivalent in kind

The narrative can be decomposed into roughly thirteen propositions. Some are potentially observable events (he emailed; he contacted family members; he called and emailed repeatedly). Others are interpretations layered onto those events (the statement "you will be sorry" constituted a threat; the contact was unwanted). Others attribute mental state (he lied; he intended to make the recipient believe she was at fault). Still others are evaluative or legal conclusions (the conduct was "emotionally abusive and manipulative"; the legal threats were "frivolous").

Grammatically, all of these are presented in the same simple subject-predicate form — "He emailed," "He lied," "He threatened" — which gives them equal rhetorical weight. Logically, they require entirely different evidentiary foundations. "He emailed me" can be established directly from the email. "He lied" requires establishing both falsity and knowledge. "He intended to make me believe X" requires evidence of mental state. "His conduct was abusive" and "the threats were frivolous" require independent evaluative or legal determinations. CD calls this an **epistemic leveling effect**: syntax that treats unequal claims as equivalent factual units.

## 2. The inferential bridges are missing

Each transition from a factual proposition to an interpretive or evaluative one requires a premise the passage never states — a textbook enthymeme:

- *He threatened legal action* → *the threat was frivolous* requires a premise about the actual legal basis for the threat, which is never supplied.
- *He made statements the speaker believes were false* → *he intentionally lied* requires evidence of knowledge, not just falsity.
- *He intended to mislead her* → *his conduct was emotionally abusive/manipulative* is a further, independent evaluative leap.

None of these transitions is automatically licensed by the proposition before it. CD requires the missing premise to be made explicit and tested, rather than allowed to disappear inside the narrative.

## 3. Repetition is rhetorical accumulation, not evidentiary accumulation

The passage relies heavily on frequency and pattern language: "repeatedly," "similar manner," "also," "numerous times," "repeated unwanted contact." Grammatical aspect reinforces this — perfect and past-perfect constructions ("he has repeatedly contacted," "he has also...") convert discrete, individually uncertain events into the appearance of an already-established history.

But six restatements of one grievance are not six independent incidents. Stripped to their semantic core, the six sentences all assert the same claim — that repeated contact and threats, especially legal ones, are being used to intimidate and control the speaker — with only the surrounding detail (an email deadline, contact with family, contact with friends at work, a lie, a call, an email) varying each time. The effect is to project a rich, multi-incident pattern in the *subject matter*, while the actual repeated pattern is in the *language*: the same sentence template, the same core claim, and a small fixed set of charged keywords ("repeated," "threatening," "frivolous," "emotionally abusive") redeployed with new decoration each time.

This matters because CD asks whether repetition increases evidentiary strength or merely increases the number of assertions. A genuine pattern requires independently substantiated, sufficiently similar events. A templated narrative instead manufactures the appearance of accumulation without adding independent evidentiary weight — and it is effective against both human and automated review precisely because it produces the surface features (specificity, frequency markers, labeled legal elements) that reviewers are trained, or a classifier is tuned, to credit, without anyone asking whether the underlying incidents are actually distinct.

## 4. The agent/recipient frame is structurally one-sided

Every clause places the same person in the agent position and the other party in the object/recipient position: he emailed, he contacted, he lied, he threatened, he called. This doesn't make the underlying characterization false, but it means the narrative's grammar consistently allocates agency to one side regardless of the evidentiary status of any given clause — reinforcing the leveling effect described above rather than testing it.

## 5. The compounding risk in institutional reuse

Once this kind of narrative is incorporated into a petition and a court order is issued referencing it, later documents that cite the order ("consistent with the allegations in the order") are not supplying independent corroboration — they are citing the same original, unexamined characterization. CD distinguishes **independent premises** from **institutional repetitions of the same premise**: ten references to a proposition across a record do not equal ten independent grounds for it. If the original representation never distinguished allegation from established fact, every downstream document that treats it as fact inherits that defect.

## 6. Reconstruction

A CD-compliant reconstruction separates the narrative into tiers, rather than a single bundled account:

- **Facts:** an email was sent; it stated a deadline; it referenced legal action; other people were contacted; additional communications followed.
- **Interpretations:** the statement constituted a threat; the contact was unwanted; the communications were intended to pressure the recipient.
- **Mental-state claims:** he knew the statements were false; he intended to cause a particular belief; he intended to manipulate or control.
- **Evaluative conclusions:** the conduct was abusive; the conduct was manipulative; the legal threats were frivolous.

This produces an argument graph rather than a narrative bundle, so each transition can be tested against the evidence that actually supports it.

## 7. A second instance of the same defect: conclusion without factual predicate

The same CD framework applies to a different passage — one arguing for ex parte TRO relief under Rule 65:

1. Rule 65 has stringent restrictions on ex parte TROs.
2. Those restrictions reflect opposition to action without notice and hearing.
3. Ex parte TROs should serve the purpose of preserving the status quo and preventing irreparable harm until a hearing.

Here the defect is not epistemic leveling — it's a missing symbolic element entirely. The passage supplies a conclusion and its purpose ("preserving the status quo," "preventing irreparable harm") but supplies no factual object for that conclusion to operate on. In notation: let *Y* = specific facts and *X* = conclusion/purpose. The passage gives *X* but no *Y* — not insufficient facts, not unverified facts, not irrelevant facts, but no facts at all.

The strictly textual statement is: the passage asserts the legal result and its purpose, but contains no particular facts from which that result or purpose could be derived.

This is a distinct failure mode from the declaration narrative above (Sections 1–6), where every clause corresponds to *some* factual or quasi-factual assertion, and the defect is that those assertions carry unequal evidentiary weight while being presented as equivalent. Here, the defect is prior to that: there is no factual assertion at all for CD to test the weight of. The two passages illustrate opposite failure modes of the same underlying discipline — one compresses facts and conclusions into a single undifferentiated form, the other omits the facts and leaves only the conclusion.

## Core takeaway

The defect in this kind of passage is not that any individual proposition is necessarily false. It is that propositions of different epistemic status — descriptive, interpretive, mental-state, and evaluative — are compressed into a single grammatical form and then treated as though they carried the same evidentiary weight. That is a more precise and more defensible claim than simply calling the passage "biased," because it identifies exactly where the inferential gaps sit and what would be needed to close them.
