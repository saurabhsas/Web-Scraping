# Web-Scraping
Web scraping : Data Extraction from National CSR Portal (India)

Background
The full form of CSR is Corporate Social Responsibility. The topic is largely discussed and deliberated in Indian society in recent years. CSR is a law in India. Under this law, corporates in the country must do social work. CSR is included in social work, which is necessary for the upliftment of society, to uplift the needy sections of society. 
The National Corporate Social Responsibility Data Portal is an initiative by Ministry of Corporate Affairs, Government of India to establish a platform to disseminate Corporate Social Responsibility related data and information filed by the companies registered with it.
https://www.csr.gov.in/

Following are the key-steps for web-crawling of CSR data from the portal: 
1). List of all the listed and unlisted companies from the portal (Copy & Paste) into excel sheets.
2). In above step we will get names of the companies. These names will help to extract CIN from the portal (web-crawling).
3). Next from this list of CIN (companies) can be used to crawl data for corresponding financial year(s): 2019-20 and collect data for following columns:
i.	CIN
ii.	Name of the Company

iii.	Class
iv.	Company Type
v.	Listing Status
vi.	RoC
vii.	State of Registration

viii.	Sub Category
ix.	Average Net Profit 
x.	CSR Prescribed Expenditure 
xi.	CSR Spent 
xii.	Local Area Spent 
xiii.	Financial Year
xiv.	CSR Project
xv.	Development Sector
xvi.	State/Union Territory
xvii.	District
xviii.	Project Amount Outlay
xix.	Amount Spent
xx.	Mode of Implementation

4). Crawling codes can be run in multiple parts (or batches) for 22,531 CIN (companies).
5). After merging and appending of data, we can have a dataset from the CSR portal.
6). Next, we need to get the additional data from different other sources. Following is the list of additional data: 
I.	Social Sector Expenditure
II.	Health-Infrastructure
III.	Tendulkar Poverty Estimates (Combined)
IV.	Primary Education Indicators
V.	State & UT-wise Prevention of Corruption Act & related Sections of IPC Cases Reported from 2014 to 2019
VI.	Nominal GSDP Series
VII.	State-wise Total Population

7). Finally, we can merge the dataset of CSR portal (step5) with Additional data (step 6) and our final Dataset is ready to be shared.

Python Packages:
For the entire crawling activity Python codes with Jupyter notebooks can be used.
Key Libraries: Pandas, requests and BeautifulSoup

