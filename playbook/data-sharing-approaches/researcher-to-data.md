# Researcher to Data

</br>

**Researcher to Data** is an approach where the _data controller_ creates a secure computing environment in which interested parties are able to perform requests for data processing on a centralised database. This approach requires technical expertise to implement, although many modern database solutions provide the tools to implement this without significant overhead.

```{figure} ./_static/img/datastrategy2.png
---
height: 398px
name: datastrategy2
---
```

The centralised secure environment allows restriction for data processing, for example limitation on which data may be used, which parties are allowed for analysis of data, limitation of time to access the data and limitation of processing power. Before accessing such an environment legal agreement between the data controller and the data processors is needed. 

The provision of secure computing environments can in some cases be complex and maintenance has traditionally been expensive, but with advances in software and with the low entry cost modern cloud cyberinfrastructure, these technological solutions are becoming more feasible to implement for a larger range of organizations. 

The researcher-to-data approach is mostly applied by parties that collect large data sets. For example, [LifeLines](https://www.lifelines.nl/) manages a large amount of health data from a major cohort of volunteers (167.000) in the Northern part of the Netherlands. LifeLines allows other research parties to use data within a secure computing environment. In the UK [OpenSafely](https://www.opensafely.org/) provides a secure analytics platform for analysis of 58 million NHS electronic health records. OpenSafely also provides an [open source software platform](https://github.com/opensafely-core) that can be used for the researcher-to-data approach by other parties or institutes.

This method works well in terms of synchronzing between local and remote data states. Since the data analysis is done on the remote storage, all users work with the same version of the data. 

The researcher-to-data strategy works well when there is one -data controller- that controls a large collection of data. However, a problem arises when sensitive data from multiple data holders are in combination needed for analysis. In those cases, collecting data in one central environment is often not a convenient solution since individual data holders might not want to lose control over their data.

 </br>

:::{seealso}

*Bringing Code to Data: Do Not Forget Governance*, article available on [PubMed](https://pubmed.ncbi.nlm.nih.gov/32540846/).

:::
