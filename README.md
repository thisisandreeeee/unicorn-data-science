# unicorn-data-science
This repository contains useful articles and papers for the (aspiring) unicorn data scientist. Unlike other `awesome-xyz` repositories, this does not consolidate software tools or libraries; only reading materials.

Pull requests are welcome! See [Contributing](./CONTRIBUTING.md).

--------------------

<!-- toc -->

- [Engineering](#engineering)
  * [ML Engineering](#ml-engineering)
  * [Experimentation](#experimentation)
- [Statistics](#statistics)
  * [Distributions](#distributions)
  * [Inference](#inference)
- [Data Science](#data-science)
  * [Recommendations](#recommendations)
  * [Causal Inference](#causal-inference)
  * [Regression](#regression)
  * [Forecasting](#forecasting)
  * [Deep Learning](#deep-learning)
- [Analytics](#analytics)
  * [Analytics Engineering](#analytics-engineering)
  * [Data Governance](#data-governance)
- [Teams](#teams)
  * [Management](#management)
  * [Hiring](#hiring)
  * [Interviewing](#interviewing)
- [Consulting](#consulting)

<!-- tocstop -->

--------------------

## Engineering

### ML Engineering

- [Rules of ML](https://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)
- [Engineers Shouldn’t Write ETL: A Guide to Building a High Functioning Data Science Department](https://multithreaded.stitchfix.com/blog/2016/03/16/engineers-shouldnt-write-etl/)
- [Machine Learning: The High-Interest Credit Card of Technical Debt](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/43146.pdf)
  - [Follow-up post on ML technical debt](https://matthewmcateer.me/blog/machine-learning-technical-debt/)
- [Production-Level-Deep-Learning](https://github.com/alirezadir/Production-Level-Deep-Learning)
- [End-to-end Machine Learning with TFX on TensorFlow 2.x](https://towardsdatascience.com/end-to-end-machine-learning-with-tfx-on-tensorflow-2-x-6eda2fb5fe37)
- [Monitoring Machine Learning Models in Production](https://christophergs.com/machine%20learning/2020/03/14/how-to-monitor-machine-learning-models/)
- [ML engineering best practices](https://se-ml.github.io/practices/)
- [Google MLOps whitepaper](https://services.google.com/fh/files/misc/practitioners_guide_to_mlops_whitepaper.pdf)
- [Ways I Use Testing as a Data Scientist](https://www.peterbaumgartner.com/blog/testing-for-data-science/)
- [MLOps Principles](https://ml-ops.org/content/mlops-principles)
- [Continuous delivery and automation pipelines in machine learning](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning)

### Experimentation

- [Detecting Interference: An A/B Test of A/B Tests](https://engineering.linkedin.com/blog/2019/06/detecting-interference--an-a-b-test-of-a-b-tests)
- [Switchback Tests and Randomized Experimentation Under Network Effects at DoorDash](https://medium.com/@DoorDash/switchback-tests-and-randomized-experimentation-under-network-effects-at-doordash-f1d938ab7c2a)
- [Innovating Faster on Personalization Algorithms at Netflix Using Interleaving](https://netflixtechblog.com/interleaving-in-online-experiments-at-netflix-a04ee392ec55)

## Statistics

### Distributions

- [Probability Distribution Explorer](http://bois.caltech.edu/distribution_explorer/)
- [Common probability distributions](https://medium.com/@srowen/common-probability-distributions-347e6b945ce4)
- [William Chen probability cheat sheet](https://static1.squarespace.com/static/54bf3241e4b0f0d81bf7ff36/t/55e9494fe4b011aed10e48e5/1441352015658/probability_cheatsheet.pdf)
- [KDE visualisation](https://mathisonian.github.io/kde/)
- [Modeling conversion rates and saving millions of dollars using Kaplan-Meier and gamma distributions](https://better.engineering/2019/07/29/modeling-conversion-rates-and-saving-millions-of-dollars-using-kaplan-meier-and-gamma-distributions/)
- [Robust Statistical Distances for Machine Learning](https://www.datadoghq.com/blog/engineering/robust-statistical-distances-for-machine-learning/)

### Inference

- [Common statistical tests are linear models](https://lindeloev.github.io/tests-as-linear/)
- [Bayesian Optimization](https://distill.pub/2020/bayesian-optimization/)
- [On Average, You’re Using the Wrong Average: Geometric & Harmonic Means in Data Analysis](https://towardsdatascience.com/on-average-youre-using-the-wrong-average-geometric-harmonic-means-in-data-analysis-2a703e21ea0)
- [Stop aggregating away the signal in your data](https://stackoverflow.blog/2022/03/03/stop-aggregating-away-the-signal-in-your-data/)
- [Inferring Concept Drift Without Labeled Data](https://concept-drift.fastforwardlabs.com/)

## Data Science

### Recommendations

- [Google Recommendation Systems Crash Course](https://developers.google.com/machine-learning/recommendation)
- [Deep Neural Networks for YouTube Recommendations](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45530.pdf)
- [Deep density networks and uncertainty in recommender systems](https://arxiv.org/pdf/1711.02487.pdf)

### Causal Inference

- [Bandit Algorithms](https://banditalgs.com/)
- [A Contextual-Bandit Approach to Personalized News Article Recommendation](https://arxiv.org/pdf/1003.0146.pdf)
- [Python Causality Handbook](https://matheusfacure.github.io/python-causality-handbook/)

### Regression

- [OLS Regression Explained Visually](http://setosa.io/ev/ordinary-least-squares-regression/)
- [How Instacart delivers on time (using quantile regression)](https://tech.instacart.com/how-instacart-delivers-on-time-using-quantile-regression-2383e2e03edb)

### Forecasting

- [Our quest for robust time series forecasting at scale](http://www.unofficialgoogledatascience.com/2017/04/our-quest-for-robust-time-series.html)
- [Sorry ARIMA, but I’m Going Bayesian](https://multithreaded.stitchfix.com/blog/2016/04/21/forget-arima/)

### Deep Learning

- [A Recipe for Training Neural Networks](http://karpathy.github.io/2019/04/25/recipe/)
- [Numerically stable and computationally efficient log-sum-exp](http://www.nowozin.net/sebastian/blog/streaming-log-sum-exp-computation.html)
- [Interpreting loss curves](https://developers.google.com/machine-learning/testing-debugging/metrics/interpretic)
- [Visualizing the Loss Landscape of a Neural Network](https://mathformachines.com/posts/visualizing-the-loss-landscape/)

## Analytics

### Analytics Engineering

- [Practical advice for analysis of large, complex data sets](http://www.unofficialgoogledatascience.com/2016/10/practical-advice-for-analysis-of-large.html)
- [The hacker's guide to uncertainty estimates](https://erikbern.com/2018/10/08/the-hackers-guide-to-uncertainty-estimates.html)
- [What is an analytics engineer?](https://blog.getdbt.com/what-is-an-analytics-engineer/)
- [The Modern Data Stack](https://blog.getdbt.com/future-of-the-modern-data-stack)
- [Emerging architectures for modern data infrastructure](https://future.a16z.com/emerging-architectures-modern-data-infrastructure/)
- [Highly Opinionated Integrations](https://davidsj.substack.com/p/highly-opinionated-integrations)

### Data Governance

- [DataHub: Popular metadata architectures explained](https://engineering.linkedin.com/blog/2020/datahub-popular-metadata-architectures-explained)
- [Biases in AI Systems](https://queue.acm.org/detail.cfm?id=3466134)
- [How to Move Beyond a Monolithic Data Lake to a Distributed Data Mesh](https://martinfowler.com/articles/data-monolith-to-mesh.html)

## Teams

### Management

- [Hashicorp manager charter](https://works.hashicorp.com/articles/manager-charter)
- [Good DS vs. Bad DS](https://ianwhitestone.work/good-ds-bad-ds)
- [Open decision making](https://web.stanford.edu/~ouster/cgi-bin/decisions.php)
- [North star metrics](https://future.com/north-star-metrics/)
- [Agile analytics](https://locallyoptimistic.com/post/agile-analytics-p1/)
- [Modern data culture stack](https://humansofdata.atlan.com/2021/12/modern-data-culture-stack/)

### Hiring

- [How to Consistently Hire Remarkable Data Scientists](https://firstround.com/review/how-to-consistently-hire-remarkable-data-scientists/)
- [How Coursera Competes Against Google and Facebook for the Best Talent](https://firstround.com/review/this-is-how-coursera-competes-against-google-and-facebook-for-the-best-talent/)
- [How to hire smarter than the market: a toy model](https://erikbern.com/2020/01/13/how-to-hire-smarter-than-the-market-a-toy-model.html)
- [Interviewing is a noisy prediction problem](https://erikbern.com/2018/05/02/interviewing-is-a-noisy-prediction-problem.html)
- [How to set compensation using commensense principles](https://erikbern.com/2020/06/08/how-to-set-compensation-using-commonsense-principles.html)
- [VP of Engineering hiring cheatsheet](https://notion.notion.site/VP-of-Engineering-hiring-cheatsheet-f7824eb3f60748bb997f9b9b14c073a5)

### Interviewing

- [Conor Dewey's list of data science interview resources](https://www.conordewey.com/blog/the-big-list-of-data-science-interview-resources/)
- [101 Data Science Interview Questions, Answers, and Key Concepts](https://blog.datasciencedojo.com/data-science-interview-questions/)
- [How I negotiated a $300,000 job offer in Silicon Valley](https://medium.com/@bayareabelletrist/how-i-negotiated-a-software-engineer-offer-in-silicon-valley-f11590f5c656)
- [How to Make Your Data Science Job Application Stand Out](https://www.dataquest.io/blog/how-to-data-science-job-application-stand-out/)
- [You’re probably answering these 5 common interview questions wrong](https://www.holistics.io/blog/judge-your-company-using-three-levels-data-analysis-data-career-decision-making/)
- [6 red flags I saw while doing 60+ technical interviews in 30 days](http://blog.interviewing.io/6-red-flags-i-saw-while-doing-60-technical-interviews-in-30-days)
- [Google interview warmup](https://grow.google/certificates/interview-warmup/)
- [Red Flags to Look Out for When Joining a Data Team](https://eugeneyan.com/writing/red-flags/)

## Consulting

- [10 Reads for Data Scientists Getting Started with Business Models](https://www.conordewey.com/blog/10-reads-for-data-scientists-getting-started-with-business-models/)
- [Smart companies try to commoditize their products’ complements](https://www.joelonsoftware.com/2002/06/12/strategy-letter-v/)
- [How to find consulting clients](https://chrisachard.com/how-to-find-consulting-clients)
- [Doing Freelance Data Science Consulting in 2019](https://www.ethanrosenthal.com/2020/01/08/freelance-ds-consulting/)
