# Financial Statements - Reconstruct-Model (Analytics-Engineer)

##  Why we are doing this 
In the finance world, many analytical assignments and real-world engagement start with using only the published financial statements (PDFs, Excel, Power BI screenshots).The General Ledger (GL) is often unavailable for confidentiality or access reasons. Those formatted reports are human-readable but not analysis-ready (they are not SQL friendly).

This repository shows a repeatable, auditable process to extract and canonicalize those reports into a tidy, analytics-ready star schema (while maintaining data quality) where the grain is one account × one fiscal period by using dimensional modeling and ragged-hierarchy mapping so analysts (and non-technical stakeholders) can run CFO-grade trends, reconciliations and drilldowns without access to the raw General Ledger (GL).


