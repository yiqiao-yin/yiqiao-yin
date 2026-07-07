# Yin's Profile:

## Brief
<b>Principal AI Engineer · I build, ship, and lead production AI/ML systems.</b> 🚀

I have led applied AI/ML since 2015 (and data science since 2014), delivering production solutions across Computer Vision, NLP, and today's Large Language Models and Generative AI. My focus is end to end: I <b>architect, build, and ship full-stack, production-grade AI platforms</b>, from the frontend through inference down to the cloud infrastructure beneath. I am currently a Principal AI Engineer at <a href="https://www.fico.com/">FICO</a>, a global data analytics leader in credit scoring, where I <b>lead GenAI engineering</b> and ship customer-facing LLM copilots for enterprise and Tier-1 banking environments under strict compliance and data-residency constraints. 📊🔢

Previously, I was Tech Lead at <a href="https://www.vertexinc.com/">Vertex Inc</a> (global tax technology), Senior ML Engineer at S&P 500 company <a href="https://www.labcorp.com/">LabCorp</a> (AI for drug diagnostics, drug development, and operations across life sciences 🧠🔬), enterprise Data Scientist at EURO STOXX 50 company <a href="https://www.bayer.com/en/agriculture">Bayer</a>, Quantitative Researcher (apprenticeship) at hedge fund <a href="https://www.aqr.com/">AQR</a>, and Equity Trader at <a href="https://t3trading.com/">T3 Trading</a> on Wall Street (briefly <a href="https://brokercheck.finra.org/individual/summary/6338834">Series 56</a> licensed by FINRA). 💼📈

Beyond engineering, I <b>advise and consult</b> on enterprise AI strategy and delivery, teach and <b>mentor</b> as a Clinical Assistant Professor and independent mentor (with mentees earning peer-reviewed publications and international science-fair awards), and supervise a small AI fund (since 2011 now managing 7-figure AUM) spanning equities, cryptocurrencies, and real estate. I also run a monetized <a href="https://youtube.com/YiqiaoYin/">YouTube channel</a> on applied AI and publish research in representation learning (feature learning, deep learning, CV, NLP) and empirical asset pricing. 🤖📉

<i>Academic foundation:</i>MBA from University of [Chicago Booth School of Business](https://www.chicagobooth.edu/), PhD in Statistics at [Columbia University](https://www.columbia.edu/), B.A. in Mathematics and M.S. in Finance from the University of Rochester. 🎓

<sub>More at [y-yin.io](https://www.y-yin.io/) · [GitHub](https://github.com/yiqiao-yin) · [LinkedIn](https://www.linkedin.com/in/yiqiaoyin) · [YouTube](https://www.youtube.com/@YiqiaoYin)</sub>

- Google scholar: [https://scholar.google.com/citations?hl=en&user=Ju6m_O4AAAAJ](https://scholar.google.com/citations?hl=en&user=Ju6m_O4AAAAJ)
- Personal site: [https://www.y-yin.io/](https://www.y-yin.io/)
- YouTube: [https://www.youtube.com/@YiqiaoYin](https://www.youtube.com/@YiqiaoYin)
- LinkedIn: [https://www.linkedin.com/in/yiqiaoyin](https://www.linkedin.com/in/yiqiaoyin)

For more published work by Yiqiao, please check out the site [https://www.y-yin.io/](https://www.y-yin.io/) under 'Research'.

## 🛠️ Build + Ship: Production AI Systems

Beyond research and modeling, I design, build, and deploy **full-stack, production-grade AI platforms** end to end: from the frontend, through inference, down to the cloud infrastructure underneath. Across several systems spanning regulated fintech and consumer AI, I have repeatedly taken agentic and LLM-powered products from architecture to live deployment at enterprise scale. 🚀

### Representative platforms

- **[Clawdeck](https://clawdeck-app.com)** (agentic cloud-compute platform): gives an AI agent its own **isolated, disposable cloud desktop** with sandboxed code execution and on-demand GPU, where credentials are brokered *outside* the sandbox for a safe execution model. Built and operated solo.
- **[Alpha Seentio](https://app-seentio.com)** (AI-native investment-research platform): pairs LLM reasoning with **two-way MCP tool-calling**, live brokerage integration, and strategy backtesting, exposing structured financial workflows to an agent. Built and operated solo.
- **Enterprise banking copilot** (delivered into customer environments): a customer-facing LLM assistant deployed **multi-cloud and multi-tenant** into the clouds of **Tier-1 banks**, engineered to satisfy strict **banking compliance, data-residency, and tenant-isolation** requirements. Delivering AI into someone else's regulated cloud, not just my own.
- **Internal AI productivity platform**: an **LLM / MCP gateway** and full-stack chat platform serving **700+ engineers and product managers** behind a zero-trust service mesh.

### Architecture and infrastructure patterns

Patterns I apply across these systems:

- **Cloud-native on Kubernetes (EKS):** Helm-deployed services, autoscaling with **HPA + Karpenter**, stateless pods, and spot-node cost optimization.
- **Async, event-driven backends:** `API → SQS → Worker → Redis` pipelines for long-running agentic jobs, with Redis pub/sub fan-out to WebSockets for live results, plus buffering, retries, and horizontal scale.
- **Managed LLM access:** provider gateways (AWS **Bedrock**, Anthropic) with **IRSA**-scoped credentials, token metering, and per-user rate limiting.
- **Zero-trust service networking:** **Istio** service mesh with **mTLS**, **JWT / Okta** auth, secrets isolation, and credential-brokering so execution environments never hold keys.
- **Agent tooling and interop:** two-way **MCP** (server + client), FastMCP streamable-HTTP, and **OAuth 2.1 / JWT-scoped** tool access.
- **Sandboxed and GPU compute:** ephemeral execution via **E2B / RunPod**, multi-GPU provisioning (RTX → A100 / H100), and full sandbox lifecycle management (boot, hydrate, drive, sync, reap).
- **Data and storage:** **DynamoDB**, **S3**, and **Redis**, separating durable state from ephemeral real-time coordination.
- **Full-stack delivery:** **SvelteKit / React** frontends through **FastAPI** services to the infrastructure above, architected, built, and operated solo or as lead.

### Stack at a glance

`Python` · `FastAPI` · `SvelteKit / React` · `AWS (EKS, Bedrock, SQS, DynamoDB, S3, IRSA)` · `Kubernetes` · `Helm` · `Istio` · `Redis` · `Karpenter` · `E2B / RunPod` · `MCP` · `OAuth 2.1` · `Okta` · `JFrog`

### View about stock market:
Yiqiao believed that stock market is mostly fairly efficient. Many research groups and companies are doing great things out there with advanced tools. However, market does get "noisy" once in a while and that breeds opportunity. Yiqiao personally trades off a momentum strategy and he has his own market timing algorithm. This app [https://huggingface.co/spaces/eagle0504/technical-trader](https://huggingface.co/spaces/eagle0504/technical-trader) demonstrates how Yiqiao times the entry point should he decides to enter a stock. This app [https://huggingface.co/spaces/eagle0504/Momentum-Strategy-Screener](https://huggingface.co/spaces/eagle0504/Momentum-Strategy-Screener) demonstrates how Yiqiao weighs the stocks in his portfolio.

### View about AI:
Yiqiao has good faith in today's advancement of AI technology and is a big supporter of AI-backed technology to boost business operation and enhance corporate strategy. Many clients and companies Yiqiao worked with in the past led him to conclude that 'AI alone may falter and stray, but built around a corporate strategy, it paves the way.'

## Apps
Yiqiao built a series of AI-backed apps:
- GPT-4o demo: 'https://huggingface.co/spaces/eagle0504/gpt-4o-demo'
- Llama demo: 'https://huggingface.co/spaces/eagle0504/meta-llama'
- Software-as-a-Service or SAAS demo: 'https://huggingface.co/spaces/eagle0504/saas-template'
- Technical Trader (a timing strategy) demo: 'https://huggingface.co/spaces/eagle0504/stable-audio-demo'
- Momentum Strategy (a trading algorithm) demo: 'https://huggingface.co/spaces/eagle0504/Momentum-Strategy-Screener'
- Stable Audio demo: 'https://huggingface.co/spaces/eagle0504/stable-audio-demo'
- Duel Agent Simulation (a chain of thoughts/abstraction) demo: 'https://huggingface.co/spaces/eagle0504/duel-agent-simulation'
- Intelligent Document Processing demo: 'https://huggingface.co/spaces/eagle0504/IDP-Demo'

## Yin's Research and Watchlist on SEC Filings:

<!-- big list starts here -->

### Representation Learning

#### Papers

- 2024-04 | **Yiqiao Yin** (2024), Vision Augmentation Prediction Autoencoder with Attention Design (VAPAAD), _arXiv preprint arXiv:2404.10096_: [ArXiv](https://arxiv.org/abs/2404.10096)
- 2024-04 | Vivian Liu, **Yiqiao Yin** (2024), Green AI: Exploring Carbon Footprints, Mitigation Strategies, and Trade Offs in Large Language Model Training, _arXiv preprint arXiv:2404.01157_: [ArXiv](https://arxiv.org/abs/2404.01157)
- 2024-03 | Keshav Rangan, **Yiqiao Yin** (2024), A Fine-tuning Enhanced RAG System with Quantized Influence Measure as AI Judge, _arXiv preprint arXiv:2402.17081_: [ArXiv](https://arxiv.org/abs/2402.17081)
- 2023-02 | Xuan Di, **Yiqiao Yin**, Yongjie Fu, Zhaobin Mo, Shaw-Hwa Lo, Carolyn DiGuiseppi, David W. Eby, Linda Hill, Thelma J. Mielenz, David Strogatz, Minjae Kim, Guohua Li (2023), Detecting mild cognitive impairment and dementia in older adults using naturalistic driving data and interaction-based classification from influence score (Feb., 2023), _Artificial Intelligence in Medicine_, 102510: [Print](https://www.sciencedirect.com/science/article/pii/S0933365723000246)
- 2023-01 | Jaiden Shraut, Leon Liu, Jonathan Gong, **Yiqiao Yin** (2023), A Multi-Output Network with U-net Enhanced Class Activation Map and Robust Classification Performance for Medical Imaging Analysis (Jan., 2023), _Discover Artificial Intelligence_, 3(1): [Print](https://link.springer.com/article/10.1007/s44163-022-00045-1), [Media](https://www.scientia.global/yiqiao-yin-seeing-deep-into-the-lungs-with-deep-learning/)
- 2022-11 | Kieran Pichai, Benjamin Park, Aaron Bao, **Yiqiao Yin** (2022), Automated Segmentation and Classification of Aerial Forest Imagery, _Analytics_, 1(2), 135-143: [Print](https://www.mdpi.com/2813-2203/1/2/10), [Media](https://www.scientia.global/yiqiao-yin-tracking-deforestation-with-neural-networks/)
- 2022-08 | **Yiqiao Yin** (2022+), AI4ALL and K12 AI Education: [Preprint](https://wyn-associates.s3.amazonaws.com/public/research/economics/art-of-money-management.pdf)
- 2022-01 | Shaw-hwa Lo and **Yiqiao Yin** (2022), An I-score Review Paper - A Novel Approach to Adopt Explainable Artificial Intelligence (Jan., 2022), _Adv. Mach. Learn. Art. Inte._, 3(1), 01-11: [Print](https://opastpublishers.com/open-access/a-novel-approach-to-adopt-explainable-artificial-intelligence-in-x-ray-image-classification.pdf)
- 2021-12 | Shaw-hwa Lo and **Yiqiao Yin** (2021), An Interaction-based Recurrent Neural Network (IRNN) (Dec., 2021), _Mach. Learn. Knowl. Extr_., 3(4), 922-945: [ArXiv](https://arxiv.org/abs/2112.02997), [Print](https://www.mdpi.com/2504-4990/3/4/46)
- 2021-12 | Shaw-hwa Lo and **Yiqiao Yin** (2021), An Interaction-based Convolutional Neural Network (ICNN) (Dec., 2021), _Algorithms_, 14(11), 337: [ArXiv](https://arxiv.org/abs/2106.06911), [Print](https://www.mdpi.com/1999-4893/14/11/337)
- 2021-12 | Shaw-hwa Lo and **Yiqiao Yin** (2021), A Novel Interaction-based Method (Dec., 2021), _Discover Artificial Intelligence_, 1(16): [ArXiv](https://arxiv.org/abs/2104.12672), [Print](https://link.springer.com/article/10.1007/s44163-021-00015-z)

#### Conferences

- 2024-01 | Xuan Di, **Yiqiao Yin**, Yongjie Fu, Zhaobin Mo, Shaw-Hwa Lo, Carolyn DiGuiseppi, David W. Eby, Linda Hill, Thelma J. Mielenz, David Strogatz, Minjae Kim, Guohua Li (2024), Detecting mild cognitive impairment and dementia in older adults using naturalistic driving data and interaction-based classification from influence score, _The 103rd Transportation Research Board (TRB) Annual Meeting_: [Link](https://annualmeeting.mytrb.org/OnlineProgram/Details/21137)
- 2023-04 | Leon Liu, **Yiqiao Yin** (2023), Towards Explainable AI on Chest X-Ray Diagnosis Using Image Segmentation and CAM Visualization (Mar, 2023), _FICC 2023: Advances in Information and Communication_, pp 659-675: [Link](https://link.springer.com/chapter/10.1007/978-3-031-28076-4_48), [Print](https://wyn-associates.s3.amazonaws.com/public/research/representation_learning/FICC2023Vol1.pdf)
- 2022-11 | Leon Liu, **Yiqiao Yin** (2022), Towards Explainable AI on Chest X-Ray Diagnosis using Image Segmentation and CAM Visualization (Nov, 2022), _Third Symposium on Knowledge-Guided ML (KGML-AAAI-22)_, Held as part of AAAI Fall Symposium Series (FSS) 2022 in November: [Link](https://sites.google.com/vt.edu/kgml-aaai-22), scheduled on Day 2 Session 5 at 2PM EST at Westin Arlington Gateway, Room **Fitzgerald D**, Arlington, VA
- 2022-10 | **Yiqiao Yin** (credit to Edna Williams) (2022), A Machine Learning based Enrollment Forecasting System (Oct, 2022), _OHDSI_: [OHDSI](https://www.ohdsi.org/2022showcase-97/), [Oct. 14 Agenda](https://www.ohdsi.org/wp-content/uploads/2022/10/OHDSI2022-Agenda.pdf)
- 2022-02 | **Yiqiao Yin** (2022), XAI in Healthcare: A Novel XAI Approach Towards Radiology Image Classification: [AAAI 22' Workshops](https://aaai.org/Conferences/AAAI-22/ws22workshops/#ws37), [W37 Home](https://taih21.github.io/), [Poster](https://wyn-associates.s3.amazonaws.com/public/research/representation_learning/aaai_22__workshop_w37_poster.pdf), [Presentation](https://wyn-associates.s3.amazonaws.com/public/research/representation_learning/aaai_22__workshop_w37_presentation.pdf) | Venue details: [AAAI 22' Schedule Home](https://aaai-2022.virtualchair.net/index.html), [AAAI 22' Workshop Page](https://aaai-2022.virtualchair.net/events_workshops.html) (My talk is in W37: Trustworthy AI in Healthcare) | Updated [slides](https://wyn-associates.s3.amazonaws.com/public/research/representation_learning/tech-discussion-2022-4-20.pdf)

#### Selected Awards/Paper/Work from My Students

- 2023-12 | Kieran Pichai **Yiqiao Yin** as mentor (2023), A Retrieval-Augmented Generation Based Large Language Model Benchmarked On a Novel Dataset, _Journal of Student Research_, 12(4): [Print](https://www.jsr.org/hs/index.php/path/article/view/6213)
- 2023-12 | Yash Bingi, **Yiqiao Yin** as mentor (2023), Using Machine Learning to Classify Fetal Health and Analyze Feature Importance, _1st Place by US Agency for International Development in the Regeneron International Science and Engineering Competition and the 4th Place in the Massachusetts Science & Engineering Fair (MSEF)_: [Site](https://www.sefmd.org/Awards/2023/Professional%20Awards%20by%20Student.pdf)
- 2023-05 | Jonathan Gong, **Yiqiao Yin** as mentor (2023), COVID-19 Chest X-ray Image Classification and Improved U-Net Segmentation, _Excellence Award - Silver at the Canada-Wide Science Fair (CWSF)_: [Site](https://www.sciencefairs.ca/news/2023/cwsf-concludes-in-edmonton/)
- 2023-03 | Aarav Monga, **Yiqiao Yin** as mentor (2023), A For-Profit Model of Microcredit, _Journal of Student Research_, 11(1): [Print](https://www.jsr.org/hs/index.php/path/article/view/2378)

#### Books

- 2023-12 | **Yiqiao Yin** (2023), AI Decoded: Making Sense of Deep Learning and Generative AI (Dec., 2023): [Book sale on Amazon](https://www.amazon.com/dp/B0CNJDWYXW), see slides [here](https://wyn-associates.s3.amazonaws.com/public/research/education/AI_Decoded__Yin_2024.pdf)
- 2023-06 | **Yiqiao Yin** (2023), Understand Asset Prices Using Empirical Studies (Jun., 2023): [Book sale on Amazon](https://www.amazon.com/dp/9994988417)
- 2022-05 | **Yiqiao Yin** (2022), Towards Explainable Artificial Intelligence Using Interaction-based Representation Learning (May, 2022): [Book sale on Amazon](https://www.amazon.com/dp/9994980157)
- 2022-04 | **Yiqiao Yin** (credit to Professor Shaw-hwa Lo) (2022), Fundamentals of Interaction-based Learning (Apr., 2022): [Book sale on Amazon](https://www.amazon.com/dp/163648641X)

### Economics

- Yin (2017), Art of Money Management: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/economics/art-of-money-management.pdf)
- Yin (2016), Trade Dynamics with Endogenous Contact Rate: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/economics/trade-dynamics-with-endogenous-contact-rate.pdf)

### Empirical Asset Pricing

- Yin (2016), Empirical Study on Greed: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/empirical_asset_pricing/empirical-study-on-greed.pdf)
- Yin (2015), Empirical Study on MVBS: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/empirical_asset_pricing/empirical-study-on-mvbs.pdf)
- Yin (2015), Cross-sectional Study on Stock Returns to Future Expectation Theorem: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/empirical_asset_pricing/cross-section-study-on-stock-returns-to-future-expectation-theorem.pdf)
- Yin (2015), Alternative Empirical Study on Market Value Balance Sheet: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/empirical_asset_pricing/alternative-empirical-study-on-market-value-balance-sheet.pdf)
- Yin (2014), How to Understand Future Returns of a Security: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/empirical_asset_pricing/how-to-understand-future-returns-of-a-securityef80a5-revised-2014.pdf)

### Trading

- Yin (2020), Buy Signal from Limit Theorem: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/trading/buy-signal-from-limit-theorem.pdf)
- Yin (2020), Buy Signal from Limit Theorem: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/trading/buy_signal_from_limit_theorem-yin.pdf)
- Yin (2017), Time Series Analysis on Stock Returns: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/trading/time-series-analysis-on-stock-returns.pdf)
- Yin (2016), Martingale to Optimal Trading: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/trading/martingale-to-optimal-trading.pdf)
- Yin (2016), Anomaly Correction by Optimal Trading Frequency: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/trading/anomaly-correction-by-trading-frequency.pdf), [Slide](https://wyn-associates.s3.amazonaws.com/public/research/trading/slide_anom_corr_by_trad_freq.pdf)
- Yin (2016), Absolute Alpha with Moving Averages: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/trading/absolute-alpha-with-moving-averages.pdf), [Slide](https://wyn-associates.s3.amazonaws.com/public/research/trading/slide_abs_alpha_mov_ave.pdf)
- Yin (2016), Absolute Alpha with Limited Leverage: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/trading/absolute-alpha-with-limited-leverage.pdf)
- Yin (2015), Absolute Alpha by Beta Manipulation: [PDF](https://wyn-associates.s3.amazonaws.com/public/research/trading/absolute-alpha-by-beta-manipulation.pdf)
