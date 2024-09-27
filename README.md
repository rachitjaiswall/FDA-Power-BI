# FDA-Power-BI

This dataset contains information related to adverse events reported to the FDA (Food and Drug Administration) involving various products, primarily focusing on food items. Each row represents a unique adverse event, detailing the event's associated product, outcomes, and symptoms experienced by the affected individual.

File Structure
The dataset is structured into the following columns:

RA_Report #:
A unique identifier for each adverse event report.

RA_CAERS Created Date:
The date when the adverse event report was created in the FDA CAERS (Center for Food Safety and Applied Nutrition Adverse Event Reporting System).

AEC_Event Start Date:
The date when the adverse event occurred. In some cases, this field might be missing.

PRI_Product Role:
Specifies the product's role in the event (e.g., "Suspect").

PRI_Reported Brand/Product Name:
The reported brand or product name associated with the adverse event.

PRI_FDA Industry Code:
The FDA industry code corresponding to the type of product involved in the event.

PRI_FDA Industry Name:
The FDA industry name associated with the product (e.g., "Bakery Prod/Dough/Mix/Icing", "Baby Food Prod", etc.).

CI_Age at Adverse Event:
The age of the individual at the time of the adverse event.

CI_Age Unit:
The unit of measurement for the individual's age (e.g., "Year(s)", "Month(s)").

AEC_One Row Outcomes:
A description of the outcomes from the adverse event, which may include:

VISITED AN ER: The individual visited an emergency room.
VISITED A HEALTH CARE PROVIDER: The individual sought medical help from a healthcare provider.
REQ. INTERVENTION TO PRVNT PERM. IMPRMNT.: The event required medical intervention to prevent permanent impairment.
HOSPITALIZATION: The individual was hospitalized.
NON-SERIOUS INJURIES/ILLNESS: The event resulted in non-serious injuries or illness.
DEATH: The event resulted in the individual's death.
SYM_One Row Coded Symptoms:
A description of the symptoms experienced during the adverse event. Examples of symptoms include "SWELLING FACE", "RASH", "COUGH", "DYSPNOEA", "CHOKING", "VOMITING", etc.
Data Notes:
Some records have missing data, such as missing event start dates or ages.
The dataset captures both serious and non-serious adverse events.
The information may include both direct and indirect impacts of the products consumed or used.
Usage
This dataset is intended to be used for analyzing adverse events associated with various products reported to the FDA. It can help in understanding product safety trends, identifying high-risk products, and improving consumer safety awareness.
