## Lecture by Andrew El-Kadi (DeepMind)

### Overview
- Weather and cyclone forecasting
###  Medium-range global weather forecasting
- Problems:
	- Trying to predict atmosphere
	- A lot of interest in issue 
#### Graphcast 
- a determinisitc weather model used in the model 
- GenCast was a probabilistic forecast
- FGN model is a probabilist version

#### Gencast
**Option 1 (Best Default)**

- How do you maintain physical consistency when generating many probabilistic atmospheric futures?
    

**Option 2 (If more research focused)**

- How robust are generative weather models to climate distribution shift vs physics models?
    

**Option 3 (If deployment mentioned)**

- Is uncertainty calibration or raw forecast accuracy harder to improve in practice?
    

---

Functional Generative Networks (FGN)
- Diffusion considered expensive, FGN is 8x faster, can run entire forecast in ~1 min
- ""
- Adaptive instance normalisation -- used as an instance within FGN

FGN architecture:
- Transformers used in FGN for efficiency
- FGN beats GenCast by 99.9% of targets being used


### Cyclone Forecasting:
- FNv3: Model built on FGN specifically for forecasting cyclones
- Is there specific weather patterns that are better/weaker to predict
- 
- Does FGN work better for some weather variables than others?
- Does FGN help more with cyclone track prediction or intensity prediction?
    
- How does FGN represent uncertainty in extreme weather events?
**How do you ensure FGN forecasts stay physically realistic?**

deepmind.google.com/science/weatherlab

Could you explain the architecture a bit more aagian

