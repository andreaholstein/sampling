# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1. In two to three sentences, describe the purpose of your survey
2. Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3. Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios

1. You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2. You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3. You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s)
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used

# Your Changes

## Part A - Survey Design:

The number of your chosen topic: `2`

Describe the purpose of your survey:

```
 I am designing a survey to better understand which issues are top-of-mind for voters in this federal election cycle. The goal is to identify ways to better position our party's leader as the ideal candidate to address voter concerns, and ensure that campaign promises more closely align with what voters seek from their next political leader.
```

Describe your target population, sampling frame, sampling units, and observational units:

```
The target population is all eligible voters in Canada. The frame is 1000 registered voters in each province and territory selected from the target population. The sampling units are individuals, 18 and older, who are registered to vote, and can be reached by Canada Post/mail delivery service in their home jurisdiction. The goal of the sampling strategy is to collect a representative sample of registered voters across each province and territory in order to glean some region-specific insight into the issues voters care most about, in order to extrapolate from that the ideal political candidate strategy to appeal to those diverse voters.
```

Your 5-10 question survey:

```
1. Do you intend to vote in the upcoming federal election: why or why not? [Y/N, space to elaborate on their reasoning]
2. In the last election in which you cast a vote, which party did you vote for and why? [List of parties to choose from, space to elaborate on their reasoning]
3. In the upcoming election, which party do you intend to vote for? [List of parties]
4. In the following list of 5 issues, rank these issues based on their importance to you as a voter, with 1 meaning 'of no importance', and 5 meaning 'of greatest importance'. [List of 5 established popular issues]
5. Is there a political issue that matters to you and which you have yet to see a political party/candidate address in their campaigning so far? Please elaborate on what this issue is. [Space to elaborate]
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type
  - Observational - "sample survey with cross-sectional design."
2. Sample size
  - 50,000 units.
3. Target population
  - All individuals, aged 15+, living in the Canadian provinces, and excludes folks institutionalized for 6 months or longer.
4. Sampling frame:
  - Individuals reachable by cellphone or landline numbers.
5. Survey mode(s)
  - Interviews with a single member of a household, aged 15+, reachable by telephone. Further subdivided based on volunteering status, with folks who identify as volunteers doing long interviews, and others do short ones.
6. Timeline
  - 2018-09-04 to 2018-12-28
7. Response rate
  - 41.9%.
8. Weights
  - Estimation weights: "WGHT_PER: This is the basic weighting factor for analysis at the person level, i.e. to calculate estimates of the number of persons (non-institutionalized and aged 15 or over) having one or several given characteristics."
  - Bootstrap weights: "In addition to the estimation weights, bootstrap weights have been created for the purpose of design-based variance estimation."
9. Data processing
  - Data collected directly from survey respondents via either electtronic questionnaires or through CATI. Participation was voluntary and no proxies were allowed.
  - Data was linked to tax records of respondents and their household.

10. Cleaning, imputation, etc
  - Error edtection strategies were employed to detect and edit out-of-range values in real-time to try and resolve those with respondents - anything that couldn't be resolved then was forwarded to the head office for resolution (more checks and edits).
  - Imputations largely done using donor records (evaluating records against respondent info to find a close "match"), and using their info to fill in missing respondent info.
  - Where donor imputation wasn't possible, mean imputation of the donor pool was used.
11. Sources of error
  - Imperfect coverage: i.e. unreachable households/telephone #s.
  - Non-response: 2 stages of surveying - at the household level and at the individual level, which presented two opportunities for non-response.
  - Also: response errors, processing errors.
12. Limitations, known biases, etc
  - Reduced nonresponse bias by adjusting the survey weights to account for it. Where information could be extracted from admin sources to make up for missing basic info, that strategy was used.
13. Link to documentation and any additional sources used
  - https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
```

## Rubric

- All required components are present and complete **Complete / Incomplete**
- Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
- Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:

- Submission Due Date: `23:59 - 29/06/2025`
- The branch name for your repo should be: `assignment-2`
- What to submit for this assignment:
  - This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
- What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
  - Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:

- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
