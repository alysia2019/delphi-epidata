# Status

[![Deploy Status](https://delphi.cmu.edu/~automation/public/github_deploy_repo/badge.php?repo=cmu-delphi/delphi-epidata)](#)

# About

This is the home of [Delphi](https://delphi.cmu.edu/)'s epidemiological data
API. See our [API documentation](https://cmu-delphi.github.io/delphi-epidata/)
for details on the available data sets, APIs, and clients.

# COVID-19 Notice

We are working on collecting several new data sources that may be useful for
nowcasting and forecasting ILI during the COVID-19 pandemic.  Each of these will
make these available as soon as individually possible, through our [covidcast
endpoint](https://cmu-delphi.github.io/delphi-epidata/api/covidcast.html).

For a list of many other data sources relevant to COVID-19, publicly available
through external sites, we have compiled a simple
[spreadsheet](https://docs.google.com/spreadsheets/d/16Nn_3ZvSLnpxRyA2DkoMMzyrd11-AlGJXasS0owln88/edit#gid=0).

**Note:** apart from the COVID-19-specific data sources described above, the
rest of this repository was built to support modeling and forecasting efforts
surrounding seasonal influenza (and dengue).  All other data sources than those
in our covidcast endpoint should be **held to great scrutiny** (if they are even
to be considered at all in this pandemic period), since they were designed to
serve as indicators of typical seasonal ILI (influenza-like illness), and
certainly not pandemic ILI or CLI (covid-like illness).

## Contributing

If you are interested in contributing:

- For development of the API itself, see the
  [development guide](docs/epidata_development.md).
- To suggest changes, additions, or other ways to improve,
  [open an issue](https://github.com/cmu-delphi/delphi-epidata/issues/new)
  describing your idea.

## Citing

We hope that this API is useful to others outside of our group, especially for
epidemiological and other scientific research. If you use this API and would
like to cite it, we would gratefully recommend the following copy:

> David C. Farrow,
> Logan C. Brooks,
> Aaron Rumack,
> Ryan J. Tibshirani,
> Roni Rosenfeld
> (2015).
> _Delphi Epidata API_.
> https://github.com/cmu-delphi/delphi-epidata

# Related work

 - Cook, Samantha, et al. "Assessing Google flu trends performance in the United
   States during the 2009 influenza virus A (H1N1) pandemic." PloS one 6.8
   (2011): e23610.
 - Broniatowski, David A., Michael J. Paul, and Mark Dredze. "National and local
   influenza surveillance through Twitter: an analysis of the 2012-2013
   influenza epidemic." (2013): e83672.
 - Dredze, Mark, et al. "HealthTweets. org: A Platform for Public Health
   Surveillance using Twitter." AAAI Conference on Artificial
   Intelligence. 2014.
 - Generous, Nicholas, et al. "Global disease monitoring and forecasting with
   Wikipedia." (2014): e1003892.
 - Hickmann, Kyle S., et al. "Forecasting the 2013–2014 Influenza Season Using
   Wikipedia." (2015): e1004239.
 - McIver, David J., and John S. Brownstein. "Wikipedia usage estimates
   prevalence of influenza-like illness in the United States in near real-time."
   PLoS Comput Biol 10.4 (2014): e1003581.
