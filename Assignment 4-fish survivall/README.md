Assignment 4-- fish survival

The file fush.csv Download fush.csvcomes from a study of the survival of under-sized fish that are caught by beam trawler commercial fishing boats and returned to the sea. These fish live on or near the sea bottom.  The study explored effects of environmental conditions at sea and of the use of a water-filled hopper on the survival of the fish.  During trips with commercial trawlers, catches were unloaded from the  net  into either water-filled hoppers or conventional dry hoppers before sorting for size and species. For both hoppers, undersized fish were sampled from the sorting belt. After assessment of vitality status, sampled fish were housed in dedicated survival monitoring tanks on board. Upon return in the harbour fish were transferred to the laboratory to monitor their survival for up to 18 days post-catch.  The researchers recorded sea conditions such as wave height and water temperature, or obtained them from public data sources.   

 

Variables

Fish_no   An identifier for each fish

Trip_ID   An identifier for each trip

Haul_ID  An identifier for each haul (there are multiple hauls per trip)

Temp_water Water temperature (degrees Celsius)

Survival_time (h) Observation time of the fish for survival (hours)

Status_end (1=dead) Whether the fish was alive or dead at the end of the observation time

Vitality_class How healthy the fish appeared after being caught and sorted (A is good, D is bad)

Wave_height (cm) The height of waves at sea when the fish were caught

Depth (m) The depth at which the fish were caught

Processing time (min) Time from fish coming on board to ending up in storage tanks

Hopper type The type of hopper the fish went into between being caught and being sorted. This is experimentally assigned.

Haul_duration (min) How long this specific trawling operation took (before the fish came on board).

Substrate  The type of sea bottom conditions

Length (cm) Size of fish

 

Questions:

1. Which variables are potential confounders for the effect of hopper type on survival?

2. Which variables are potential mediators of the effect of hopper type on survival?

3. Estimate the effect of hopper type on survival. 

4. How does the effect of hopper type on survival vary with fish characteristics and sea conditions?

5. Is vitality class a good summary of the survival risk of the fish?
