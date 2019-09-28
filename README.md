# Baseline Proxy

There are a many ways to remove carbon dioxide from the atmosphere but the [cheapest method available so far](https://www.sciencedirect.com/science/article/abs/pii/S1462901115000222) that [could have material impact on carbon dioxide levels](https://science.sciencemag.org/content/304/5677/1623) is regenerative agriculture. The practice involves a farmer adjusting their land-use practices in ways that cause the soil to absorb carbon (which, conveniently, also increases the fertility of the soil). Doing so requires time and/or material investment. Fortunately there are [people](https://www.terrapass.com/) and [businesses](https://news.shopify.com/we-need-to-talk-about-carbon) that [would gladly pay](https://stripe.com/blog/negative-emissions-commitment) for this carbon removal. 

[Nori](https://nori.com) has developed a model that can estimate how much carbon was removed by any particular farmer’s change in land-use practices. That enables farmers to type information about their farming practices into a form and get an estimate of how much they could get paid for practicing regenerative agriculture. This enables them to forecast whether or not their effort would be worth it. But it takes times for farmers to input the data necessary to create that estimate.

## The Goal

The goal is to use open-source data to create sensible defaults. Using these defaults will make it easier for farmers to get a carbon removal payment quote because they will reduce the amount of manual input needed. For example, most farmers in certain areas grow only corn. If a farmer enters their address in that area, the Baseline Proxy should return a value of `corn`. 

### Raw farm data
- USDA QuickStats: https://quickstats.nass.usda.gov/
- USDA QuickStats API: https://quickstats.nass.usda.gov/api
- USDA Soil Data: https://www.nrcs.usda.gov/wps/portal/nrcs/detail/soils/survey/?cid=nrcs142p2_053627 
- Main USDA statistics site: https://www.nass.usda.gov
- Stanford Yield Mapper: https://lobell-lab.stanford.edu/research/scalable-satellite-based-yield-mapper

### Background on carbon removal
- [Carbon cycle on Wikipedia](https://en.wikipedia.org/wiki/Carbon_cycle) 
- [Carbon dioxide removal on Wikipedia](https://en.wikipedia.org/wiki/Carbon_dioxide_removal)

### Nori 
- [Nori's white paper](Nori.com/white-paper)
- [Nori's resources](Nori.com/resources)
- [Reversing Climate Change podcast](https://nori.com/podcasts/reversing-climate-change) and [Carbon Removal Newsroom podcast](https://nori.com/podcasts/carbon-removal-newsroom) 
