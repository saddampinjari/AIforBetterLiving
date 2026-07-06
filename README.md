🏙️ Urban Pulse Platform: Real-Time Traffic Telemetry Engine
The Urban Pulse Platform is an accelerated, AI-powered Decision Intelligence Engine engineered to optimize urban mobility, safety, and smart community infrastructure response.

By injecting an ultra-fast hardware-acceleration layer into a standard data engineering loop, this platform aggregates, filters, and analyzes massive streams of live city telemetry records in milliseconds, shifting municipal traffic management from slow historical batch processing to near-instantaneous autonomous intervention.

🚀 The Core Innovation & Outcomes
Data Processing Scale: Seamlessly ingests and maps a dense matrix of 10,000,000 real-time records.

The Hardware Breakthrough: Leverages parallel processing architectures on an NVIDIA T4 GPU container to isolate and filter 50,000 critical gridlock anomalies in a mere 0.0150 seconds (15 milliseconds).

Immediate Time-to-Insight: Replaces hour-long delay loops with sub-second, production-grade automated analytics, giving city dispatchers the ability to deploy active signal timing overrides the exact moment a bottleneck forms.

🛠️ Technical Architecture Stack
Acceleration Engine: NVIDIA RAPIDS (cudf.pandas running on a managed T4 GPU sandbox profile) for high-velocity, sub-second data manipulations.

Cloud Data Warehouse: Google Cloud BigQuery, serving as the scalable real-time sync for filtered traffic anomaly streams.

Generative AI Orchestration: Gemini Enterprise Agent Platform (gemini-2.5-flash endpoint) for text-based contextual reasoning and operational decision support.

Visualization Layer: Looker Studio, mapping regional system alerts using real-time geospatial scatter charts.

📂 System Pipeline Workflow
Ingestion & GPU Acceleration: 10 Million rows of time-series telemetry data are parsed and queried in under 0.02 seconds using GPU-accelerated frames.

Dynamic Syncing: Critical slowdown bottlenecks (segments verified under 15 km/h) are instantly filtered out of the dense array and piped natively straight into BigQuery.

Autonomous Decision Support: The pipeline triggers a Vertex AI call, prompting Gemini to review the telemetry metrics and draft a high-priority, bulleted tactical operational alert bulletin for stakeholder deployment.

Geospatial Control Center Dashboard: Operators interact with a live, responsive Looker Studio data mapping grid that plots exact coordinates across a coordinates matrix.

🔗 Live Project Artifacts
Google Colab Workspace Pipeline: https://colab.research.google.com/drive/1u3LqHH_g-LJ57LybhksBW7bYiM0aveVl?usp=sharing

Interactive Looker Studio Dashboard: https://datastudio.google.com/reporting/f5fcee2d-dee0-4236-8215-9025a21e3348

3-Minute Project Demo Video: 
