# Checklist for Multilingual LLM Evaluation

Last updated: April 15, 2025

## Evaluation Prompts
- [ ] Are evaluation prompts representative samples of all languages included in the evaluation?
- [ ] Are evaluation prompts human-curated, localized or edited?
- [ ] If using model generated prompts: Have you analyzed the data for potential biases?
- [ ] If using translations: Have you estimated, reported, and attempted to optimize translation quality on this particular set of prompts?

## Choice of Metrics
- [ ] Are metrics adequate for all evaluated languages?

## Statistical Testing
- [ ] Does the evaluation include adequate statistical significance tests for all included languages?
- [ ] Does the evaluation include an estimate of statistical power?
- [ ] If using stochastic decoding, does it include estimates of sampling induced variance?

## Aggregating Results Across Languages
- [ ] Is the aggregation of results disproportionately influenced by any outliers?
- [ ] Are language support differences taken into consideration when aggregating results across languages?
- [ ] Are language support differences documented with the results?
- [ ] Are task- and language-specific scores reported?

## Qualitative Insights
- [ ] Are quantitative metrics accompanied by qualitative error analyses?
- [ ] Are differences in metrics due to meaningful distinctions rather than incidental artifacts?

## Reproducibility
- [ ] Are the results calculated with standardized pipelines?
- [ ] Is the evaluation code released?
- [ ] Are exact evaluation prompts and format published?
- [ ] Are model outputs released?
- [ ] Are prompt-level evaluation scores released?
- [ ] Are metric hyperparameters documented?
- [ ] Are model versions documented?

 ## Enabling Meta-Evaluation
 - [ ] Are any human evaluations (consensually) released?
