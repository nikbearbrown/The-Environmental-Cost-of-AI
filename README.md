# The Environmental Impact of AI

# Energy Consumption of AI: Trends, Impacts, and Sustainability

## Growing Energy Demand of Large AI Models  
The computational requirements of artificial intelligence have skyrocketed with the rise of large-scale models. GPT-4, for example, is reported to have **around 1.8 trillion parameters**, over 6× more than GPT-3’s 175 billion and **1,200×** more than GPT-2 ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=great%20deal%20of%20computation%20resources,4)). This massive scale translates into enormous energy needs. Training GPT-3 consumed roughly **1,287 MWh** of electricity – about as much power as **120 average U.S. homes use in a year** ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=great%20deal%20of%20computation%20resources,4)) ([AI Energy Consumption: How Much Power AI Models Like GPT-4 Are Using (New Stats) | PatentPC](https://patentpc.com/blog/ai-energy-consumption-how-much-power-ai-models-like-gpt-4-are-using-new-stats#:~:text=7.%20Training%20GPT,metric%20tons%20of%20CO%E2%82%82%20emissions)). GPT-4’s training likely required even more energy given its size ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=great%20deal%20of%20computation%20resources,4)). Such energy-intensive training runs have become increasingly common as model sizes and data volumes grow. In fact, the computing power used for cutting-edge AI has been **doubling roughly every 100 days**, far outpacing Moore’s Law ([How to manage AI's energy demand — today and in the future | World Economic Forum](https://www.weforum.org/stories/2024/04/how-to-manage-ais-energy-demand-today-tomorrow-and-in-the-future/#:~:text=AI%20and%20energy%20demand)). One analysis projects that by **2028** the power draw of AI could exceed the **entire electricity consumption of Iceland (as of 2021) ([How to manage AI's energy demand — today and in the future | World Economic Forum](https://www.weforum.org/stories/2024/04/how-to-manage-ais-energy-demand-today-tomorrow-and-in-the-future/#:~:text=Remarkably%2C%20the%20computational%20power%20required,of%20Iceland%20used%20in%202021))**. 

This trend is driving a surge in data center energy use. What was once relatively stable has **“skyrocketed with the AI boom,”** and global data center power demand is forecast to grow **160% by 2030** due in large part to AI workloads ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=Then%20there%20are%20the%20data,on%20and%20the%20hardware%20cool)). Industry estimates already suggest data centers (many running AI services) consume on the order of **1–2% of the world’s electricity** ([AI Energy Consumption: How Much Power AI Models Like GPT-4 Are Using (New Stats) | PatentPC](https://patentpc.com/blog/ai-energy-consumption-how-much-power-ai-models-like-gpt-4-are-using-new-stats#:~:text=5,of%20global%20electricity%20usage)), and climbing. A BBC report even warned that by 2027 the **AI industry may draw more power annually than an entire country (the Netherlands) ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=Massachusetts%20www,environmental%20degradation%20is%20deeply%20concerning))**. In short, as AI models and usage proliferate, so do their energy appetites – raising significant sustainability concerns.

## Energy Use: Training vs. Inference (and Other AI Tasks)  
AI’s energy consumption can be divided into the **training phase** (building the model) and the **inference phase** (running the model for predictions or user queries). While one might assume training dominates, it is often a one-time (if extremely large) expense, whereas inference happens continuously. In practice, **inference now accounts for the lion’s share – about 80% – of AI’s total energy footprint, vs. ~20% for training ([How to manage AI's energy demand — today and in the future | World Economic Forum](https://www.weforum.org/stories/2024/04/how-to-manage-ais-energy-demand-today-tomorrow-and-in-the-future/#:~:text=The%20AI%20lifecycle%20impacts%20the,its%20environmental%20footprint%20will%20escalate))**. Google engineers similarly estimated about **60% of AI energy goes to inference** in production ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=training,of%20CO2%20in%20a%20year)). The reason is scale: a model may be trained once or periodically, but then used millions or billions of times by end-users. For example, **GPT-3’s daily usage was estimated at ~50 lbs of CO₂ emissions (8.4 tons in a year) ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=training,of%20CO2%20in%20a%20year))**, reflecting the cumulative energy of many inference calls. Two months after launch, ChatGPT reached 100 million users – each query drawing power – so over time the **energy to serve users far exceeds the initial training cost ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Inference%20energy%20consumption%20is%20high,according%20to%20one%20tech%20expert))**.

**Training** large models remains extremely energy-intensive in its own right. Training the BERT language model on a large dataset required **64 TPU chips running for four days** ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=The%20more%20data%20an%20AI,are%20typically%20the%20most%20energy)), and a University of Massachusetts study calculated that training a single big NLP model (with extensive experimentation) could emit **626,000 pounds of CO₂** – about **5× the lifetime emissions of an average car** ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=sources%20of%20energy%20that%20result,of%20extra%20burden%20this%20will)). OpenAI’s GPT-3 training run consumed an estimated **1,287 MWh** and produced **502 metric tons of CO₂** ([AI Energy Consumption: How Much Power AI Models Like GPT-4 Are Using (New Stats) | PatentPC](https://patentpc.com/blog/ai-energy-consumption-how-much-power-ai-models-like-gpt-4-are-using-new-stats#:~:text=7.%20Training%20GPT,metric%20tons%20of%20CO%E2%82%82%20emissions)). By contrast, **inference** is less intensive per operation but can eclipse training in aggregate. Serving one **ChatGPT query uses nearly 10× more electricity than a typical Google search** ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=The%20main%20determinant%20of%20AI,to%20match%20the%20pace%20of)), because generating a response requires billions of compute operations across a large neural network. (Some experts put this figure even higher in certain cases ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=smaller%20AI%20models%2C%20many%20people,according%20to%20one%20tech%20expert)).) Multiply that by millions of prompts and you see why running the model can dominate total energy use. In research tests, more complex generative tasks can be especially demanding – for instance, generating 1,000 AI images was measured to consume about **2.9 kWh of energy** (on a particular model/setup), which was higher per-inference energy than comparable text tasks ([Sending One Email With ChatGPT is the Equivalent of Consuming One Bottle of Water](https://www.techrepublic.com/article/generative-ai-data-center-water-use/#:~:text=How%20much%20electricity%20does%20it,to%20generate%20an%20AI%20image)). 

Other AI operations also contribute to energy draw: data preprocessing, hyperparameter tuning, and maintaining the **infrastructure** all add overhead. Keeping **AI servers idling and ready** incurs non-trivial energy as well – a single high-end AI server can draw multiple kWh per day even when just hosting a model ([AI Energy Consumption: How Much Power AI Models Like GPT-4 Are Using (New Stats) | PatentPC](https://patentpc.com/blog/ai-energy-consumption-how-much-power-ai-models-like-gpt-4-are-using-new-stats#:~:text=4,per%20day%20per%20server)). In summary, training a modern AI model can be compared to an **energy-intensive “construction project”**, but inference is like operating a heavy-duty machine continuously. Current usage patterns indicate **inference can account for ~80%** of a model’s **lifetime energy consumption ([How to manage AI's energy demand — today and in the future | World Economic Forum](https://www.weforum.org/stories/2024/04/how-to-manage-ais-energy-demand-today-tomorrow-and-in-the-future/#:~:text=The%20AI%20lifecycle%20impacts%20the,its%20environmental%20footprint%20will%20escalate))**, making efficiency in serving AI just as crucial as efficiency in training it.

## Water Usage for AI Data Center Cooling  
Another often-overlooked aspect of AI’s resource consumption is its **water footprint**. Data centers running AI workloads require enormous cooling capacity to dissipate heat from thousands of high-power chips. In many facilities, cooling is achieved with water – lots of it. **Generative AI’s rise is matched by “millions of gallons of water to cool the equipment”** in data centers ([As Use of A.I. Soars, So Does the Energy and Water It Requires](https://e360.yale.edu/features/artificial-intelligence-climate-energy-emissions#:~:text=Requires%20e360,of%20water%20to%20cool)). For example, in **July 2022 – the final month of GPT-4’s training – Microsoft had to pump about 11.5 million gallons of water** from local Iowa watersheds **just to cool the supercomputer** powering the AI ([Artificial intelligence technology behind ChatGPT was built in Iowa — with a lot of water | AP News : r/Iowa](https://www.reddit.com/r/Iowa/comments/16gbhw6/artificial_intelligence_technology_behind_chatgpt/#:~:text=disclosure)). That single month accounted for **~6% of all water usage in the district** (West Des Moines) ([Artificial intelligence technology behind ChatGPT was built in Iowa — with a lot of water | AP News : r/Iowa](https://www.reddit.com/r/Iowa/comments/16gbhw6/artificial_intelligence_technology_behind_chatgpt/#:~:text=,water%20to%20the%20city%E2%80%99s%20residents)). Microsoft’s overall data center water consumption surged **34% in 2022, reaching nearly 1.7 billion gallons (6.4 billion liters)**, largely due to its expanding AI operations ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=,footprint%20an%20increasingly%20urgent%20issue)). Google’s data centers are similarly water-hungry – one campus in Council Bluffs, Iowa used **about 980 million gallons in 2023** (the highest of any U.S. data center) ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=,households)). 

Even on a per-interaction level, AI “drinks” notable water behind the scenes. Researchers from UC Riverside estimate that **every 20 to 50 user prompts to ChatGPT consume about 500 milliliters (half a liter) of water** for cooling, when factoring in both direct cooling and the water used by power plants supplying the electricity ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=Let%E2%80%99s%20break%20it%20down%20further,about%20500%20milliliters%20of%20water)). In other words, a small bottle of water is depleted for a short AI conversation. If one in ten American workers wrote just a single 100-word email using GPT-4 each week, the annual water required is estimated at **435 million liters** – roughly **all the water used in the state of Rhode Island over 1.5 days ([Sending One Email With ChatGPT is the Equivalent of Consuming One Bottle of Water](https://www.techrepublic.com/article/generative-ai-data-center-water-use/#:~:text=,hours%20%28MWh%29%20of%20electricity))**. And recall, **training itself has a water cost**: OpenAI’s GPT-3 training consumed an estimated **700,000 liters** of water (about 185,000 gallons) through cooling and power generation needs ([Sending One Email With ChatGPT is the Equivalent of Consuming One Bottle of Water](https://www.techrepublic.com/article/generative-ai-data-center-water-use/#:~:text=That%E2%80%99s%20the%20same%20amount%20of,took%20700%2C000%20liters%20of%20water)). 

The scale of AI’s water use is becoming a concern, especially in regions facing drought or water scarcity. Data centers often locate where power is cheap, which can be arid areas – raising the risk of **competition with local communities for water resources ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=water%20increases%2C%20putting%20even%20more,pressure%20on%20local%20supplies))**. Looking forward, the **“water thirst” of AI is poised to grow**. One projection warns that by **2027, AI workloads could consume 4.2 to 6.6 **billion cubic meters** of water annually** (including indirect water use for electricity) if trends continue ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=It%E2%80%99s%20like%20filling%20up%20a,speed%20we%E2%80%99ve%20come%20to%20expect)). That is trillions of liters – equivalent to the water usage of entire large cities or regions – just to support AI computations. Such figures highlight why the **water footprint** now joins energy as a key environmental consideration for AI. 

## Carbon Footprint and Environmental Impact  
The energy and water consumption of AI translates into a substantial **carbon and ecological footprint**. Because most data centers still draw power from fossil-fueled grids, heavy electricity use means high greenhouse gas emissions. There is a direct link between AI’s energy draw and CO₂ output: **the more power-hungry the model, the more carbon it emits**, unless mitigated by clean energy ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=There%E2%80%99s%20a%20causal%20relationship%20between,industry%20may%20consume%20more%20energy)). Researchers have quantified some eye-opening examples. The **University of Massachusetts study** found that training a single large NLP model (with extensive experimentation) emitted **626,000 lbs of CO₂** (~284 metric tons) – **about five times the lifetime emissions of an average car** ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=sources%20of%20energy%20that%20result,of%20extra%20burden%20this%20will)). OpenAI’s GPT-3, as noted, was responsible for roughly **502 tCO₂ just from training ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Moving%20large%20jobs%20to%20data,tons%20of%20carbon%20dioxide%20equivalent))**, equivalent to the annual emissions of **hundreds of gasoline cars ([AI Energy Consumption: How Much Power AI Models Like GPT-4 Are Using (New Stats) | PatentPC](https://patentpc.com/blog/ai-energy-consumption-how-much-power-ai-models-like-gpt-4-are-using-new-stats#:~:text=GPT,powered%20cars%20in%20a%20year))**. And these figures don’t yet account for the ongoing emissions from running the model for millions of users afterward.

At the macro level, data centers (across all applications) are estimated to account for **2.5–3.7% of global greenhouse gas emissions**, exceeding even the aviation industry’s share ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Today%20data%20centers%20run%2024%2F7,those%20of%20the%20aviation%20industry)). AI’s growing footprint is becoming a larger slice of that pie. As companies like OpenAI, Google, and Baidu race to build bigger models and more people use them, the concern is that **AI could make cutting overall CO₂ emissions much harder ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Northeastern%20University%20and%20MIT%20researchers,our%20societies%20much%20more%20difficult))**. One analysis predicted that by 2027, the energy consumption (and by extension carbon emissions) of the AI sector might outstrip that of some entire countries (e.g. the Netherlands) if unchecked ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=Massachusetts%20www,environmental%20degradation%20is%20deeply%20concerning)). 

Beyond carbon emissions, **AI’s hardware supply chain has environmental impacts**. Manufacturing the thousands of specialized chips (GPUs, TPUs, etc.) for AI requires mining and refining of rare materials and consumes significant energy and water. This contributes to electronic waste and resource depletion. The World Economic Forum projects **e-waste could exceed 120 million metric tons annually by 2050** (the equivalent mass of **nearly 12,000 Eiffel Towers**) ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=Apart%20from%20carbon%20emissions%2C%20the,degradation%20but%20also%20geopolitical%20tension)). The demand for rare earth metals and other components to build AI infrastructure can also lead to habitat disruption and geopolitical tensions over those resources ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=Apart%20from%20carbon%20emissions%2C%20the,degradation%20but%20also%20geopolitical%20tension)). Additionally, the strain on power grids and water supplies in certain locales can **impact local environments and public health** – for instance, increased air pollution from power generation or reduced water availability in drought-prone areas ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=water%20increases%2C%20putting%20even%20more,pressure%20on%20local%20supplies)) ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=There%E2%80%99s%20a%20causal%20relationship%20between,industry%20may%20consume%20more%20energy)). All these factors raise the question of **sustainability**: How can we continue to advance AI without unsustainable environmental costs?

## Toward Sustainable AI: Mitigation Efforts and Solutions  
Recognizing these challenges, researchers and industry leaders are exploring numerous strategies to **mitigate the environmental costs of AI**. A key approach is improving **efficiency** at all levels:

- **Smarter Model Design:** AI scientists are adopting techniques like *model pruning*, *knowledge distillation*, and *quantization* to make neural networks leaner. Pruning removes redundant parameters, and distillation trains smaller models to replicate larger ones’ behavior. *Quantization*, which uses lower-precision calculations, can cut computation requirements drastically – studies show it can save **up to 50% of the computational cost** with minimal accuracy loss ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=the%20AI%20development%20community)). By using these methods, companies can deploy models that achieve similar results with far less energy. There’s also emphasis on choosing the **right-sized model for the task** – using a massive 175B-parameter model for every little task is wasteful if a smaller model or more traditional algorithm would suffice ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=The%20appropriate%20model)).

- **Efficient Hardware:** Hardware innovation is another pillar of sustainable AI. Specialized AI chips are being developed to deliver more performance per watt. For instance, **NVIDIA’s H100 GPU offers improved throughput per unit of power compared to the A100** (which itself draws up to 400 W per chip) ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=NVIDIA%E2%80%99s%20A100%20GPU%2C%20used%20in,less%20energy%20than%20previous%20generations)). Google’s **TPU (Tensor Processing Unit)** is designed for efficiency in training large models and can outperform general GPUs in both speed and energy use ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=More%20efficient%20hardware)). As a result, the **energy cost per AI operation drops** with each hardware generation. Companies are also turning to *accelerators for inference* – chips optimized to run trained models faster and with lower power, which is critical since inference constitutes ~80% of AI’s energy usage ([How to manage AI's energy demand — today and in the future | World Economic Forum](https://www.weforum.org/stories/2024/04/how-to-manage-ais-energy-demand-today-tomorrow-and-in-the-future/#:~:text=The%20AI%20lifecycle%20impacts%20the,its%20environmental%20footprint%20will%20escalate)). On the data center side, operators are using **liquid cooling and advanced cooling designs** to reduce the power needed for cooling. Some new systems cool chips directly (at the server rack or chip level) rather than chilling whole rooms, which improves efficiency. For example, Microsoft in 2024 launched a **“zero-water” cooling design that uses a closed-loop liquid system**, eliminating evaporative cooling. Each such data center can save over **125 million liters of water per year** by not using fresh water for cooling ([Sustainable by design: Next-generation datacenters consume zero water for cooling | The Microsoft Cloud Blog](https://www.microsoft.com/en-us/microsoft-cloud/blog/2024/12/09/sustainable-by-design-next-generation-datacenters-consume-zero-water-for-cooling/#:~:text=Beginning%20in%20August%202024%2C%20Microsoft,water%20per%20year%20per%20datacenter)). Microsoft reports this and other optimizations have already improved its data centers’ water efficiency by **39% (WUE down to 0.30 L/kWh)** in recent years ([Sustainable by design: Next-generation datacenters consume zero water for cooling | The Microsoft Cloud Blog](https://www.microsoft.com/en-us/microsoft-cloud/blog/2024/12/09/sustainable-by-design-next-generation-datacenters-consume-zero-water-for-cooling/#:~:text=We%20measure%20water%20efficiency%20through,actively%20reduce%20water%20wastage%2C%20expand)).

- **Renewable Energy and Carbon Offsets:** A direct way to cut AI’s carbon footprint is to power it with clean energy. Major cloud providers are increasingly investing in renewable power for their data centers. Microsoft, Google, Amazon, and others have pledged to reach **100% carbon-free or renewable energy for data centers by 2030** (with some claiming to already match 100% of their usage with renewable purchases today) ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Renewable%20energy%20use)). Google reports that its data centers already offset *all* their electricity with renewables ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=According%20to%20Microsoft%2C%20all%20the,their%20energy%20from%20renewable%20sources)), and Microsoft aims to run on **100% renewable power by 2025** for its cloud operations ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Renewable%20energy%20use)). Additionally, companies are using tools to monitor and manage emissions – for example, Microsoft’s Azure **Emissions Impact Dashboard** helps cloud customers track the CO₂ from their AI workloads ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=You%20can%E2%80%99t%20solve%20a%20problem,users%20to%20calculate%20their%20cloud%E2%80%99s)). Such transparency and reporting is increasingly encouraged, so that organizations can **select lower-carbon options** (like scheduling jobs in regions or times when green energy is abundant) and purchase carbon offsets for the remainder. Researchers have even developed independent trackers to measure AI training energy and emissions for academic models, pushing for more open reporting of AI’s environmental impact ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=You%20can%E2%80%99t%20solve%20a%20problem,users%20to%20calculate%20their%20cloud%E2%80%99s)).

- **Intelligent Scheduling and Optimization:** Efficiency isn’t just about hardware – *when* and *how* we run AI jobs can make a difference. Strategically scheduling AI computations for times of lower demand or cooler ambient temperatures can reduce stress on the grid and cooling systems ([How to manage AI's energy demand — today and in the future | World Economic Forum](https://www.weforum.org/stories/2024/04/how-to-manage-ais-energy-demand-today-tomorrow-and-in-the-future/#:~:text=Research%20is%20emerging%20about%20the,longer)). For instance, non-urgent training jobs could run overnight or in cooler seasons to save on air conditioning energy ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=He%20is%20also%20currently%20researching,computers%20need%20to%20run%20quickly)). *Dynamic scaling* of cloud resources is another tactic: scaling servers down when demand lulls so they don’t waste energy idling ([AI Energy Consumption: How Much Power AI Models Like GPT-4 Are Using (New Stats) | PatentPC](https://patentpc.com/blog/ai-energy-consumption-how-much-power-ai-models-like-gpt-4-are-using-new-stats#:~:text=Some%20ways%20to%20manage%20this,include)). Some data centers use AI itself to optimize operations – Google famously applied DeepMind AI to its HVAC controls and achieved a **40% reduction in cooling energy** ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=various%20industries%2C%20so%20why%20not,it%20to%20its%20own%20operations)). That not only saves electricity but also the associated water for cooling. Similarly, AI-driven predictive maintenance can detect cooling inefficiencies or leaks early, preventing waste ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=,like%20solar%20and%20wind%2C%20which)). In essence, there’s a feedback loop where AI can be used to improve the sustainability of AI operations.

- **Innovations in Cooling and Water Recycling:** Given AI’s heavy water usage, companies are innovating on that front too. Apart from the zero-water cooling mentioned, data center operators are exploring using **recycled or non-potable water** for cooling instead of tapping municipal fresh water ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=various%20industries%2C%20so%20why%20not,it%20to%20its%20own%20operations)). Some are locating data centers near large water sources or in cooler climates to reduce cooling needs. Others experiment with **submersion cooling** (immersing servers in special fluids) to drastically cut both electricity and water required for cooling. These efforts aim to curb AI’s **“hidden thirst”** so that even as compute grows, it doesn’t dry up local water supplies.

The **case of BLOOM vs GPT-3** illustrates multiple sustainability strategies in action. BLOOM is an open large language model with 176 billion parameters, comparable in size to GPT-3. By training BLOOM on a French supercomputer largely powered by nuclear (low-carbon) energy, the project kept its emissions to just **25 metric tons of CO₂ for 433 MWh of energy used ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Moving%20large%20jobs%20to%20data,tons%20of%20carbon%20dioxide%20equivalent))**. In contrast, GPT-3’s training on a mostly fossil-powered grid produced **502 tCO₂ from 1,287 MWh ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Moving%20large%20jobs%20to%20data,tons%20of%20carbon%20dioxide%20equivalent))**. In other words, BLOOM achieved a similar scale with **~5% of the carbon footprint** of GPT-3 by leveraging cleaner energy and efficient infrastructure. This kind of case study underscores that **where and how** we train models can make a huge difference. 

Finally, the AI community is increasingly aware of these issues. Workshops on “Green AI” and energy-efficient machine learning have emerged, and conferences now encourage authors to report energy usage for new models. There is recognition that progress in AI should be measured not only in accuracy or capability but also in **compute efficiency**. As one expert put it, we’re entering a phase where we must **“be aware of the energy usage…and take that into our calculations of whether we should be doing it”** ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=%E2%80%98amazed%20by%20what%20we%20can,%E2%80%9D)). In response, researchers are developing tools to estimate and **budget the carbon cost** of AI projects upfront, and exploring techniques to **“stop early”** in training when additional cycles yield diminishing returns ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Another%20area%20of%20Stein%E2%80%99s%20research,The%20challenge%20is)). All these efforts, from efficient algorithms and hardware to green energy and cooling, are aimed at **bending the curve** of AI’s environmental impact. The goal is to enable continued AI innovation while ensuring its energy and resource demands become sustainable in the long run ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=KEY%20TAKEAWAYS)) ([How to manage AI's energy demand — today and in the future | World Economic Forum](https://www.weforum.org/stories/2024/04/how-to-manage-ais-energy-demand-today-tomorrow-and-in-the-future/#:~:text=,AI%20and%20the%20green%20transition)).




**Sources:** Recent analyses and case studies on AI energy use ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=great%20deal%20of%20computation%20resources,4)) ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=NVIDIA%E2%80%99s%20A100%20GPU%2C%20used%20in,less%20energy%20than%20previous%20generations)) ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=The%20main%20determinant%20of%20AI,to%20match%20the%20pace%20of)) ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=sources%20of%20energy%20that%20result,of%20extra%20burden%20this%20will)) ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Moving%20large%20jobs%20to%20data,tons%20of%20carbon%20dioxide%20equivalent)) ([Artificial intelligence technology behind ChatGPT was built in Iowa — with a lot of water | AP News : r/Iowa](https://www.reddit.com/r/Iowa/comments/16gbhw6/artificial_intelligence_technology_behind_chatgpt/#:~:text=disclosure)) ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=,footprint%20an%20increasingly%20urgent%20issue)) ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=Let%E2%80%99s%20break%20it%20down%20further,about%20500%20milliliters%20of%20water)) ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=It%E2%80%99s%20like%20filling%20up%20a,speed%20we%E2%80%99ve%20come%20to%20expect)) ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Today%20data%20centers%20run%2024%2F7,those%20of%20the%20aviation%20industry)) ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Northeastern%20University%20and%20MIT%20researchers,our%20societies%20much%20more%20difficult)) ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=Apart%20from%20carbon%20emissions%2C%20the,degradation%20but%20also%20geopolitical%20tension)) ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=There%E2%80%99s%20a%20causal%20relationship%20between,industry%20may%20consume%20more%20energy)), and industry reports on sustainable AI practices ([Understanding AI Energy Consumption: Trends and Strategies](https://www.eweek.com/artificial-intelligence/ai-energy-consumption/#:~:text=the%20AI%20development%20community)) ([Sustainable by design: Next-generation datacenters consume zero water for cooling | The Microsoft Cloud Blog](https://www.microsoft.com/en-us/microsoft-cloud/blog/2024/12/09/sustainable-by-design-next-generation-datacenters-consume-zero-water-for-cooling/#:~:text=Beginning%20in%20August%202024%2C%20Microsoft,water%20per%20year%20per%20datacenter)) ([AI’s hidden thirst or how much water does Artificial Intelligence really drink? – Solveo](https://solveo.co/ais-hidden-thirst-or-how-much-water-does-artificial-intelligence-really-drink/#:~:text=various%20industries%2C%20so%20why%20not,it%20to%20its%20own%20operations)) ([AI’s Growing Carbon Footprint – State of the Planet](https://news.climate.columbia.edu/2023/06/09/ais-growing-carbon-footprint/#:~:text=Renewable%20energy%20use)).
