# Backfire Effect Analysis
This is work I have done on an upcoming paper: a study further examining some of the issues raised in the principal
author's last paper, [Searching for the backfire effect: measurement and design
considerations](https://psyarxiv.com/ba2kc/). This paper compares a control group, who received no corrections of
misinformation, and a treatment group, who did receive corrections on pieces of misinformation. After 3 weeks, both
groups were retested. The study found that the putative *backfire effect*, in which correcting people's mistaken beliefs
causes a paradoxical increase in belief, correlates significantly with the reliability of the measure in the control
group, with a strong negative relationship. Put another way, the more a control group's answers about their belief in a
particular bit of misinformation or information changed, the more likely the treatment group was to experience a
backfire effect. This strongly suggests, in combination with the above paper, that the backfire effect as discussed in
the literature is largely due to measurement errors.

## Files
This repository has no intended user except myself, and so the organization is not especially clean. Briefly, what is
where:

 - `reliability-analysis.ipynb` was my first work making sense of the data after processing it, and is more exploratory.
 - `reliability-paper.ipynb` is my version of the statistics and figures included in the final manuscript, used both to
   corroborate the analysis of others and some original analysis of my own.
 - `paper-figures.ipynb` is the version of the figures used in the final manuscript being submitted, matching *Nature:
   Human Behavior*'s style.
   
The `processed_data.xlsx` being referenced is the processed survey results: even though they're anonymous, I'd rather
not share that unless necessary to respect the privacy of the research participants.
