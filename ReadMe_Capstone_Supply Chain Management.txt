

Business Context:
A fast-moving consumer goods (FMCG) company that entered the instant noodles market two years ago is facing challenges in balancing demand and supply across its warehouses nationwide. In some regions, demand far exceeds supply, while in others, excess inventory is leading to wastage and higher costs. This mismatch results in significant inventory losses and missed sales opportunities. To remain competitive and profitable in the highly dynamic FMCG sector, the company needs a data-driven approach to optimize its supply chain and align production with regional demand patterns.



Objective:
As a data scientist, you are tasked with building a predictive model using historical sales and supply data to determine the optimum quantity of product to ship to each warehouse. Additionally, analyzing demand patterns across different regions will help management design targeted advertisement campaigns. Solving this problem will enable the company to minimize inventory costs, reduce stockouts, and drive higher sales through better demand forecasting and efficient supply chain management.



Data Description:
The dataset contains information about the historical sales patterns. The detailed data dictionary is given below:

Ware_house_ID: Product warehouse ID

WH_Manager_ID: Employee ID of warehouse manager

Location_type: Location of the warehouse, like in a city or a village

WH_capacity_size: Storage capacity size of the warehouse

zone: Zone of the warehouse

WH_regional_zone: Regional zone of the warehouse under each zone

num_refill_req_l3m: Number of times refilling has been done in the last 3 months

transport_issue_l1y: Any transport issue, like an accident or goods stolen, reported in the last year

Competitor_in_mkt: Number of instant noodles competitors in the market

retail_shop_num: Number of retail shops that sell the product under the warehouse area

wh_owner_type: Company owns the warehouse, or they have rented the warehouse

distributor_num: Number of distributors working between the warehouse and retail shops

flood_impacted: Warehouse is in the flood-impacted area indicator

flood_proof: Warehouse is flood-proof. Like storage is at some height, not directly on the ground

electric_supply: The Warehouse has an electric backup, like a generator, so they can run the warehouse in load shedding

dist_from_hub: Distance between the warehouse to the production hub in Kms

workers_num: Number of workers working in the warehouse

wh_est_year: Warehouse established year

storage_issue_reported_l3m: Warehouse reported a storage issue to the corporate office in the last 3 months. Like rats, fungus due to moisture, etc.

temp_reg_mach: Warehouse has a temperature regulating machine indicator

approved_wh_govt_certificate: What kind of standard certificate has been issued to the warehouse from the government regulatory body

wh_breakdown_l3m: Number of times the warehouse faced a breakdown in the last 3 months. Like a strike by workers, a flood, or an electrical failure

govt_check_l3m: Number of times government officers have visited the warehouse to check the quality and expiry of stored food in the last 3 months

product_wg_ton: Product has been shipped in the last 3 months. Weight is in tons