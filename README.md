# Growing Together: Koala Field Lab

A student HTML/CSS/JavaScript prototype exploring food selection, rest, and care of a developing koala joey.

## Run

Open `index.html` in a browser. No installation, dependencies, or account is needed.

## Explore

- Feed the mother suitable branch leaves to increase her score.
- Compare unsuitable leaves and flat-surface leaves, which provide no food gain.
- Select milk-dependent, pap-transition, older-joey, or independent stages.
- Feed the joey using its stage-appropriate action.
- Compare enough rest and insufficient rest.
- Watch separate mother and joey scores and read the observation trail.
- Reset to restore both scores to 60 while preserving scenario settings.

## Model assumptions

Both bars are illustrative energy and recovery scores, not measured metabolic energy. Enough rest increases recovery in this model; it does not create food energy. All numerical gains and costs are invented teaching values. Stage selection explores development rather than simulating elapsed months. Milk and carrying costs differ by stage for comparison and are not biological estimates.

Ignoring all flat-surface leaves is an unverified assumption requested for the prototype. At zero mother score, the simulation shows death and stops actions until Reset; this is not a real survival prediction. A joey at zero is shown as depleted. Pap is represented as part of the milk-to-leaves transition, not an instant digestive treatment.

## Computational thinking

The model decomposes behavior into food location, suitability, rest, maternal care, and joey development. It represents these with state variables, stage-dependent costs, conditional feeding rules, and bounded scores. Each action produces an observation explaining the outcome.

## Sources

- [Australian Koala Foundation: diet and digestion](https://savethekoala.com/about-koalas/koalas-diet-digestion/)
- [Australian Koala Foundation: life cycle](https://savethekoala.com/about-koalas/life-cycle-koala/)
- [Australian Museum: the koala genome](https://australian.museum/get-involved/amri/the-koala-genome/)

Created iteratively with ChatGPT/Codex for a computational-thinking assignment.
