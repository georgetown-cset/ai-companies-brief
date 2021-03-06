# Overview

The data in [ai_companies.csv](ai_companies.csv) is 
in support of CSET's [Identifying AI-Related Companies](https://cset.georgetown.edu/research/identifying-ai-related-companies/) data brief. [ai_companies.csv](ai_companies.csv) includes counts of selected companies’ AI-related scholarly publications, their publications in the proceedings of top AI conferences, their AI-related patent families with both applied and granted filings, and the number of graduates that each company is known to have hired recently from top U.S. AI PhD programs, as well as certain metadata related to each company. For more details, please refer to the [data brief](https://cset.georgetown.edu/research/identifying-ai-related-companies/).

We collected this data from five sources:

- The Country, Website, Crunchbase_URL, and Exchange_and_Ticker are collected from
the Crunchbase Open Data Map (Powered by Crunchbase). This data can be found at
[http://www.crunchbase.com](http://www.crunchbase.com).

- The Associated_GRID_Identifiers, AI_Top_Conference_Papers (Count and Rank), and
AI_Publications (Count and Rank) are collected from [GRID](https://grid.ac) and
Digital Science's [Dimensions](https://www.digital-science.com/products/dimensions/)
publications data.

- The AI_Patent_Families (Count and Rank) are collected from [1790 Analytics](https://1790analytics.com/)'
data on patents, specifically from a subset of this data focused on AI-related patents.

- The PhD_Hires (Count and Rank) were collected as part of CSET's own [Keeping Top
AI Talent in the United States](https://cset.georgetown.edu/wp-content/uploads/Keeping-Top-AI-Talent-in-the-United-States.pdf)
 study, analyzing hiring data for graduates with PhD dissertations
dated between 2014 and 2019, inclusive.

- The Associated_PermId_Identifiers are collected from Refinitiv's [Eikon](https://www.refinitiv.com/en/products/eikon-trading-software)
platform. These were used as company identifiers to capture hierarchical company relationships.

Further details on these data sources can be found in the "Data Sources" appendix
of the brief.
