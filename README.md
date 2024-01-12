# Text2SQL

**See the full model card for [sql-sodabot-v1.0 on HuggingFace](https://huggingface.co/kim-sha/sql-sodabot-v1.0)**.

This encoder-decoder model is a descendent of [Salesforce/codet5-small](https://huggingface.co/Salesforce/codet5-small), fine-tuned on a modified version of [b-mc2/sql-create-context](https://huggingface.co/datasets/b-mc2/sql-create-context) data. The original [CodeT5](https://github.com/salesforce/CodeT5) was published by Salesfoce Research as an "AI-powered coding assistant to boost the productivity of software developers". The goal of this project is to apply transfer learning in order to appropriate this model for text-to-SQL applications, specifically in the context of generating Socrata SQL ([SoQL](https://dev.socrata.com/docs/queries/)) queries that can be executed on the Socrata Open Data API (e.g., to analyze [NYC Open Data](https://opendata.cityofnewyork.us)).
