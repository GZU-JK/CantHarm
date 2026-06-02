# Datasheet For CantHarm

## Motivation

CantHarm supports evaluation of Cantonese harmful lexical forms under linked sense ambiguity and controlled canonical speech grounding.

## Composition

- 4,823 forms
- 6,365 linked senses
- 4,823 canonical audio clips
- 11 pseudonymous speaker IDs
- coarse labels, fine labels, and scalar severity scores

## Collection And Annotation

The annotation team comprised 12 annotators in four groups of three. Each item received two independent isolated annotations for coarse label, fine label, and severity score. Disagreements or ambiguity were escalated to an in-group third reviewer, cross-group review, and full-team adjudication when needed.

IAA values from raw independent annotations:

- coarse label Krippendorff alpha nominal: 0.86
- fine label Krippendorff alpha nominal: 0.73
- severity Krippendorff alpha ordinal: 0.82
- severity MAE: 6 points
- severity same-band agreement: 85%
- severity same-or-adjacent-band agreement: 91%

## Recommended Uses

- research benchmark evaluation
- reproducibility study
- analysis of Cantonese harmful lexical ambiguity
- controlled speech-grounded safety evaluation

## Non-Uses

- production moderation deployment
- punitive decisions
- speaker recognition or voice cloning
- claims of speaker-held-out generalization
- claims of conversational moderation coverage

## Limitations

- one canonical clip per retained form
- lexical-unit split; no speaker-held-out generalization claim is made
- current audio/fusion gains are modest and complementary
- no speaker demographic distribution claim
- dictionary-derived definitions/source text have restricted redistribution caveats

## Maintenance

Contact yueyu_dimsum@163.com. Backup: qijiayin@139.com.
