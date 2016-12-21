# Coding Sprint: Supervised Time Series

## When & Where

27th - 31st of March, at New York University.

Room: To-be-announced.

![alt text](map.png "NYU Map")


## What & Why

By providing new techniques and new ways of looking at complex datasets, machine learning is currently revolutionizing many scientific fields.

The present coding sprint aims at gathering data-scientists who specialize in high dimensional time series.

Our specific goal is to integrate the classic continuous signal processing techniques and the main machine learning techniques within a common framework following [Scikit-Learn](http://scikit-learn.org)'s API such that user can for example do

```python
make_pipeline(
    TimeFrequencyTransform(frequencies=range(1, 100)),
    GrangerCausality(),
    SVM(kernel='rbf')
)
```

We are currently biased towards neural time series (EEG, MEG, ECoG, multi-unit neural recordings etc), but would like to bridge towards other communities which deal with signals with similar underlying structures (music, speech, radar etc).

## Who

The current list of confirmed developpers are all core-developper of [MNE](mne-tools.github.io):
- [Alexandre Barachant](http://alexandre.barachant.org) is a multi-winner of [Kaggle competitions](https://www.kaggle.com/alexandrebarachant) and currently specializes in decoding MEG and EEG signals using Riemannian Geometry.
- [Denis Engemann](http://www.denis-engemann.de), is an assistant Prof at INRIA and currently specializes in large-scale analyses of EEG and MEG databases.
- [Alexandre Gramfort](alexandre.gramfort.net) is a prof at Telecom Paris-Tech, [Scikit-Learn](http://scikit-learn.org) and currently specializes in inverse modeling.
- [Chris Holdgraf](http://predictablynoisy.com/) is a grad student at Berkley and currently specializes in continuous encoding models.
- [Jean-Rémi King](https://sites.google.com/site/jeanremiking/) is a postdoc at NYU & FIAS and currently specializes in decoding M/EEG & ECoG signals.
- [Eric Larson](http://staff.washington.edu/larsoner/) is a research scientist at UW, [Scipy](https://www.scipy.org/) and currently specializes in signal denoising.
- [Jas Mainak](https://perso.telecom-paristech.fr/mjas/) is a grad student at Telecom Paris-Tech and currently specializes in denoising MEG signals.
- [Jona Sassenhagen](https://github.com/jona-sassenhagen) is a Postdoc at Uni. of Frankfurt and currently specializes in continuous encoding models.

### Support or Contact

Anyone interested in joining is welcome to join us. You can contact jeanremi.king [at] gmail [dot] com for specific information.
