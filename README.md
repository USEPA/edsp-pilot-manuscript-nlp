# EDSP Pilot Manuscript NLP

This repo contains NLP modeling code outlined in the following manuscript: 

`Lea, I.A., Wikoff, D. Borghoff, S., Fitch, S., Chappell, G., Urban, J.D., Perry, C., Choksi, N., Britt, J., Heintz, M., Klaren, W., Chew, R., Edwards, S., Bever, R.J., Hamernik, K., Kirk, A.B., Lynn, S.G., Markey, K.J. (2024) "Development of a systematic evidence mapping workflow and case study application of the workflow to interrogate thyroid hormone network information".`

In particular, the notebooks directory contains three relevant files:
- **01_Create_Embeddings.ipynb**
  - Creates text embeddings from article titles and abstracts using the [SPECTER](https://arxiv.org/abs/2004.07180) model.
- **02_Prediction_Report.ipynb**
  - Creates text classification models for the primary fields used in the study.
- **03_Article_Similiarity.ipynb**
  - Demonstrates article similarity approach used to support article selection.

## Getting Started

To run notebooks, first install the required python packages:

`pip install -r requirements.txt`

Then use Jupyter to host the notebooks in the browswer:

`juypter notebooks`

## Disclaimer

The United States Environmental Protection Agency (EPA) GitHub project
code is provided on an "as is" basis and the user assumes responsibility for its use. EPA
has relinquished control of the information and no longer has responsibility to protect
the integrity, confidentiality, or availability of the information. Any reference to specific
commercial products, processes, or services by service mark, trademark, manufacturer, or
otherwise, does not constitute or imply their endorsement, recommendation or favoring
by EPA. The EPA seal and logo shall not be used in any manner to imply endorsement of
any commercial product or activity by EPA or the United States Government.

## Contact

For questions, please reach out to Scott Lynn at <Lynn.Scott@epa.gov>
