# solana-climate
Data files/analysis for Solana climate report


Climate Footprint Analysis Summary

Blockchain networks can help address climate change, one of the greatest challenges of our time. But the energy consumption and resulting emissions of these networks can also exacerbate the problem.

Solana has built a scalable, high performance network that can play a positive role in collective climate action. The Solana approach is guided by core principles to:

-- Remain a sustainable solution as it scales

-- Be part of the solution, not just avoid being part of the problem

-- Be transparent and dedicated to continuous process improvement

In mid-2021 Solana commissioned analysis of its validator network’s climate footprint in order to: 1) reduce Solana-related greenhouse gas (GHG) emissions as far as possible; and 2) utilize high-quality offset / removal programs to address those emissions that cannot be avoided. This document and related data describe this climate footprint analysis, provide transparency into Solana’s process, create opportunity for community feedback, and will hopefully drive further conversation on the relationship between climate change and blockchain. 

In addition, ideally this program can help address the broader lack of high quality, open source, harmonized data on carbon intensity for grid electricity. The Solana Foundation has always been transparent about the data used to do this analysis, but as of September 2022 we’ve taken the additional step of adding this data to GitHub. The idea is to make it as straightforward as possible for the broader blockchain and climate advocacy community to dig into, engage with, and use this data for new purposes. Through community engagement this analysis can be improved and utilized to answer impactful questions such as: Where are the lowest carbon locations to set up a validator node? How can we standardize emissions data and reporting across blockchains?

Key takeaways

Solana’s current validator network utilizes relatively low carbon power - Solana validators are distributed worldwide by design, and the power consumption utilized by this network drives Solana’s overall carbon footprint. As the validator network grows, the overall energy consumption of Solana will follow suit. In terms of emissions, the International Energy Agency recently estimated that the global average for electricity carbon intensity is 475 gCO2/kWh. Based on the most recent validator network analysis, the current Solana weighted average for electricity carbon intensity is 180g CO2/kWh–less than half the global average. This weighted average emissions intensity is expected to fall further once more information on data center-specific emission reduction programs is gathered and integrated in collaboration with the Solana community (see below).

Solana’s total climate footprint is equivalent to a small neighborhood, not a mid-sized country - The overall network has a small impact on climate change–a result of both low energy consumption inherent to Solana’s technology and low carbon power utilized by validators. The current estimated total emissions footprint for the global Solana network is 3,412 tonnes of CO2 per year. In the near term, the network can be made carbon neutral through reducing validator emissions, and then purchasing offsets for emissions that cannot be avoided. Over the longer term, a zero carbon blockchain will become increasingly feasible as access to 24/7 renewable energy options improves.

Analysis notes

The beginning, not the end - This analysis is a first step to characterizing the climate footprint of the Solana network, and will be improved as needed over time. For example, estimates of the hardware production emissions associated with validator systems have been added to this third Solana climate report, in order to continue improving the overall quality and completeness of the analysis.

The perfect need not be the enemy of the good - This analysis is not 100% correct, and never will be. Data availability on power consumption and carbon intensity is generally limited, especially for open source use and distribution.

Released for transparency + collaboration - The Solana community and stakeholders can use this data, but hopefully will also engage to help improve it and expand its utilization.

When in doubt, overestimate - Given the limitations in the data inputs, when in doubt the Solana climate footprint analysis errs on the side of caution, assuming worst case efficiencies, higher carbon intensity power, etc.

Limited credit for cleaner data centers - A key example of analysis overestimation is the power utilized in data centers where Solana validators operate. In many instances data center operators utilize a range of options to reduce their climate impact, such as installation of on-site renewable energy, storage, and/or purchase of renewable energy credits. The renewable energy programs at three of the data centers that host a wide range of Solana validators were assessed and included in the current analysis. But accessing information on data center-specific emissions reduction programs and then assessing their quality/validity would have delayed implementation of the Solana climate program. As such the current analysis significantly overestimates the Solana network footprint. However, as the climate program matures, validators will be encouraged to submit information on any data center-specific GHG reduction initiatives. This will help create a more robust, community-driven view of the climate footprint of both Solana and the data center sector more broadly.

Node location verification - If/when validator carbon intensity is operationalized on the Solana network, it will become more relevant to confirm node and data center locations.

Open data vs best data - Organizations such as the International Energy Agency and various consulting firms have some of the best globally harmonized power sector data available, but generally it cannot be publicly distributed. As such, the Solana footprint analysis is based on aggregation of various open data sources and is not fully harmonized across locations.

Suitable temporal data resolution - For each location where Solana validators currently operate, annual average carbon intensity for local grid power has been sourced. Annual values are appropriate as Solana validators typically run constantly and their power footprint would fit with these averages. However, in reality, the carbon intensity of grid power is highly dependent on minute-by-minute changes in supply and demand, but this data is only publicly available in a very limited range of global locations.

Suitable spatial data resolution - Power grids and national boundaries do not always neatly overlap. But this is the most comparable data scale available, and national emissions intensity factors often take cross-border energy transfers between connected grid systems into account. However, state/provincial-level data for the US and Canada was added given a) data availability, and b) often significant differences between some of these grid systems. Additional region-level granularity can be added in future based on availability and need.

Best available data recency - Credible and comparable emissions intensity data are often only updated on a periodic basis. For certain locations, data as recent as 2020 is available, but for others data may be older. This is generally appropriate as the energy mix of grid power tends to evolve slowly, and in many locations emissions intensity has been trending downward. So older data will tend to overestimate emissions in many locations.
