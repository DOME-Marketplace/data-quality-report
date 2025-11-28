# TMForum Object Validation Report

**Generated:** 2025-11-28 10:41:13 UTC

**Configuration:**
- Base URL: `https://tmf.dome-marketplace-sbx.org`
- Object Types: resource, resourceCatalog, resourceFunction, settlementAccount, usageSpecification, customerBillOnDemand, heal, productOfferingPrice, productSpecification, appliedCustomerBillingRate, cancelResourceOrder, category, organization, partyRole, resourceCategory, resourceOrder, serviceCatalog, cancelServiceOrder, catalog, financialAccount, individual, productOrder, resourceCandidate, serviceCategory, billingAccount, customer, partyAccount, product, resourceSpecification, customerBill, migrate, monitor, quote, serviceCandidate, usage, billFormat, billPresentationMedia, billingCycleSpecification, productOffering, service, serviceOrder, serviceSpecification, agreement, agreementSpecification, cancelProductOrder, scale
- Timeout: 30 seconds
- Validate Required Fields: true
- Validate Related Party: true

## Summary Statistics

| Metric | Value |
|--------|-------|
| Total Objects | 1044 |
| Valid Objects | 277 |
| Invalid Objects | 767 |
| Total Errors | 1721 |
| Total Warnings | 2722 |
| Total Errors Fixed | 0 |
| Total Warnings Fixed | 0 |
| Processing Time | 176.181µs |

## Statistics by Object Type

| Object Type | Count | Valid | Invalid | Errors | Warnings | Errors Fixed | Warnings Fixed |
|-------------|-------|-------|---------|--------|----------|--------------|----------------|
| agreement | 3 | 3 | 0 | 0 | 6 | 0 | 0 |
| appliedCustomerBillingRate | 200 | 0 | 200 | 673 | 600 | 0 | 0 |
| billingAccount | 18 | 0 | 18 | 34 | 54 | 0 | 0 |
| category | 113 | 113 | 0 | 0 | 225 | 0 | 0 |
| customerBill | 47 | 4 | 43 | 124 | 141 | 0 | 0 |
| financialAccount | 1 | 0 | 1 | 1 | 3 | 0 | 0 |
| individual | 95 | 95 | 0 | 0 | 380 | 0 | 0 |
| organization | 27 | 27 | 0 | 0 | 97 | 0 | 0 |
| product | 39 | 1 | 38 | 91 | 117 | 0 | 0 |
| productOffering | 68 | 4 | 64 | 108 | 60 | 0 | 0 |
| productOfferingPrice | 145 | 8 | 137 | 137 | 239 | 0 | 0 |
| productOrder | 67 | 5 | 62 | 186 | 268 | 0 | 0 |
| productSpecification | 50 | 11 | 39 | 64 | 37 | 0 | 0 |
| quote | 19 | 3 | 16 | 35 | 76 | 0 | 0 |
| resource | 28 | 0 | 28 | 56 | 84 | 0 | 0 |
| resourceSpecification | 17 | 0 | 17 | 18 | 34 | 0 | 0 |
| service | 82 | 0 | 82 | 164 | 246 | 0 | 0 |
| serviceSpecification | 17 | 3 | 14 | 15 | 31 | 0 | 0 |
| settlementAccount | 1 | 0 | 1 | 1 | 3 | 0 | 0 |
| usageSpecification | 7 | 0 | 7 | 14 | 21 | 0 | 0 |

## Error Summary

| Error Code | Count |
|-------------|-------|
| MISSING_RELATED_PARTY_INFO | 1721 |

## Warning Summary

| Warning Code | Count |
|---------------|-------|
| MISSING_RECOMMENDED_FIELD | 2722 |

## Detailed Validation Results

### agreement Objects

#### Object: [urn:ngsi-ld:agreement:adc8a095-b1bd-471c-87f0-a49487618c7c](https://tmf.dome-marketplace-sbx.org/tmf-api/agreementManagement/v4/agreement/urn:ngsi-ld:agreement:adc8a095-b1bd-471c-87f0-a49487618c7c)

- **Type:** agreement
- **Valid:** true
- **Timestamp:** 2025-11-28 10:41:13 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to agreement (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:agreement:efffa430-8b52-4e9c-9e83-e1849ec9b162](https://tmf.dome-marketplace-sbx.org/tmf-api/agreementManagement/v4/agreement/urn:ngsi-ld:agreement:efffa430-8b52-4e9c-9e83-e1849ec9b162)

- **Type:** agreement
- **Valid:** true
- **Timestamp:** 2025-11-28 10:41:13 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to agreement (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:agreement:0d2c6b4e-7f36-454a-81d1-dcfe7fae9560](https://tmf.dome-marketplace-sbx.org/tmf-api/agreementManagement/v4/agreement/urn:ngsi-ld:agreement:0d2c6b4e-7f36-454a-81d1-dcfe7fae9560)

- **Type:** agreement
- **Valid:** true
- **Timestamp:** 2025-11-28 10:41:13 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to agreement (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### appliedCustomerBillingRate Objects

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:d93e128d-8fa2-49ad-a643-749d6e636fe7](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:d93e128d-8fa2-49ad-a643-749d6e636fe7)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:48ddac6d-f01b-42e1-965e-7e926d0b4915](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:48ddac6d-f01b-42e1-965e-7e926d0b4915)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:cc328443-4fbb-4ab1-98d9-d1ad9405d863](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:cc328443-4fbb-4ab1-98d9-d1ad9405d863)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:71a057cb-5e3b-4246-a299-f038687d2c66](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:71a057cb-5e3b-4246-a299-f038687d2c66)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:9d379ca9-58d5-4328-b980-5ba45e96d314](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:9d379ca9-58d5-4328-b980-5ba45e96d314)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:37de4f55-a8c3-409e-9856-bfc5bd8f85b4](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:37de4f55-a8c3-409e-9856-bfc5bd8f85b4)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:70094e7c-6190-403e-b5cd-a93047507b0a](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:70094e7c-6190-403e-b5cd-a93047507b0a)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:8ea8ee21-d86b-443a-8b4f-7afcdac75983](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:8ea8ee21-d86b-443a-8b4f-7afcdac75983)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:9339860a-f37a-4a99-a4da-16791de52296](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:9339860a-f37a-4a99-a4da-16791de52296)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:fd193128-6f0c-4f43-af4d-003a9d766158](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:fd193128-6f0c-4f43-af4d-003a9d766158)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:d9bec7ff-fa90-4f60-9af4-dc6ecd977132](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:d9bec7ff-fa90-4f60-9af4-dc6ecd977132)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:543820cc-f7dc-4488-8d2b-62a54386abf1](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:543820cc-f7dc-4488-8d2b-62a54386abf1)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:44608aec-c353-42f9-b998-d27e715fda7f](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:44608aec-c353-42f9-b998-d27e715fda7f)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:180bb66c-2dac-4c4d-957e-68fa962d643d](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:180bb66c-2dac-4c4d-957e-68fa962d643d)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:99daf6e4-5a97-4554-b6da-c5e5821aba9a](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:99daf6e4-5a97-4554-b6da-c5e5821aba9a)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:0f1787fd-768e-450a-922e-78114049041d](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:0f1787fd-768e-450a-922e-78114049041d)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:fafcea31-fd01-495f-bb18-509f489076fd](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:fafcea31-fd01-495f-bb18-509f489076fd)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:2346817f-e25f-48ae-8956-c0d83f71efe1](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:2346817f-e25f-48ae-8956-c0d83f71efe1)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:675165c7-64fc-4cfe-8bb3-eb33ede7bdf3](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:675165c7-64fc-4cfe-8bb3-eb33ede7bdf3)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:29452e37-7b0a-4704-9201-760e2b986250](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:29452e37-7b0a-4704-9201-760e2b986250)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:02f8dd56-00f4-4afe-88cb-77aa4ffcb24d](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:02f8dd56-00f4-4afe-88cb-77aa4ffcb24d)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:1b45ab72-14b3-4d57-8e0e-6d7659f19203](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:1b45ab72-14b3-4d57-8e0e-6d7659f19203)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:1ebbf946-fc97-4043-acf1-e8cb9b7006a2](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:1ebbf946-fc97-4043-acf1-e8cb9b7006a2)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:3bfa8108-1826-4812-803d-7698d24a8929](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:3bfa8108-1826-4812-803d-7698d24a8929)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7619966e-e9bd-44ab-a2b9-7357b0d912a6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7619966e-e9bd-44ab-a2b9-7357b0d912a6)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:8942dc14-0c69-43e5-ab28-602e9f74550d](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:8942dc14-0c69-43e5-ab28-602e9f74550d)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:924c6b62-9911-4928-af3e-b9947669d8f7](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:924c6b62-9911-4928-af3e-b9947669d8f7)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:32e45d7e-17a6-4c64-a3cd-e62f360969fe](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:32e45d7e-17a6-4c64-a3cd-e62f360969fe)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7dcfae86-35c8-4907-b805-0fdeca8779cb](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7dcfae86-35c8-4907-b805-0fdeca8779cb)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:e3c2cc97-64f6-4221-87d7-a6c889976dd2](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:e3c2cc97-64f6-4221-87d7-a6c889976dd2)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:fafa6f8f-502c-4fde-8c34-b0e4aa49be1f](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:fafa6f8f-502c-4fde-8c34-b0e4aa49be1f)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:03c22eb4-153d-425f-acff-4bce15e9aeb4](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:03c22eb4-153d-425f-acff-4bce15e9aeb4)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:e72279e7-92b5-45d3-a4ed-756dd85b867d](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:e72279e7-92b5-45d3-a4ed-756dd85b867d)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f9c270e8-527a-4c52-ab85-82f8d5a98447](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f9c270e8-527a-4c52-ab85-82f8d5a98447)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:a049386b-db21-4dbc-9cca-07af99553503](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:a049386b-db21-4dbc-9cca-07af99553503)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:1e6b40f0-443b-4f7d-afa2-2528f06e1f5f](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:1e6b40f0-443b-4f7d-afa2-2528f06e1f5f)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:0042dbdc-ae07-419f-9982-9b261e54604f](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:0042dbdc-ae07-419f-9982-9b261e54604f)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:6c9c73c5-6a76-4639-b0e8-b4ce17f1eef5](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:6c9c73c5-6a76-4639-b0e8-b4ce17f1eef5)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:55cf216c-1c24-4504-b373-e2e0463855dd](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:55cf216c-1c24-4504-b373-e2e0463855dd)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:30e8aa1a-6145-49b9-a783-ad390c345163](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:30e8aa1a-6145-49b9-a783-ad390c345163)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7cee803e-bb8a-42da-bacf-39d19e6e3ad8](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7cee803e-bb8a-42da-bacf-39d19e6e3ad8)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:52b6603e-0ad3-43b1-a46c-d712e948f69b](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:52b6603e-0ad3-43b1-a46c-d712e948f69b)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:9f50cc49-2fd1-43cb-a9f2-2d83056f66fb](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:9f50cc49-2fd1-43cb-a9f2-2d83056f66fb)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:fe274245-b684-4fa7-a1fd-b4f337439478](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:fe274245-b684-4fa7-a1fd-b4f337439478)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:2503bb12-3697-47cf-b865-5a0485c02e4a](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:2503bb12-3697-47cf-b865-5a0485c02e4a)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:0d2f5868-d09b-4dbc-b492-2ad9366d92f6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:0d2f5868-d09b-4dbc-b492-2ad9366d92f6)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:a27f10be-1e69-4929-aa18-e99eb928bf2f](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:a27f10be-1e69-4929-aa18-e99eb928bf2f)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:b6ff35ed-3a3a-438f-835c-cc183e12b695](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:b6ff35ed-3a3a-438f-835c-cc183e12b695)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:c57dc9a3-eb8e-4666-977c-2f30724d5370](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:c57dc9a3-eb8e-4666-977c-2f30724d5370)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:1579296d-5604-44a3-a5cb-31189de48c9e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:1579296d-5604-44a3-a5cb-31189de48c9e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:04ab6f53-c31e-4ba8-8418-5480f4611067](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:04ab6f53-c31e-4ba8-8418-5480f4611067)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:a3a8874f-d470-40f0-8fce-6066a1116e41](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:a3a8874f-d470-40f0-8fce-6066a1116e41)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:2553474f-8cf3-4153-8f5b-7d25291944c8](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:2553474f-8cf3-4153-8f5b-7d25291944c8)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:6eb117b8-34c8-406e-91d3-e74d758fe3af](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:6eb117b8-34c8-406e-91d3-e74d758fe3af)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:1aab4d06-0ad3-4aaa-8e86-06f794ee7254](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:1aab4d06-0ad3-4aaa-8e86-06f794ee7254)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:26b425d4-be54-410d-bb5c-7193f9545fd3](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:26b425d4-be54-410d-bb5c-7193f9545fd3)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:268bf2d5-968a-49d7-ad9f-3cdba22e2887](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:268bf2d5-968a-49d7-ad9f-3cdba22e2887)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:3a346b17-184c-429c-81ed-f2bdcae2015e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:3a346b17-184c-429c-81ed-f2bdcae2015e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:2f712ddd-0825-43ea-8196-b64e2727da14](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:2f712ddd-0825-43ea-8196-b64e2727da14)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:3f2ed19f-dfb3-4110-804f-037dd34e002e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:3f2ed19f-dfb3-4110-804f-037dd34e002e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:79ecfc63-030a-4c2f-ac01-d1dc664957cc](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:79ecfc63-030a-4c2f-ac01-d1dc664957cc)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:bb010b0a-3402-4e0a-bdb3-197ec04ede3b](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:bb010b0a-3402-4e0a-bdb3-197ec04ede3b)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:949d5944-75cf-4f4d-9a53-dd47108ee9d9](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:949d5944-75cf-4f4d-9a53-dd47108ee9d9)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:015226fe-5c1c-4b79-8266-45805920e141](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:015226fe-5c1c-4b79-8266-45805920e141)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:57838490-6e5b-4a2c-a8ad-83eeea140fdc](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:57838490-6e5b-4a2c-a8ad-83eeea140fdc)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:a1bef2e3-f5db-4618-a259-ed2249f21522](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:a1bef2e3-f5db-4618-a259-ed2249f21522)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:8080f913-3084-43d9-a70f-fda46dc4787c](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:8080f913-3084-43d9-a70f-fda46dc4787c)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:41063304-631d-474c-a58f-fa41bcad06c2](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:41063304-631d-474c-a58f-fa41bcad06c2)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:2a99dfc2-8c06-4762-b67f-709be613fa5e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:2a99dfc2-8c06-4762-b67f-709be613fa5e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:3353376c-61ec-4568-98de-8da47852046e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:3353376c-61ec-4568-98de-8da47852046e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:71ac5884-b78a-445f-ae15-ab0b765e8721](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:71ac5884-b78a-445f-ae15-ab0b765e8721)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:306c350a-1672-4b7f-aca7-e9abd9409ec7](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:306c350a-1672-4b7f-aca7-e9abd9409ec7)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:29c9ebe7-eb28-44d5-8128-4c953147e9e9](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:29c9ebe7-eb28-44d5-8128-4c953147e9e9)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:980e632a-e32c-48b5-9570-aed1cda736e6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:980e632a-e32c-48b5-9570-aed1cda736e6)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7f884c5a-95ed-48d9-b180-89a7f21228d4](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7f884c5a-95ed-48d9-b180-89a7f21228d4)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:d685bc98-9eb8-4e5a-a3e7-667a3690989c](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:d685bc98-9eb8-4e5a-a3e7-667a3690989c)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:c80769fd-f949-4a43-8dc4-dd116d7788c5](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:c80769fd-f949-4a43-8dc4-dd116d7788c5)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:53133903-eb0b-4def-a654-8f916131fe65](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:53133903-eb0b-4def-a654-8f916131fe65)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:65fbbad0-99b9-426f-a210-8efaaa563153](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:65fbbad0-99b9-426f-a210-8efaaa563153)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:d08c50c8-395d-4a8a-9ad9-7e1687610862](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:d08c50c8-395d-4a8a-9ad9-7e1687610862)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:027391c9-f3a8-444e-a5d7-bbd8fc683add](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:027391c9-f3a8-444e-a5d7-bbd8fc683add)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f6931d83-b2f6-4b1d-9786-087320b9ee3f](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f6931d83-b2f6-4b1d-9786-087320b9ee3f)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:53043aac-0d78-4bae-9247-fdfb90bdc986](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:53043aac-0d78-4bae-9247-fdfb90bdc986)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:dbbac728-fd39-41db-806e-c8a6e27efca7](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:dbbac728-fd39-41db-806e-c8a6e27efca7)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:ea3a18d6-0d02-4c5e-99cd-2cf2646b9b35](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:ea3a18d6-0d02-4c5e-99cd-2cf2646b9b35)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:17b1f5f1-f20d-4b3e-8a9b-f002484073fe](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:17b1f5f1-f20d-4b3e-8a9b-f002484073fe)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:b252215c-bc3c-4a40-8844-2e2a994ec0c4](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:b252215c-bc3c-4a40-8844-2e2a994ec0c4)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:59bbdc23-2a7c-4693-8ff2-25d932310b2f](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:59bbdc23-2a7c-4693-8ff2-25d932310b2f)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:d113cf60-b3da-4620-ab81-8f916e92db63](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:d113cf60-b3da-4620-ab81-8f916e92db63)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:26feb55e-a603-4d3b-9d57-f9ded92ee4ec](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:26feb55e-a603-4d3b-9d57-f9ded92ee4ec)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:e96d4fc7-a6de-467d-b4b7-23da72cf1eac](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:e96d4fc7-a6de-467d-b4b7-23da72cf1eac)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:3e8b475e-2aa8-46c7-a269-47f0cb4238e0](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:3e8b475e-2aa8-46c7-a269-47f0cb4238e0)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:b62113ab-21fe-4335-a287-9cf1b68f788b](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:b62113ab-21fe-4335-a287-9cf1b68f788b)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:0ae9a38a-b79f-45b3-a47f-40dd9d89bf92](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:0ae9a38a-b79f-45b3-a47f-40dd9d89bf92)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:16d926d7-b0cf-4402-86b3-0a4e6a3eeaaf](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:16d926d7-b0cf-4402-86b3-0a4e6a3eeaaf)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f59593b5-9d77-4fe4-9b53-01eb5646aa49](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f59593b5-9d77-4fe4-9b53-01eb5646aa49)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:82f581ab-f143-43bc-a241-bdf3ce8b7877](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:82f581ab-f143-43bc-a241-bdf3ce8b7877)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:c0ba53b7-ac3f-43d1-9c2d-4b037032bd89](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:c0ba53b7-ac3f-43d1-9c2d-4b037032bd89)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:86210323-9e2f-4cd6-b90e-895fb3412bbe](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:86210323-9e2f-4cd6-b90e-895fb3412bbe)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:96262cea-5b33-4c80-8472-1badb948ed04](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:96262cea-5b33-4c80-8472-1badb948ed04)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:38 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7c14c9ec-a051-4877-a39e-3eab457fdb27](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7c14c9ec-a051-4877-a39e-3eab457fdb27)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:499d95af-f038-41a0-b043-43b91000ae3e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:499d95af-f038-41a0-b043-43b91000ae3e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:dceba86b-50cd-4732-9abf-d8aeb083dcb8](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:dceba86b-50cd-4732-9abf-d8aeb083dcb8)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:d687d701-072d-4e57-b174-3dac7089d373](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:d687d701-072d-4e57-b174-3dac7089d373)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:159e23fb-2adc-461d-8ab7-a2d03b51ebc9](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:159e23fb-2adc-461d-8ab7-a2d03b51ebc9)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:db454275-dd56-4485-870a-b91c15dc3aca](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:db454275-dd56-4485-870a-b91c15dc3aca)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:8f773a11-c696-47b3-b5d5-9966147c3b22](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:8f773a11-c696-47b3-b5d5-9966147c3b22)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:22cb7098-c040-4f33-96f8-19a26bd731a6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:22cb7098-c040-4f33-96f8-19a26bd731a6)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:b0675439-179f-4156-bd2e-6b11127270de](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:b0675439-179f-4156-bd2e-6b11127270de)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:dc2aeee1-fa55-495c-91f1-13ebb71b3f05](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:dc2aeee1-fa55-495c-91f1-13ebb71b3f05)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:e67645fd-225c-4a07-a827-306e371ee215](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:e67645fd-225c-4a07-a827-306e371ee215)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:b83a536d-7de8-4364-b16c-7f223e205563](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:b83a536d-7de8-4364-b16c-7f223e205563)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:db9f17c0-5c6a-4a8f-9b60-8efa6406c6ab](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:db9f17c0-5c6a-4a8f-9b60-8efa6406c6ab)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f5870965-ba2d-463a-8b9e-e87d6ba5a2ae](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f5870965-ba2d-463a-8b9e-e87d6ba5a2ae)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:5f1d1bc9-dc3c-493f-98a0-d47cd03e1e3f](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:5f1d1bc9-dc3c-493f-98a0-d47cd03e1e3f)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:bb7be3ef-dc00-4454-a1db-df3f9fe72b17](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:bb7be3ef-dc00-4454-a1db-df3f9fe72b17)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:04e80ac9-d73b-4cf1-bfb4-cfd8cb61c67d](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:04e80ac9-d73b-4cf1-bfb4-cfd8cb61c67d)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:96248143-a46c-409f-9c24-e8100f13c233](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:96248143-a46c-409f-9c24-e8100f13c233)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:37f26d3c-6d2e-4813-b578-ec4481aa5ef4](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:37f26d3c-6d2e-4813-b578-ec4481aa5ef4)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:e9f8a91b-6fcf-46b2-b7bb-1c66fbf15f91](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:e9f8a91b-6fcf-46b2-b7bb-1c66fbf15f91)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:63f0263d-2dfc-4dff-8e10-4ae7cf6a2531](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:63f0263d-2dfc-4dff-8e10-4ae7cf6a2531)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f48d1bfa-6737-422e-854c-83534780a8ac](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f48d1bfa-6737-422e-854c-83534780a8ac)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:fdf02201-0b42-4a28-b9ca-24b21923ff86](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:fdf02201-0b42-4a28-b9ca-24b21923ff86)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:5ed78b4b-1bf2-4b17-bfe7-42fccf9f1b19](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:5ed78b4b-1bf2-4b17-bfe7-42fccf9f1b19)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f7f9cc81-7fc9-4267-b075-0e175689e368](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f7f9cc81-7fc9-4267-b075-0e175689e368)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:537eb49b-2385-4d55-aafb-e7edb548b222](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:537eb49b-2385-4d55-aafb-e7edb548b222)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f6f78c07-fca8-4b01-8738-06f3b8166d79](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f6f78c07-fca8-4b01-8738-06f3b8166d79)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:e4537c65-46e3-45a7-b50e-386ae577f856](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:e4537c65-46e3-45a7-b50e-386ae577f856)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:8966239a-721c-4cb4-bb26-79c2316a4a57](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:8966239a-721c-4cb4-bb26-79c2316a4a57)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7caace0b-682a-4036-942c-02181f3e0bf9](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7caace0b-682a-4036-942c-02181f3e0bf9)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:c52bf4c1-dac9-4e24-b28f-6d8f737ac744](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:c52bf4c1-dac9-4e24-b28f-6d8f737ac744)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:5e5768dd-9101-491e-a73e-cadf2dfcd200](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:5e5768dd-9101-491e-a73e-cadf2dfcd200)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:aa0d6f90-7120-4283-8736-2eecf3db2231](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:aa0d6f90-7120-4283-8736-2eecf3db2231)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:ab1139b7-28fa-4b4e-8084-fce7e521ef71](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:ab1139b7-28fa-4b4e-8084-fce7e521ef71)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:21556d87-daaf-4011-a441-ded18f863f16](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:21556d87-daaf-4011-a441-ded18f863f16)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:d487c076-dc91-4792-9abc-4befdc363346](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:d487c076-dc91-4792-9abc-4befdc363346)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:3686b78e-de5c-40e9-867d-ea1796d402d2](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:3686b78e-de5c-40e9-867d-ea1796d402d2)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7dbf6dd2-dfd6-4a30-b47b-b5b27ce0f497](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7dbf6dd2-dfd6-4a30-b47b-b5b27ce0f497)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:bfac3c47-8d2f-4cc2-b4e1-e4198f393264](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:bfac3c47-8d2f-4cc2-b4e1-e4198f393264)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f0d31d08-64e6-4663-acc2-aa25bb647dc5](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f0d31d08-64e6-4663-acc2-aa25bb647dc5)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:6a86e855-a513-4b0e-992b-3a235caf76ef](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:6a86e855-a513-4b0e-992b-3a235caf76ef)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:ad2be5da-1d48-4bce-b0bd-9a6d8c4888a2](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:ad2be5da-1d48-4bce-b0bd-9a6d8c4888a2)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:4c9dc507-5499-4ba7-bef1-27198dfe08de](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:4c9dc507-5499-4ba7-bef1-27198dfe08de)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:dcddfa81-351b-4882-9667-bc57c1e2546e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:dcddfa81-351b-4882-9667-bc57c1e2546e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f9809454-1987-4e1a-846f-0d8f86b5614c](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f9809454-1987-4e1a-846f-0d8f86b5614c)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:dd8ffd34-82fc-414d-8211-dbaeb187b018](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:dd8ffd34-82fc-414d-8211-dbaeb187b018)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:63dca400-a4ae-4062-b4bd-20ef74802f09](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:63dca400-a4ae-4062-b4bd-20ef74802f09)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:b458c9e0-ea03-48bd-9392-cf25f1fe541f](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:b458c9e0-ea03-48bd-9392-cf25f1fe541f)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:889c7996-1a80-4e53-8ab8-2b6c9ee7d39b](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:889c7996-1a80-4e53-8ab8-2b6c9ee7d39b)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:3b5d3474-6f5f-49d9-b9e0-05fc9899a8d1](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:3b5d3474-6f5f-49d9-b9e0-05fc9899a8d1)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:014c22b0-a814-4254-bb2b-e728c39c3791](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:014c22b0-a814-4254-bb2b-e728c39c3791)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:c63a9b8c-2fcc-4502-a05f-0f2e43236551](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:c63a9b8c-2fcc-4502-a05f-0f2e43236551)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:ccda15db-575e-47a2-a36e-d6e03de2dddb](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:ccda15db-575e-47a2-a36e-d6e03de2dddb)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:abe0beee-6abf-4e0c-a667-9f969afabe40](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:abe0beee-6abf-4e0c-a667-9f969afabe40)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7142435b-24c2-4afd-84c2-5a05583e2db9](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7142435b-24c2-4afd-84c2-5a05583e2db9)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:99b194b6-ed5f-481e-87b2-145ef0401fa6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:99b194b6-ed5f-481e-87b2-145ef0401fa6)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7be979b5-dc6a-4fd3-85ce-a28028be7ffe](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7be979b5-dc6a-4fd3-85ce-a28028be7ffe)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:b55d8310-f8ec-407e-9e73-818eb484702c](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:b55d8310-f8ec-407e-9e73-818eb484702c)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:c556e541-b01b-400e-bb7b-30b02719fb67](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:c556e541-b01b-400e-bb7b-30b02719fb67)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:e6d52f88-d734-4565-8fbb-d950efb27c1d](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:e6d52f88-d734-4565-8fbb-d950efb27c1d)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:859e65ae-ffcd-4e00-9805-c90a844ef9c3](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:859e65ae-ffcd-4e00-9805-c90a844ef9c3)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:295bee94-f652-4b4c-a1da-709bc9eca3cc](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:295bee94-f652-4b4c-a1da-709bc9eca3cc)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7ea8921e-0294-48ba-8039-b9287c221715](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7ea8921e-0294-48ba-8039-b9287c221715)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:d83d71c0-401a-4cff-a451-d3e50b51946e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:d83d71c0-401a-4cff-a451-d3e50b51946e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:179dbb74-95d8-4627-85e0-7de1711d70e5](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:179dbb74-95d8-4627-85e0-7de1711d70e5)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:5fa68bb0-d92b-45d9-9bc3-37fbc8830168](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:5fa68bb0-d92b-45d9-9bc3-37fbc8830168)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:019c8ca4-9548-417c-8f4b-826294c2c1ec](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:019c8ca4-9548-417c-8f4b-826294c2c1ec)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:af3c1385-a3cc-4a4e-8d9f-57a428098b1e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:af3c1385-a3cc-4a4e-8d9f-57a428098b1e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f67777d0-16a4-4a09-bba4-ca42567cf63b](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f67777d0-16a4-4a09-bba4-ca42567cf63b)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:e48e5f2e-fde2-4a62-ae10-9de78304c0f9](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:e48e5f2e-fde2-4a62-ae10-9de78304c0f9)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:8aba2e58-ea0d-438b-b51f-47284d0143ff](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:8aba2e58-ea0d-438b-b51f-47284d0143ff)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:af8c35b2-e5cb-42b1-bd39-5aa64c05f38e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:af8c35b2-e5cb-42b1-bd39-5aa64c05f38e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:eefc5a64-b0b6-4e20-9ddd-8c7a78768c94](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:eefc5a64-b0b6-4e20-9ddd-8c7a78768c94)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:0361426a-bad6-4112-90b2-0346b8e74444](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:0361426a-bad6-4112-90b2-0346b8e74444)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:26f5b03a-5375-4280-a705-3136333a981e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:26f5b03a-5375-4280-a705-3136333a981e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:613c10c2-c1b2-44b0-a19a-6094a4ae3fdc](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:613c10c2-c1b2-44b0-a19a-6094a4ae3fdc)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:c09b846d-7f41-4d69-9d7a-38b5cfd3dad4](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:c09b846d-7f41-4d69-9d7a-38b5cfd3dad4)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:4e3066f5-61e3-4013-b004-24a61846132e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:4e3066f5-61e3-4013-b004-24a61846132e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:4bea05d0-6bc0-471b-b2ac-90716aa92784](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:4bea05d0-6bc0-471b-b2ac-90716aa92784)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:084add03-bf03-4ec4-964e-92909a8725f7](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:084add03-bf03-4ec4-964e-92909a8725f7)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:a20f77ea-cd6b-47f4-911a-0dd885a64de7](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:a20f77ea-cd6b-47f4-911a-0dd885a64de7)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:d56c6cee-a9b4-4d1f-a21b-a3ff3e8032e3](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:d56c6cee-a9b4-4d1f-a21b-a3ff3e8032e3)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f18a4dd6-c906-41ac-8291-156647120c6e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f18a4dd6-c906-41ac-8291-156647120c6e)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:4e957082-d6f0-4d1a-a20a-a1e4045fd438](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:4e957082-d6f0-4d1a-a20a-a1e4045fd438)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:bdae6ef3-9731-4d8e-a33a-e62cbe2856f6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:bdae6ef3-9731-4d8e-a33a-e62cbe2856f6)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:5bd79289-6e3d-4cfa-83db-20b87e48bc83](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:5bd79289-6e3d-4cfa-83db-20b87e48bc83)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:02453925-bc84-47f9-8705-6deeb174098a](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:02453925-bc84-47f9-8705-6deeb174098a)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:b7a61903-7562-4ada-8b7a-ae30e3e4fcb0](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:b7a61903-7562-4ada-8b7a-ae30e3e4fcb0)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:583f7295-9fa7-4989-bd44-d7e06d61e468](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:583f7295-9fa7-4989-bd44-d7e06d61e468)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:ffc8bcc8-4bb6-44d0-9e68-768bc8382241](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:ffc8bcc8-4bb6-44d0-9e68-768bc8382241)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:8a450917-51fa-4b90-b553-e522c13061d5](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:8a450917-51fa-4b90-b553-e522c13061d5)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:936021f0-0fc2-4f3f-a238-82a32639d073](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:936021f0-0fc2-4f3f-a238-82a32639d073)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:5ae6fadc-2283-41c7-8f85-43086da544d6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:5ae6fadc-2283-41c7-8f85-43086da544d6)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:f5b6bbf8-36c7-4849-ac4a-5a5a98526df2](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:f5b6bbf8-36c7-4849-ac4a-5a5a98526df2)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:e219f78e-55f7-43c4-8a8c-73d3335d766c](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:e219f78e-55f7-43c4-8a8c-73d3335d766c)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:5f645bcb-bd57-4e22-ad80-9d49379fa931](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:5f645bcb-bd57-4e22-ad80-9d49379fa931)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:7e6a02bc-c9a2-44d4-a4c3-508e39c985fa](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:7e6a02bc-c9a2-44d4-a4c3-508e39c985fa)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:2a64536e-7727-4ecc-b746-895e78ffc751](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:2a64536e-7727-4ecc-b746-895e78ffc751)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:c9040af0-a1c4-4a80-a804-13476dd8ba9d](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:c9040af0-a1c4-4a80-a804-13476dd8ba9d)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:applied-customer-billing-rate:57e1605d-92b8-4ed9-a35e-4fe46452a577](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/appliedCustomerBillingRate/urn:ngsi-ld:applied-customer-billing-rate:57e1605d-92b8-4ed9-a35e-4fe46452a577)

- **Type:** appliedCustomerBillingRate
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:44 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to appliedCustomerBillingRate (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### billingAccount Objects

#### Object: [urn:ngsi-ld:billing-account:3b49919b-ab08-4969-ab53-cfd06cc21206](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:3b49919b-ab08-4969-ab53-cfd06cc21206)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:d2c224df-b007-4524-9029-7e7e1b021d35](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:d2c224df-b007-4524-9029-7e7e1b021d35)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:c84d03ff-fc74-435c-a54c-fed6e95ff80a](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:c84d03ff-fc74-435c-a54c-fed6e95ff80a)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:f98a4654-612b-474a-875b-107243e814bb](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:f98a4654-612b-474a-875b-107243e814bb)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:5a7a0a3f-61f8-4b62-bdf9-5212cbfc129c](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:5a7a0a3f-61f8-4b62-bdf9-5212cbfc129c)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:f727fb85-51f5-4dca-822f-4f4bb2775549](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:f727fb85-51f5-4dca-822f-4f4bb2775549)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:4da08929-a8a0-4362-aed8-a4d0d25032f2](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:4da08929-a8a0-4362-aed8-a4d0d25032f2)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:b62afbb3-0991-4c3d-85be-d96f95c55435](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:b62afbb3-0991-4c3d-85be-d96f95c55435)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:d8f73230-fe44-4594-9cc0-6c2b76107187](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:d8f73230-fe44-4594-9cc0-6c2b76107187)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:1011429f-061e-481c-9a1d-49226061b1c3](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:1011429f-061e-481c-9a1d-49226061b1c3)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:1ff83842-9917-4ac7-8f43-8e4e53a147ee](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:1ff83842-9917-4ac7-8f43-8e4e53a147ee)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:c2b41658-aabb-41da-ba36-d618ab076327](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:c2b41658-aabb-41da-ba36-d618ab076327)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:804ca8ab-75ec-469a-8bc9-8722c78a67db](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:804ca8ab-75ec-469a-8bc9-8722c78a67db)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:beb15d55-3a13-423f-bcb6-85066c45b984](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:beb15d55-3a13-423f-bcb6-85066c45b984)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:0ffd0fc2-4524-4f2c-881a-b5f4b936f33f](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:0ffd0fc2-4524-4f2c-881a-b5f4b936f33f)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:449b4aac-a10c-475a-8f9e-320bf2a0a4b7](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:449b4aac-a10c-475a-8f9e-320bf2a0a4b7)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:84257bf5-e3b4-4305-926a-fc55e6f992ef](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:84257bf5-e3b4-4305-926a-fc55e6f992ef)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:billing-account:65f511aa-d7ec-4c34-930d-cc3cb5033db3](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/billingAccount/urn:ngsi-ld:billing-account:65f511aa-d7ec-4c34-930d-cc3cb5033db3)

- **Type:** billingAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to billingAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### category Objects

#### Object: [urn:ngsi-ld:category:73dd1ca0-defd-4642-bbec-f44d52273973](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:73dd1ca0-defd-4642-bbec-f44d52273973)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:57158a09-c62b-4160-a49e-2295ca068682](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:57158a09-c62b-4160-a49e-2295ca068682)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:3cad4d15-bbe6-44d6-a82a-a6478b8e53ce](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:3cad4d15-bbe6-44d6-a82a-a6478b8e53ce)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:35182b9c-be04-4a40-ae67-f9433f4d36e1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:35182b9c-be04-4a40-ae67-f9433f4d36e1)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:b332fe31-ec4d-4883-b051-e663a3d40830](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:b332fe31-ec4d-4883-b051-e663a3d40830)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:3ae62a2d-a194-4250-9b3f-8c9349ef4799](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:3ae62a2d-a194-4250-9b3f-8c9349ef4799)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:bb19f802-c0dd-4686-9049-cbd4665e7a04](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:bb19f802-c0dd-4686-9049-cbd4665e7a04)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:44370eaa-8828-4e1d-b9be-03b64eb11309](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:44370eaa-8828-4e1d-b9be-03b64eb11309)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:840bf629-6e64-4e49-94c0-740d7b312dd4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:840bf629-6e64-4e49-94c0-740d7b312dd4)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:7c796f0f-8e89-4578-bd6f-5d6c56ec912d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:7c796f0f-8e89-4578-bd6f-5d6c56ec912d)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:44e33c19-dd19-4ee9-a816-9dea2d34f02c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:44e33c19-dd19-4ee9-a816-9dea2d34f02c)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:d154f150-2980-4b5d-9aef-2fdc123dc4d9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:d154f150-2980-4b5d-9aef-2fdc123dc4d9)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:2b015a9f-50e6-453f-a251-e8770e2260bb](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:2b015a9f-50e6-453f-a251-e8770e2260bb)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:9bfdb312-ad44-41c5-9c5a-4d58ad861f63](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:9bfdb312-ad44-41c5-9c5a-4d58ad861f63)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:7aa7ae47-4c3d-447e-848b-60b3f015cb49](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:7aa7ae47-4c3d-447e-848b-60b3f015cb49)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:b51bdeb5-0cf0-41a3-b0af-3ef48a88c988](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:b51bdeb5-0cf0-41a3-b0af-3ef48a88c988)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:15f52622-9097-4fba-a66b-435fb651a393](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:15f52622-9097-4fba-a66b-435fb651a393)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:bd99e5e4-5143-470e-9c05-d7839dfc71bc](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:bd99e5e4-5143-470e-9c05-d7839dfc71bc)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:ed12cd4a-3a23-46fe-8135-ea5bdfbb2b4b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:ed12cd4a-3a23-46fe-8135-ea5bdfbb2b4b)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:17c3aafe-2c2d-49be-8dce-dd4981e22e28](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:17c3aafe-2c2d-49be-8dce-dd4981e22e28)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:08892d05-2e7a-41f9-8e8b-2dcc28f86b8a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:08892d05-2e7a-41f9-8e8b-2dcc28f86b8a)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:abe28b41-cc3a-4624-9c23-2ed3e021dbb5](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:abe28b41-cc3a-4624-9c23-2ed3e021dbb5)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:96778468-41b5-4245-842e-f3c481a240b0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:96778468-41b5-4245-842e-f3c481a240b0)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:8337bace-8228-4925-a75a-e2654f0bac41](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:8337bace-8228-4925-a75a-e2654f0bac41)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:94bd8c25-4183-4124-a6ed-0516d4ced4a6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:94bd8c25-4183-4124-a6ed-0516d4ced4a6)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:c053c314-6696-49bd-a10b-052e6f3dbddb](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:c053c314-6696-49bd-a10b-052e6f3dbddb)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:630359eb-7d66-4eb2-bf07-2590841049a0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:630359eb-7d66-4eb2-bf07-2590841049a0)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:af87fc59-aafb-4301-8ba9-3594558a9eff](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:af87fc59-aafb-4301-8ba9-3594558a9eff)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:9c02c10e-1cdf-4de3-a99e-f0b689881d2b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:9c02c10e-1cdf-4de3-a99e-f0b689881d2b)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:47eeb384-4400-49c1-b0e5-718ef17860ba](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:47eeb384-4400-49c1-b0e5-718ef17860ba)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:8795e633-8a64-438f-8cad-a2d5175cc9cb](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:8795e633-8a64-438f-8cad-a2d5175cc9cb)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:6ff41b67-bf97-4772-86ef-52d1d4998a3e](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:6ff41b67-bf97-4772-86ef-52d1d4998a3e)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:228fb947-48df-4281-b95d-c675bdc31b7a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:228fb947-48df-4281-b95d-c675bdc31b7a)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:9a7f4ac4-e481-4303-98fc-b4f9911f6529](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:9a7f4ac4-e481-4303-98fc-b4f9911f6529)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:419a8fac-d55a-4ae7-867f-2a3a338844cb](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:419a8fac-d55a-4ae7-867f-2a3a338844cb)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:03e76d62-a8c6-4571-ad7a-c31e754d3d3f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:03e76d62-a8c6-4571-ad7a-c31e754d3d3f)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:0b5cb3a5-b08e-4fca-8fb4-f99afaf71a2a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:0b5cb3a5-b08e-4fca-8fb4-f99afaf71a2a)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:061ba18d-4263-42f3-9d6e-17d90ad25832](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:061ba18d-4263-42f3-9d6e-17d90ad25832)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:55ff6485-3bcf-4009-815a-fca65727c64d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:55ff6485-3bcf-4009-815a-fca65727c64d)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:b1f8c6b7-e73e-415a-9f28-51c01adc36c1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:b1f8c6b7-e73e-415a-9f28-51c01adc36c1)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:cfb68599-fde0-457e-bd8d-f6f6db20025f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:cfb68599-fde0-457e-bd8d-f6f6db20025f)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:13837a4a-4eee-4879-be8b-da8bc88f8086](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:13837a4a-4eee-4879-be8b-da8bc88f8086)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:ef80f5f1-c480-48f8-b96b-b893efec3e4d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:ef80f5f1-c480-48f8-b96b-b893efec3e4d)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:b4998d10-d9c2-46ad-a08d-63df7cd8e911](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:b4998d10-d9c2-46ad-a08d-63df7cd8e911)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:10ba35dd-4906-4434-adac-9bb9268e1127](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:10ba35dd-4906-4434-adac-9bb9268e1127)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:3beea627-9691-4ed8-9bbf-7c6fe06e278a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:3beea627-9691-4ed8-9bbf-7c6fe06e278a)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:3ebbe833-9f85-42d2-b76d-7429d156eba6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:3ebbe833-9f85-42d2-b76d-7429d156eba6)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:818597c8-6de7-4961-8ce3-61fb30d7fbb8](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:818597c8-6de7-4961-8ce3-61fb30d7fbb8)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:2cc758fa-80b3-4704-9c38-26918c25b535](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:2cc758fa-80b3-4704-9c38-26918c25b535)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:a456f7a7-cbb0-4b71-9c25-f8cb46555016](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:a456f7a7-cbb0-4b71-9c25-f8cb46555016)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:6df17fbc-465d-4e0e-93af-ecc0ccdf34b1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:6df17fbc-465d-4e0e-93af-ecc0ccdf34b1)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:9c12beda-8e3b-4b90-ba96-191e0129a9d4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:9c12beda-8e3b-4b90-ba96-191e0129a9d4)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:c9f5f9b8-2991-4cb5-aad9-eede449c88e8](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:c9f5f9b8-2991-4cb5-aad9-eede449c88e8)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:f0c23dff-8f09-474a-8306-607ca835d8ce](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:f0c23dff-8f09-474a-8306-607ca835d8ce)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:465a29be-b24c-448e-80ed-c9a1e5aeb3da](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:465a29be-b24c-448e-80ed-c9a1e5aeb3da)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:ac6eefc6-1e58-432f-a9b9-c8349c3a3d68](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:ac6eefc6-1e58-432f-a9b9-c8349c3a3d68)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:4c9b41bb-2eeb-4229-8442-b0e8d8127271](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:4c9b41bb-2eeb-4229-8442-b0e8d8127271)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:917fa857-f354-49f1-84f3-38540e07e434](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:917fa857-f354-49f1-84f3-38540e07e434)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:1d731f47-e2ce-4f2a-899b-f7f1c449cd98](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:1d731f47-e2ce-4f2a-899b-f7f1c449cd98)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:63ed0da1-bc76-4e8d-af4d-f551d8148394](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:63ed0da1-bc76-4e8d-af4d-f551d8148394)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:8ec9aa71-afa0-4ae4-93d2-61eef79fe9c6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:8ec9aa71-afa0-4ae4-93d2-61eef79fe9c6)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:fcf925b0-bb66-4860-8c2a-db17861fe105](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:fcf925b0-bb66-4860-8c2a-db17861fe105)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:b664a377-e12c-465b-ae2c-0c5a53438e65](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:b664a377-e12c-465b-ae2c-0c5a53438e65)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:2fffafeb-64ca-4d72-9e4c-ed7d2973b3a9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:2fffafeb-64ca-4d72-9e4c-ed7d2973b3a9)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:a6f7ec89-e2e3-429d-a16c-30b0a1ab0ff6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:a6f7ec89-e2e3-429d-a16c-30b0a1ab0ff6)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:4b11ef5c-50a6-4a20-8817-8152b372cc95](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:4b11ef5c-50a6-4a20-8817-8152b372cc95)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:69261f7b-f228-4aa5-a180-02f2e4c192bf](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:69261f7b-f228-4aa5-a180-02f2e4c192bf)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:9508e28c-dca7-4cdb-b49a-8ad9b473a106](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:9508e28c-dca7-4cdb-b49a-8ad9b473a106)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:2fe2b111-636e-4ccc-96fc-4a2bde912e31](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:2fe2b111-636e-4ccc-96fc-4a2bde912e31)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:e0c4ad97-585d-44c7-99b7-f55e31be1ce3](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:e0c4ad97-585d-44c7-99b7-f55e31be1ce3)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:c8286912-7ad4-431c-a112-f3c0298c1806](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:c8286912-7ad4-431c-a112-f3c0298c1806)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:e464a506-ef2c-468c-9033-ec5572d5076e](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:e464a506-ef2c-468c-9033-ec5572d5076e)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:91764e83-85e2-48c8-9311-b19ee59219cc](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:91764e83-85e2-48c8-9311-b19ee59219cc)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:0b4a0d9e-0a4e-4489-9da0-6ffd18e1cbc4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:0b4a0d9e-0a4e-4489-9da0-6ffd18e1cbc4)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:0ed1e073-6168-4bcf-b249-221c8f386507](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:0ed1e073-6168-4bcf-b249-221c8f386507)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:0d52ebea-3b4c-45c0-9dc7-c1379135950d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:0d52ebea-3b4c-45c0-9dc7-c1379135950d)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:821c1437-f982-446e-866c-c43a680bf0f0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:821c1437-f982-446e-866c-c43a680bf0f0)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:0b74e44c-c05b-4bbe-8530-a73a4d9cf928](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:0b74e44c-c05b-4bbe-8530-a73a4d9cf928)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:b334a7a2-3e7d-473e-a042-09ba2ff6cff6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:b334a7a2-3e7d-473e-a042-09ba2ff6cff6)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:31ca6777-cc13-4d74-bbc7-b8bc10e6fcd7](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:31ca6777-cc13-4d74-bbc7-b8bc10e6fcd7)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:8cdb4483-2185-4dc6-afd0-a70d30010849](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:8cdb4483-2185-4dc6-afd0-a70d30010849)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:39a55d2f-6014-4cab-8f40-cc564e2e253b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:39a55d2f-6014-4cab-8f40-cc564e2e253b)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:607af425-d44e-4274-be73-9493297ec4a5](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:607af425-d44e-4274-be73-9493297ec4a5)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:4cb199d8-4bbb-4ea7-b811-03a54e6fcbc9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:4cb199d8-4bbb-4ea7-b811-03a54e6fcbc9)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:424eca22-053f-458e-8bd2-51318b733f7e](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:424eca22-053f-458e-8bd2-51318b733f7e)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:0186f2e7-869f-4118-83c5-7de931733af0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:0186f2e7-869f-4118-83c5-7de931733af0)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:b523a55b-29fe-431c-809b-4339ae34d944](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:b523a55b-29fe-431c-809b-4339ae34d944)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:f5e856f7-a619-4fd4-b9d2-99fe8a778db9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:f5e856f7-a619-4fd4-b9d2-99fe8a778db9)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:8d222bda-159e-4957-8b76-0fb06b4449dd](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:8d222bda-159e-4957-8b76-0fb06b4449dd)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:91abfd48-4870-4af1-b64f-69cb144d1dc6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:91abfd48-4870-4af1-b64f-69cb144d1dc6)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:a14a4067-a5c9-4122-b2a7-28ee2dd85036](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:a14a4067-a5c9-4122-b2a7-28ee2dd85036)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:814efafb-b2be-4d7e-b83d-0d447d9f68ac](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:814efafb-b2be-4d7e-b83d-0d447d9f68ac)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:d6aa17c8-a0d4-4312-9ab1-ae78a0aace1d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:d6aa17c8-a0d4-4312-9ab1-ae78a0aace1d)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:dc159e2d-d0a1-49e2-a2ec-b7c4c97e4dd7](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:dc159e2d-d0a1-49e2-a2ec-b7c4c97e4dd7)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:55b2cb9f-e13b-499e-bf76-fd1eb56d2bde](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:55b2cb9f-e13b-499e-bf76-fd1eb56d2bde)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:405c922f-0de1-4e7f-b478-713240b9b381](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:405c922f-0de1-4e7f-b478-713240b9b381)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:466cc605-e806-43e1-9291-84deac0028f1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:466cc605-e806-43e1-9291-84deac0028f1)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:b96911a6-e09e-4776-b4fc-4faf7004a162](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:b96911a6-e09e-4776-b4fc-4faf7004a162)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:ffeae64f-edc2-4754-906e-a4d35d10c806](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:ffeae64f-edc2-4754-906e-a4d35d10c806)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:b0cd7c24-e3c1-49a7-8fc4-8e8d492d513b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:b0cd7c24-e3c1-49a7-8fc4-8e8d492d513b)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:645f0c9a-816c-4cf8-a307-2503c4c75742](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:645f0c9a-816c-4cf8-a307-2503c4c75742)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:d64a7aff-f49c-4cbf-84d8-4b883e59e392](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:d64a7aff-f49c-4cbf-84d8-4b883e59e392)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:cf5a08f4-a4da-4e0d-bd87-643894ae957c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:cf5a08f4-a4da-4e0d-bd87-643894ae957c)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:1d359cb4-dc15-4c87-afd2-da18a2940b5b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:1d359cb4-dc15-4c87-afd2-da18a2940b5b)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:515f7838-331f-4164-bb9f-8d843e04a101](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:515f7838-331f-4164-bb9f-8d843e04a101)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:9b57eaca-bc73-4283-8226-8c8666498cfa](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:9b57eaca-bc73-4283-8226-8c8666498cfa)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:3867db98-1eb3-4bff-8a23-715082f404ff](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:3867db98-1eb3-4bff-8a23-715082f404ff)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:920f950b-9ee3-4cf1-8f2d-caf5f8488d2e](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:920f950b-9ee3-4cf1-8f2d-caf5f8488d2e)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:0c4373c1-9a3b-4797-9880-24d170a350ee](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:0c4373c1-9a3b-4797-9880-24d170a350ee)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:5b55bcbc-4776-4702-b400-bf32a1821fb4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:5b55bcbc-4776-4702-b400-bf32a1821fb4)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:a7779dea-c0c0-47af-b078-3098c309cc23](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:a7779dea-c0c0-47af-b078-3098c309cc23)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:ef149b50-08ea-4ee2-bf41-a90b04a1ce79](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:ef149b50-08ea-4ee2-bf41-a90b04a1ce79)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:category:961389ac-7e86-4e80-864a-0f130cc9863b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/category/urn:ngsi-ld:category:961389ac-7e86-4e80-864a-0f130cc9863b)

- **Type:** category
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to category (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

### customerBill Objects

#### Object: [urn:ngsi-ld:customer-bill:87fe1707-c5b3-4a74-9d67-3113c2b07045](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:87fe1707-c5b3-4a74-9d67-3113c2b07045)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:5efe1990-db82-4eef-99e3-d3d4671ca625](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:5efe1990-db82-4eef-99e3-d3d4671ca625)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:beb50ce0-3ab9-403f-84e6-ee03c44be13b](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:beb50ce0-3ab9-403f-84e6-ee03c44be13b)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:f59a5928-230f-4cd1-a354-c993c565a4a6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:f59a5928-230f-4cd1-a354-c993c565a4a6)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:5f53afa7-a1c6-458a-8dd7-45da0b8ef3e7](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:5f53afa7-a1c6-458a-8dd7-45da0b8ef3e7)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:b7b8bf50-300d-494b-a406-0f2a3778fcbc](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:b7b8bf50-300d-494b-a406-0f2a3778fcbc)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:80397d05-2196-4e39-9265-4610e37fde50](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:80397d05-2196-4e39-9265-4610e37fde50)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:61c3057a-e565-4bb4-940a-61dd30fd6de3](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:61c3057a-e565-4bb4-940a-61dd30fd6de3)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:885f82ce-116d-4271-95ac-5b1150f210a4](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:885f82ce-116d-4271-95ac-5b1150f210a4)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:e642addf-48e2-4627-8489-a1bad7d09e10](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:e642addf-48e2-4627-8489-a1bad7d09e10)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:7753b831-d482-44b1-a3de-9790c7df2f40](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:7753b831-d482-44b1-a3de-9790c7df2f40)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:f25072b8-572e-4d53-898d-3fef1c7bd3d6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:f25072b8-572e-4d53-898d-3fef1c7bd3d6)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:b542fc2a-975e-446e-b18a-2a6d37957f0b](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:b542fc2a-975e-446e-b18a-2a6d37957f0b)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:e1b3be4f-dcc6-4133-b2b3-47154665444a](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:e1b3be4f-dcc6-4133-b2b3-47154665444a)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:82bc0490-7868-4f71-ae26-94dbb314eb17](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:82bc0490-7868-4f71-ae26-94dbb314eb17)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:d45f9686-e3b6-433d-980f-3261aaafaa74](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:d45f9686-e3b6-433d-980f-3261aaafaa74)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:f7555d3f-c980-4e60-baa5-bacaeaf318df](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:f7555d3f-c980-4e60-baa5-bacaeaf318df)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:77c737cf-3e7e-4efd-bc15-d4e55d4de86e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:77c737cf-3e7e-4efd-bc15-d4e55d4de86e)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:b5bf019c-b42e-47e5-9fa5-e3cb042c1612](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:b5bf019c-b42e-47e5-9fa5-e3cb042c1612)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:c84035b8-0282-4893-bf76-41d026e9d795](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:c84035b8-0282-4893-bf76-41d026e9d795)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:28cf30a1-92af-4b50-99c2-83ef2e6ab12c](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:28cf30a1-92af-4b50-99c2-83ef2e6ab12c)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:9143c42b-8429-45e6-812e-ba8a29b840b9](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:9143c42b-8429-45e6-812e-ba8a29b840b9)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:f07eebc8-435b-4abe-ad98-a17117031588](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:f07eebc8-435b-4abe-ad98-a17117031588)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:9d17558b-d31a-40cd-9358-f7d671577beb](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:9d17558b-d31a-40cd-9358-f7d671577beb)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:4defc8f0-46a5-4fdc-8e27-b608b80578aa](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:4defc8f0-46a5-4fdc-8e27-b608b80578aa)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:0b94eac0-1103-4fa3-8e2b-e75bb78e45bc](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:0b94eac0-1103-4fa3-8e2b-e75bb78e45bc)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:77a43a73-397d-4aea-90f2-1d1bd5e37a2a](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:77a43a73-397d-4aea-90f2-1d1bd5e37a2a)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:0c2aa78f-4c1b-44e0-b31a-b753066bba65](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:0c2aa78f-4c1b-44e0-b31a-b753066bba65)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:48c5e7eb-006d-48c4-b7db-d43602e42c65](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:48c5e7eb-006d-48c4-b7db-d43602e42c65)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:385c62cf-2d3b-403b-9d27-9e2297f99b0e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:385c62cf-2d3b-403b-9d27-9e2297f99b0e)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:4f0d1fdd-78fc-4256-8edf-4569dc2bb68c](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:4f0d1fdd-78fc-4256-8edf-4569dc2bb68c)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:4d1ed9c5-1287-496a-a7c0-6262a0c96940](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:4d1ed9c5-1287-496a-a7c0-6262a0c96940)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:b9119a39-c32e-40fc-a574-2805d1b14789](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:b9119a39-c32e-40fc-a574-2805d1b14789)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:2099f627-3bdd-4d5e-8e18-c5dcdc799555](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:2099f627-3bdd-4d5e-8e18-c5dcdc799555)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:25329f76-abae-441d-84b3-8a8f800fed09](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:25329f76-abae-441d-84b3-8a8f800fed09)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:58dc4ab8-62bf-4a20-837c-d28fdaf714e9](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:58dc4ab8-62bf-4a20-837c-d28fdaf714e9)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:9fca8c85-c7cb-44be-ab3d-1912a32fae6e](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:9fca8c85-c7cb-44be-ab3d-1912a32fae6e)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:db0368e8-9e77-4691-8618-d6514dd0a6d6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:db0368e8-9e77-4691-8618-d6514dd0a6d6)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:ec2bd9a5-94f5-4eaf-9e77-34b6fc43de39](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:ec2bd9a5-94f5-4eaf-9e77-34b6fc43de39)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:db07e589-adf2-409a-a196-705b011f69d0](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:db07e589-adf2-409a-a196-705b011f69d0)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:cc3e86c0-61aa-4655-91bb-0e881e6c7df6](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:cc3e86c0-61aa-4655-91bb-0e881e6c7df6)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:b4d82222-9ffd-4113-929b-b4f9d28a61d0](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:b4d82222-9ffd-4113-929b-b4f9d28a61d0)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:094bf8be-f9de-4724-86cf-5df68f59112c](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:094bf8be-f9de-4724-86cf-5df68f59112c)

- **Type:** customerBill
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:2f1f879c-e80a-48eb-9be3-4f5acc050a91](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:2f1f879c-e80a-48eb-9be3-4f5acc050a91)

- **Type:** customerBill
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:1b90c6af-025f-4c14-aae9-d4dce786c858](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:1b90c6af-025f-4c14-aae9-d4dce786c858)

- **Type:** customerBill
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:7bd441df-3026-487e-b546-8dcb843f7c6f](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:7bd441df-3026-487e-b546-8dcb843f7c6f)

- **Type:** customerBill
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:customer-bill:23184751-c533-4c0e-ab1d-de956d46a25b](https://tmf.dome-marketplace-sbx.org/tmf-api/customerBillManagement/v4/customerBill/urn:ngsi-ld:customer-bill:23184751-c533-4c0e-ab1d-de956d46a25b)

- **Type:** customerBill
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:54 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to customerBill (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

### financialAccount Objects

#### Object: [urn:ngsi-ld:financialAccount:2a20a758-352f-44ea-b913-e16a313ae3fd](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/financialAccount/urn:ngsi-ld:financialAccount:2a20a758-352f-44ea-b913-e16a313ae3fd)

- **Type:** financialAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:46 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to financialAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### individual Objects

#### Object: [urn:ngsi-ld:individual:97790bad-066f-41fa-bb5a-745d783e044e](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:97790bad-066f-41fa-bb5a-745d783e044e)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:038e6cf4-8805-4905-a151-42012ddcdfbf](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:038e6cf4-8805-4905-a151-42012ddcdfbf)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:c1046c38-844f-471f-873c-78b35c270c27](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:c1046c38-844f-471f-873c-78b35c270c27)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:afa0bf6f-0b1e-4d9c-8529-e57bd28740f8](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:afa0bf6f-0b1e-4d9c-8529-e57bd28740f8)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:911f60f5-9a54-4d1c-ae99-46079d5c6143](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:911f60f5-9a54-4d1c-ae99-46079d5c6143)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:9506e609-cf28-4302-9592-7a49521d0412](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:9506e609-cf28-4302-9592-7a49521d0412)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:c5b57368-f3cc-46ed-838d-25153f471c5d](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:c5b57368-f3cc-46ed-838d-25153f471c5d)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:d6cccbbb-3fae-413f-89b9-c3d41ea25362](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:d6cccbbb-3fae-413f-89b9-c3d41ea25362)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:73ecc3c1-41b9-48a3-8c99-b29e6e02ad2d](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:73ecc3c1-41b9-48a3-8c99-b29e6e02ad2d)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:8f307e88-4208-4484-9a62-b06b9b4d4a29](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:8f307e88-4208-4484-9a62-b06b9b4d4a29)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:9e2e4859-c2f4-491c-a787-5f3aeec93ef6](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:9e2e4859-c2f4-491c-a787-5f3aeec93ef6)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:b8d107f5-5888-413c-a334-df87468398ad](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:b8d107f5-5888-413c-a334-df87468398ad)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:d3b2d0a8-d490-43df-8f00-f76b45cae5af](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:d3b2d0a8-d490-43df-8f00-f76b45cae5af)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:68f857d5-4de3-4f22-8daf-0b46d9699a8d](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:68f857d5-4de3-4f22-8daf-0b46d9699a8d)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:5c9d40b0-5628-4dec-9228-08fbee4bcce2](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:5c9d40b0-5628-4dec-9228-08fbee4bcce2)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:46b73e37-a453-4b19-8df0-85356a52cd8a](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:46b73e37-a453-4b19-8df0-85356a52cd8a)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:b266d7da-0852-4659-a003-820b391f7927](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:b266d7da-0852-4659-a003-820b391f7927)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:98d935c4-5f25-42de-a000-844950f1b766](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:98d935c4-5f25-42de-a000-844950f1b766)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:0774f8c5-073e-4334-97b2-5b71167dfc2b](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:0774f8c5-073e-4334-97b2-5b71167dfc2b)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:a0e4422b-1464-42a5-ac76-2901329a5c8b](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:a0e4422b-1464-42a5-ac76-2901329a5c8b)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:b068358a-d4c0-4f20-a522-ac6286181d49](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:b068358a-d4c0-4f20-a522-ac6286181d49)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:c475f14f-97b3-45ec-8a34-4f22f4931f04](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:c475f14f-97b3-45ec-8a34-4f22f4931f04)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:f366c06b-38b2-4039-b66a-8dde9a88f1f2](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:f366c06b-38b2-4039-b66a-8dde9a88f1f2)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:80bb5420-a8c4-47a6-aa73-8c96ccc9a525](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:80bb5420-a8c4-47a6-aa73-8c96ccc9a525)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:6aebe06a-54d2-4f17-87c4-940c1e22ef91](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:6aebe06a-54d2-4f17-87c4-940c1e22ef91)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:bb26a135-8281-430c-b2d0-652b752b0c15](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:bb26a135-8281-430c-b2d0-652b752b0c15)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:5e7c0d3f-235e-4507-9875-a166fb41fb35](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:5e7c0d3f-235e-4507-9875-a166fb41fb35)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:551f1882-63c9-44fb-b001-d9c2648ba6bc](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:551f1882-63c9-44fb-b001-d9c2648ba6bc)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:16a87ab8-2d62-4298-97dd-6c96f2556397](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:16a87ab8-2d62-4298-97dd-6c96f2556397)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:521e32a5-bdc3-4530-a878-644299792594](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:521e32a5-bdc3-4530-a878-644299792594)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:2419897b-0da3-41f2-a34f-d92ccff3a9e2](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:2419897b-0da3-41f2-a34f-d92ccff3a9e2)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:67c4985f-2ed1-43d2-a631-6261a66f7c8e](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:67c4985f-2ed1-43d2-a631-6261a66f7c8e)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:6176fae2-ef4e-4bb5-aae6-f7d6e41efc3f](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:6176fae2-ef4e-4bb5-aae6-f7d6e41efc3f)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:c6abe161-5c9a-4d56-9817-917162f1e453](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:c6abe161-5c9a-4d56-9817-917162f1e453)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:b8be3518-b3ff-43a0-b8a4-5310a9ada50d](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:b8be3518-b3ff-43a0-b8a4-5310a9ada50d)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:b1256dde-1380-4ed5-95bb-8ebdcce08774](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:b1256dde-1380-4ed5-95bb-8ebdcce08774)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:50b2b804-bd99-4d30-951a-b536d3e56bf9](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:50b2b804-bd99-4d30-951a-b536d3e56bf9)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:c4177a93-1966-4fe3-bb02-ec5212b11a17](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:c4177a93-1966-4fe3-bb02-ec5212b11a17)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:775c5cc0-ae6d-4871-a8bb-c6919ef6b8c2](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:775c5cc0-ae6d-4871-a8bb-c6919ef6b8c2)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:c66bb2f7-e174-4795-a4d8-b71861080d73](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:c66bb2f7-e174-4795-a4d8-b71861080d73)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:01e063e2-505e-4e88-a571-487cba934da0](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:01e063e2-505e-4e88-a571-487cba934da0)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:1ad08cb8-8a19-4ee7-8090-a7c41c87f3d6](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:1ad08cb8-8a19-4ee7-8090-a7c41c87f3d6)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:47e67fa7-7cc6-42df-a455-b4c76c53ae56](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:47e67fa7-7cc6-42df-a455-b4c76c53ae56)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:16151a07-a931-4de5-acde-fb95b4473d1f](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:16151a07-a931-4de5-acde-fb95b4473d1f)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:4f276f57-6429-4830-938a-ed8f5f80e668](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:4f276f57-6429-4830-938a-ed8f5f80e668)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:fbddcd79-2096-4d2e-9884-fff079fc4bb2](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:fbddcd79-2096-4d2e-9884-fff079fc4bb2)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:49f59271-fe50-4917-9133-0b52d2e485cf](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:49f59271-fe50-4917-9133-0b52d2e485cf)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:32224a86-369a-46bb-8824-c56873b8df1d](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:32224a86-369a-46bb-8824-c56873b8df1d)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:936d68b8-3f6c-4913-adbe-cbde3db52e32](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:936d68b8-3f6c-4913-adbe-cbde3db52e32)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:7d0c44d0-2898-432d-bebb-58aeb0b9c5db](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:7d0c44d0-2898-432d-bebb-58aeb0b9c5db)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:561cb679-d7d3-4bed-b4e8-11f6f602bc81](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:561cb679-d7d3-4bed-b4e8-11f6f602bc81)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:2e573a9c-1c0e-4c43-af43-8f46245b06fb](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:2e573a9c-1c0e-4c43-af43-8f46245b06fb)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:5ec0e661-b7e2-4f16-bf40-010350a9e16c](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:5ec0e661-b7e2-4f16-bf40-010350a9e16c)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:99258028-9b1b-40ef-8f1a-3c7cd8c0bb27](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:99258028-9b1b-40ef-8f1a-3c7cd8c0bb27)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:442c5ac4-a40d-4fc6-90d8-db4594cde0cd](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:442c5ac4-a40d-4fc6-90d8-db4594cde0cd)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:97f2fc00-b629-4189-9925-73063b98aabc](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:97f2fc00-b629-4189-9925-73063b98aabc)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:5c2c34cb-ecfa-4c8e-b1a8-ec7487f708f4](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:5c2c34cb-ecfa-4c8e-b1a8-ec7487f708f4)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:1992e134-bb50-444e-9ee4-d1b3089f9088](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:1992e134-bb50-444e-9ee4-d1b3089f9088)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:fa4043a7-393d-4e8d-9eee-1766fde861dd](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:fa4043a7-393d-4e8d-9eee-1766fde861dd)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:5cee7312-69f8-4a15-9f48-8aa4833bd628](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:5cee7312-69f8-4a15-9f48-8aa4833bd628)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:eec0f329-1f83-4c16-bd65-aeae879c5566](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:eec0f329-1f83-4c16-bd65-aeae879c5566)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:3be1d80a-6cdf-410a-abce-36dc51dabbc3](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:3be1d80a-6cdf-410a-abce-36dc51dabbc3)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:c60bca70-2dc9-448f-8031-5f3274b17f42](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:c60bca70-2dc9-448f-8031-5f3274b17f42)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:503c45b1-c5c2-4675-a186-c8f5a57d122b](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:503c45b1-c5c2-4675-a186-c8f5a57d122b)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:7e3ea768-5c13-4d2c-93e7-664e83a9c553](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:7e3ea768-5c13-4d2c-93e7-664e83a9c553)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:613a6f20-c5f2-4678-9d9c-9c948d60d9e5](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:613a6f20-c5f2-4678-9d9c-9c948d60d9e5)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:262d5b68-4371-408f-8750-646c8f938a33](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:262d5b68-4371-408f-8750-646c8f938a33)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:4b66482b-8e2f-4f76-b4fa-44b1ba91fa98](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:4b66482b-8e2f-4f76-b4fa-44b1ba91fa98)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:1dd8899c-b9bd-4646-87a7-25701cb3bb7c](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:1dd8899c-b9bd-4646-87a7-25701cb3bb7c)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:9097b22c-5ec7-4073-8e8b-3ebda5cb1c19](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:9097b22c-5ec7-4073-8e8b-3ebda5cb1c19)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:f8aa794f-a54b-4025-8c0c-8162a79745ee](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:f8aa794f-a54b-4025-8c0c-8162a79745ee)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:093c3e41-5b33-4558-86d4-c3bd879e3778](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:093c3e41-5b33-4558-86d4-c3bd879e3778)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:8c8e8670-b1f4-4a70-a916-c69ae780fc88](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:8c8e8670-b1f4-4a70-a916-c69ae780fc88)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:e94a5bda-e810-4bbb-aaff-538ab4846ba0](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:e94a5bda-e810-4bbb-aaff-538ab4846ba0)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:0e24e8d0-2898-4afa-a8c3-15f563ade93f](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:0e24e8d0-2898-4afa-a8c3-15f563ade93f)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:410cc56f-445e-45fc-98fb-2d8998fc0b18](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:410cc56f-445e-45fc-98fb-2d8998fc0b18)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:49e20e20-0616-41d4-a4b0-0d2450307b34](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:49e20e20-0616-41d4-a4b0-0d2450307b34)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:aab1c921-cb9b-4bb2-b198-213e5d51f382](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:aab1c921-cb9b-4bb2-b198-213e5d51f382)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:e305e366-84ab-4ce0-938b-96b3fa6e372a](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:e305e366-84ab-4ce0-938b-96b3fa6e372a)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:65d60c41-5e5e-47a3-aa57-2eaa5265d451](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:65d60c41-5e5e-47a3-aa57-2eaa5265d451)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:e76d5820-65e7-4f65-94cc-48b9b646557e](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:e76d5820-65e7-4f65-94cc-48b9b646557e)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:f2d2460c-e9d0-4a02-ae3d-06a65e608e69](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:f2d2460c-e9d0-4a02-ae3d-06a65e608e69)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:df2c1ef3-1d77-411c-bdda-ba0f0ad20649](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:df2c1ef3-1d77-411c-bdda-ba0f0ad20649)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:d7dfbc4e-fae0-4f0e-98aa-3ef3c9a2a893](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:d7dfbc4e-fae0-4f0e-98aa-3ef3c9a2a893)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:1dbfcd6b-9fae-4df1-97be-cc6a331840b6](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:1dbfcd6b-9fae-4df1-97be-cc6a331840b6)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:0ce6cb59-1f98-4a2b-82fa-6819f217866f](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:0ce6cb59-1f98-4a2b-82fa-6819f217866f)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:79d65e28-ea8a-40dd-89a6-32ee266af46d](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:79d65e28-ea8a-40dd-89a6-32ee266af46d)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:a6db3ab3-d6dd-41a3-bc76-3fc7edd440b2](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:a6db3ab3-d6dd-41a3-bc76-3fc7edd440b2)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:ff3a3436-fdc4-4214-a2f8-eb2ea0d80e26](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:ff3a3436-fdc4-4214-a2f8-eb2ea0d80e26)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:622547ef-076a-4aba-90cc-f899b75bd282](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:622547ef-076a-4aba-90cc-f899b75bd282)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:a969e5b6-ba2a-44c6-af7b-c070d6ed0f31](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:a969e5b6-ba2a-44c6-af7b-c070d6ed0f31)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:714dcaff-35e2-48bc-b606-d2395b4f1b62](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:714dcaff-35e2-48bc-b606-d2395b4f1b62)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:4c1ffe40-31f2-4866-b9a0-abf52604ec52](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:4c1ffe40-31f2-4866-b9a0-abf52604ec52)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:0db6ae91-de4f-4383-9f33-8a493b3d6326](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:0db6ae91-de4f-4383-9f33-8a493b3d6326)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:individual:0e53f41a-0150-40fe-9459-0cbf1f886a11](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/individual/urn:ngsi-ld:individual:0e53f41a-0150-40fe-9459-0cbf1f886a11)

- **Type:** individual
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:47 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to individual (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### organization Objects

#### Object: [urn:ngsi-ld:organization:00026ead-d16c-40ee-9218-48defc7ce749](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:00026ead-d16c-40ee-9218-48defc7ce749)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:a2f5ebea-49c9-4015-a9d6-56f2c566f6c9](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:a2f5ebea-49c9-4015-a9d6-56f2c566f6c9)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:d8dcc7a3-0774-4824-b552-d05d91986565](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:d8dcc7a3-0774-4824-b552-d05d91986565)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:c2c39ab0-1f15-40f9-89ce-fc131953d33e](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:c2c39ab0-1f15-40f9-89ce-fc131953d33e)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:4eb54a0c-a916-499a-bf5f-6bba76101e1e](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:4eb54a0c-a916-499a-bf5f-6bba76101e1e)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:fb47dd79-6497-4ec8-8456-e6e06d3c698b](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:fb47dd79-6497-4ec8-8456-e6e06d3c698b)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:44c33614-df98-459e-b710-064b1a7c6f65](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:44c33614-df98-459e-b710-064b1a7c6f65)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:6c53e937-212b-4e8b-997c-4d8695f789d1](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:6c53e937-212b-4e8b-997c-4d8695f789d1)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:338282a4-3c06-41d0-8c35-3fe5cecc38db](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:338282a4-3c06-41d0-8c35-3fe5cecc38db)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:3c9beb13-1187-4d67-9ecf-5e6825ffb2fd](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:3c9beb13-1187-4d67-9ecf-5e6825ffb2fd)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:5ca475ec-52d3-4a0c-a1d5-0071ef09b59d](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:5ca475ec-52d3-4a0c-a1d5-0071ef09b59d)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:e4fa0e9f-1779-49c0-9e8a-66a02bf1fe4e](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:e4fa0e9f-1779-49c0-9e8a-66a02bf1fe4e)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:5f4a3634-efba-4e25-bf15-569492850093](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:5f4a3634-efba-4e25-bf15-569492850093)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:ae659146-0bab-434f-820c-6fb46701f553](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:ae659146-0bab-434f-820c-6fb46701f553)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:df924e5d-e8c8-4ea4-aca8-edaf5acdc109](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:df924e5d-e8c8-4ea4-aca8-edaf5acdc109)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:95fdc12e-6889-4f08-8ff8-296b10e8e781](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:95fdc12e-6889-4f08-8ff8-296b10e8e781)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:eb6647da-84f2-4645-8d9f-c2905775b561](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:eb6647da-84f2-4645-8d9f-c2905775b561)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:3d660d74-8f2a-444f-9451-9a6c8a0b3b66](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:3d660d74-8f2a-444f-9451-9a6c8a0b3b66)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:2bcbe859-e316-42f2-919c-f470cff9e235](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:2bcbe859-e316-42f2-919c-f470cff9e235)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:339fb0e7-3d61-4022-8d64-84a8dbe610f8](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:339fb0e7-3d61-4022-8d64-84a8dbe610f8)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:add54e87-7742-4072-a88c-789b24b92d03](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:add54e87-7742-4072-a88c-789b24b92d03)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:649e20ba-8cdc-4090-ba5e-a835b63123fc](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:649e20ba-8cdc-4090-ba5e-a835b63123fc)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:f465f0c1-b735-49f1-a1e1-c02200f250e9](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:f465f0c1-b735-49f1-a1e1-c02200f250e9)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:3af4da45-59b1-4271-84b4-d3e87bc907ae](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:3af4da45-59b1-4271-84b4-d3e87bc907ae)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:1fc74f3a-d918-4116-8d64-163b11cf8170](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:1fc74f3a-d918-4116-8d64-163b11cf8170)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:63ded74e-f2b5-4f73-a34b-3422f5ff3fee](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:63ded74e-f2b5-4f73-a34b-3422f5ff3fee)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:organization:7d7f8848-5829-4ec7-b8ca-4777b94c62b6](https://tmf.dome-marketplace-sbx.org/tmf-api/party/v4/organization/urn:ngsi-ld:organization:7d7f8848-5829-4ec7-b8ca-4777b94c62b6)

- **Type:** organization
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:45 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to organization (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### product Objects

#### Object: [urn:ngsi-ld:product:45eaa84b-122f-4e6d-9797-31ab1ab16134](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:45eaa84b-122f-4e6d-9797-31ab1ab16134)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:b0a89e11-6fde-4bd0-948b-508088655e63](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:b0a89e11-6fde-4bd0-948b-508088655e63)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:34c6acaf-e895-4747-b371-6410d05e6a73](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:34c6acaf-e895-4747-b371-6410d05e6a73)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:0226d089-0f29-4ac5-a78e-9ca7fc8e4488](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:0226d089-0f29-4ac5-a78e-9ca7fc8e4488)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:3fddee64-1256-496a-aa15-cdcf69b26642](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:3fddee64-1256-496a-aa15-cdcf69b26642)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:eb8c00a0-f013-4d7a-9b3c-477a72c0cd01](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:eb8c00a0-f013-4d7a-9b3c-477a72c0cd01)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:61540da5-526b-4063-b783-cd4e2c0c7d2f](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:61540da5-526b-4063-b783-cd4e2c0c7d2f)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:e308688a-28bd-479c-87c5-ee3ea307dcde](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:e308688a-28bd-479c-87c5-ee3ea307dcde)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:c34b7125-ee54-460a-87aa-e542d047aa50](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:c34b7125-ee54-460a-87aa-e542d047aa50)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:1993a294-196e-495b-948a-eec015d895d4](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:1993a294-196e-495b-948a-eec015d895d4)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:76c8df70-fea8-496b-88b5-90a1ed1b6430](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:76c8df70-fea8-496b-88b5-90a1ed1b6430)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:71963e8a-b738-48e7-9fed-2191b904dc44](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:71963e8a-b738-48e7-9fed-2191b904dc44)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:67103076-a396-45bc-ad7b-f58065e5e002](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:67103076-a396-45bc-ad7b-f58065e5e002)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:6a86f9b0-b00f-4fd9-b117-48304c543964](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:6a86f9b0-b00f-4fd9-b117-48304c543964)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:a0e4e826-71e4-40f6-a322-f9fd7f4521e4](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:a0e4e826-71e4-40f6-a322-f9fd7f4521e4)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:da4ddcd9-5f05-4599-a064-bcf26ad2a195](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:da4ddcd9-5f05-4599-a064-bcf26ad2a195)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:e7537033-063f-4394-add9-41fed7b2c736](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:e7537033-063f-4394-add9-41fed7b2c736)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:30187daf-064b-4c00-a00d-ffad86e8eb8c](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:30187daf-064b-4c00-a00d-ffad86e8eb8c)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:fe1d79a5-c1d5-4d60-8324-573326e3a65d](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:fe1d79a5-c1d5-4d60-8324-573326e3a65d)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:02e5916d-b80f-4847-863d-1e888a968a92](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:02e5916d-b80f-4847-863d-1e888a968a92)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:fd806e4d-33ca-4933-bed7-3e79657ce80f](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:fd806e4d-33ca-4933-bed7-3e79657ce80f)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:f3a29112-f559-4c68-b5af-ec9821732c44](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:f3a29112-f559-4c68-b5af-ec9821732c44)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:20e796a3-a53f-4f09-a27c-8c1c38d94a9a](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:20e796a3-a53f-4f09-a27c-8c1c38d94a9a)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:8f4823ca-1b5c-4625-92b0-45c852a0ded8](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:8f4823ca-1b5c-4625-92b0-45c852a0ded8)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:7f639423-63e1-4e1a-bcc9-477eaf234501](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:7f639423-63e1-4e1a-bcc9-477eaf234501)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:09b6a975-f510-4ef5-97bd-ac5d00d9c01b](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:09b6a975-f510-4ef5-97bd-ac5d00d9c01b)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:7575d6d5-4a32-4a99-8f72-5715c005e23d](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:7575d6d5-4a32-4a99-8f72-5715c005e23d)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:0b3acbf0-c65c-4749-b86b-6d5fdc196b6b](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:0b3acbf0-c65c-4749-b86b-6d5fdc196b6b)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:4c97c536-79bd-433c-8ab2-3fcaac888bdb](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:4c97c536-79bd-433c-8ab2-3fcaac888bdb)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:d0dc9008-e514-40aa-bcb4-761b79c28707](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:d0dc9008-e514-40aa-bcb4-761b79c28707)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:92c65cc5-bd77-4182-92b3-4d521ae1dfe2](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:92c65cc5-bd77-4182-92b3-4d521ae1dfe2)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:8cae331e-5901-4fb3-9ce9-a122f0039a92](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:8cae331e-5901-4fb3-9ce9-a122f0039a92)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:6e0784ed-5028-44f2-9207-a861bf6d0500](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:6e0784ed-5028-44f2-9207-a861bf6d0500)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:6d6bd534-9782-4e5d-9ad0-268c6abce924](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:6d6bd534-9782-4e5d-9ad0-268c6abce924)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:a5680a3a-6953-4a34-a8ea-56ca3f6e99cd](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:a5680a3a-6953-4a34-a8ea-56ca3f6e99cd)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:23ac0ab2-9c03-43ed-9d0c-0688f84f7f00](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:23ac0ab2-9c03-43ed-9d0c-0688f84f7f00)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:1e642558-761a-4155-abf7-fc47f27c47b5](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:1e642558-761a-4155-abf7-fc47f27c47b5)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:8a0e52f2-3cb2-4389-b6ce-501e0169da5f](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:8a0e52f2-3cb2-4389-b6ce-501e0169da5f)

- **Type:** product
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product:374535f1-5e66-4b22-9e13-ff89c097413c](https://tmf.dome-marketplace-sbx.org/tmf-api/productInventory/v4/product/urn:ngsi-ld:product:374535f1-5e66-4b22-9e13-ff89c097413c)

- **Type:** product
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to product (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### productOffering Objects

#### Object: [urn:ngsi-ld:product-offering:005974a1-f327-47bd-96fc-2c263f2818c4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:005974a1-f327-47bd-96fc-2c263f2818c4)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:4174966c-aca0-4787-88fe-96dd235fa2df](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:4174966c-aca0-4787-88fe-96dd235fa2df)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:17f86010-d4c4-4120-99f5-25d25f376bbb](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:17f86010-d4c4-4120-99f5-25d25f376bbb)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:9bbc3d54-daae-414e-a63a-52fa06dfcd0f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:9bbc3d54-daae-414e-a63a-52fa06dfcd0f)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:dcdd91b1-22ee-41e2-968b-24289c077e18](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:dcdd91b1-22ee-41e2-968b-24289c077e18)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:7bbf2620-43fe-4afe-b2ff-cfe83f78484a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:7bbf2620-43fe-4afe-b2ff-cfe83f78484a)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:1c9bdbba-e2bf-4b24-8586-9d01f8900cf1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:1c9bdbba-e2bf-4b24-8586-9d01f8900cf1)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:66b48359-1d47-42af-a974-1c40ee50f3dd](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:66b48359-1d47-42af-a974-1c40ee50f3dd)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:54a9af6f-f353-48a5-b599-84a535f0bc74](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:54a9af6f-f353-48a5-b599-84a535f0bc74)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:4699bdc1-592a-42b0-ad2d-93b0a06b044a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:4699bdc1-592a-42b0-ad2d-93b0a06b044a)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:2135b6c4-6de8-4ec9-9790-a3a322650a8a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:2135b6c4-6de8-4ec9-9790-a3a322650a8a)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:fd2bd8d2-f504-4254-9d2b-f248534d4351](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:fd2bd8d2-f504-4254-9d2b-f248534d4351)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:887a7ba9-2626-4f88-9252-5bc20239f61a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:887a7ba9-2626-4f88-9252-5bc20239f61a)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:98f94a51-6c8b-4778-a39b-10f3428428b7](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:98f94a51-6c8b-4778-a39b-10f3428428b7)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:f85cc2c5-36e3-40b9-bf3d-4de468571c83](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:f85cc2c5-36e3-40b9-bf3d-4de468571c83)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:046b7413-46e5-404d-b6f1-e8d7f0db20e1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:046b7413-46e5-404d-b6f1-e8d7f0db20e1)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:71d584b8-486b-4f47-ba95-e328474a8236](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:71d584b8-486b-4f47-ba95-e328474a8236)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:af3e6eb5-6fac-4e6c-8675-75807b938d88](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:af3e6eb5-6fac-4e6c-8675-75807b938d88)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:8683c5f5-220c-4341-81df-dd29be9acd78](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:8683c5f5-220c-4341-81df-dd29be9acd78)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:686f78fc-4b21-4c4c-9f1f-0cb8ee9fd1c9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:686f78fc-4b21-4c4c-9f1f-0cb8ee9fd1c9)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:dcb09973-7df6-42fd-86c4-6b5d79e00374](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:dcb09973-7df6-42fd-86c4-6b5d79e00374)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:a1f60a8c-010c-42f6-a0fd-f5e1884a8212](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:a1f60a8c-010c-42f6-a0fd-f5e1884a8212)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:e7dacb3f-7332-428f-8d1a-59a86ffc5985](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:e7dacb3f-7332-428f-8d1a-59a86ffc5985)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:7f4b87dc-ef28-4579-99ad-6680d48947c3](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:7f4b87dc-ef28-4579-99ad-6680d48947c3)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:87a8fa81-4b13-446b-9bdb-abfdc9e20dff](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:87a8fa81-4b13-446b-9bdb-abfdc9e20dff)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:75400f3b-452f-4b76-b98e-134179eb56bd](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:75400f3b-452f-4b76-b98e-134179eb56bd)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:19121875-d09e-4de0-bf2d-5f07c8b65d2f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:19121875-d09e-4de0-bf2d-5f07c8b65d2f)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:9c8d762d-691f-4a91-a8ad-e5d479353756](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:9c8d762d-691f-4a91-a8ad-e5d479353756)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:d61bda3f-7b40-4417-b140-057178b2c6ae](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:d61bda3f-7b40-4417-b140-057178b2c6ae)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:b60af935-1059-41cf-a789-e8593500eaec](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:b60af935-1059-41cf-a789-e8593500eaec)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:b51ce551-5844-4f1d-8f73-b420b799347d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:b51ce551-5844-4f1d-8f73-b420b799347d)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:f1646ae0-a1c6-4655-b24a-681b1114f88b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:f1646ae0-a1c6-4655-b24a-681b1114f88b)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:620c434b-f829-44f3-9161-21c97c733225](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:620c434b-f829-44f3-9161-21c97c733225)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:208c28e6-23af-4f00-8608-bafb5db10ce7](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:208c28e6-23af-4f00-8608-bafb5db10ce7)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:bd9bb9be-79b6-44e0-a3f7-b4e1eb1400ac](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:bd9bb9be-79b6-44e0-a3f7-b4e1eb1400ac)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:0de55201-a30a-4ba8-b92c-5729037d5773](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:0de55201-a30a-4ba8-b92c-5729037d5773)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:6caa329a-713f-4816-aab0-daad3536fe7a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:6caa329a-713f-4816-aab0-daad3536fe7a)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:afd19732-3509-4e52-9fe5-1bd47ab311d8](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:afd19732-3509-4e52-9fe5-1bd47ab311d8)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:7c38669c-9b54-4e03-a0ac-862e8d6850ca](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:7c38669c-9b54-4e03-a0ac-862e8d6850ca)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:f5353acd-ee1d-41b6-80d6-d3eb6ac86640](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:f5353acd-ee1d-41b6-80d6-d3eb6ac86640)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:055a8b41-f80e-4835-80f1-b8cb10d27109](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:055a8b41-f80e-4835-80f1-b8cb10d27109)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:abadbea7-1c87-46b4-b391-9110ccd7519c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:abadbea7-1c87-46b4-b391-9110ccd7519c)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:7b2fc7ad-1835-4688-9e8e-c88fc47ec179](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:7b2fc7ad-1835-4688-9e8e-c88fc47ec179)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:6b357653-81fe-4cfc-8423-19d6752822b0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:6b357653-81fe-4cfc-8423-19d6752822b0)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:41bab3d8-d030-41fb-aa74-a9ce18d80899](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:41bab3d8-d030-41fb-aa74-a9ce18d80899)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:5b9eecc9-6005-4ac2-a334-c2351e89f001](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:5b9eecc9-6005-4ac2-a334-c2351e89f001)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:e70c66c4-3581-46da-be85-1d655b5ce31c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:e70c66c4-3581-46da-be85-1d655b5ce31c)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:c1790fda-d88a-4303-bc4b-fb99ea5df960](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:c1790fda-d88a-4303-bc4b-fb99ea5df960)

- **Type:** productOffering
- **Valid:** true
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:b84d9559-b141-4d2a-804b-04569dd3e974](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:b84d9559-b141-4d2a-804b-04569dd3e974)

- **Type:** productOffering
- **Valid:** true
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:d9b8267a-58a7-48b8-b0a9-2b6ee9a0c704](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:d9b8267a-58a7-48b8-b0a9-2b6ee9a0c704)

- **Type:** productOffering
- **Valid:** true
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:140a6dd1-1d81-4959-8dbf-bf1bb46716c1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:140a6dd1-1d81-4959-8dbf-bf1bb46716c1)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:1aa3bc34-c9f1-464f-ac60-2f8ac135128b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:1aa3bc34-c9f1-464f-ac60-2f8ac135128b)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:d7a31bd0-5533-4216-94e3-694a0c69d1d2](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:d7a31bd0-5533-4216-94e3-694a0c69d1d2)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:357b3085-96d6-4421-a338-64a1e69777fd](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:357b3085-96d6-4421-a338-64a1e69777fd)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:4ec3e3c5-4d7d-4229-bd52-9fa0f96913d1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:4ec3e3c5-4d7d-4229-bd52-9fa0f96913d1)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:ba7b06f5-3e7e-436a-ab4d-2ec838968e08](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:ba7b06f5-3e7e-436a-ab4d-2ec838968e08)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:ef81e5dd-1ad8-4772-9972-575b950613d9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:ef81e5dd-1ad8-4772-9972-575b950613d9)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:9a79836f-30d8-4369-a094-7d2c043367da](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:9a79836f-30d8-4369-a094-7d2c043367da)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:ebafb975-3b08-4bff-b23a-c0eab2a54f7c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:ebafb975-3b08-4bff-b23a-c0eab2a54f7c)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:bf99c912-02ac-4688-bb15-518704bb456f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:bf99c912-02ac-4688-bb15-518704bb456f)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:38a866e7-02c6-42c4-9a67-1c611285d20c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:38a866e7-02c6-42c4-9a67-1c611285d20c)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:3410a365-1970-4911-920d-dc4ecf7d3722](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:3410a365-1970-4911-920d-dc4ecf7d3722)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering:ef686301-fb7f-44d8-9bf8-0459276ce241](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:ef686301-fb7f-44d8-9bf8-0459276ce241)

- **Type:** productOffering
- **Valid:** true
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:5498acd0-7cb0-410e-b9e7-794e8dc01260](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:5498acd0-7cb0-410e-b9e7-794e8dc01260)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:ef0fc302-62de-4a73-a326-aef165e7a29c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:ef0fc302-62de-4a73-a326-aef165e7a29c)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:27aa720f-7e3e-445e-8e56-b74751886647](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:27aa720f-7e3e-445e-8e56-b74751886647)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:e99cd5c4-7444-466e-9f18-e2303cb08698](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:e99cd5c4-7444-466e-9f18-e2303cb08698)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering:9e7982c7-acee-4541-81d0-423a9da177f9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOffering/urn:ngsi-ld:product-offering:9e7982c7-acee-4541-81d0-423a9da177f9)

- **Type:** productOffering
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:09 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOffering (Code: MISSING_RECOMMENDED_FIELD)

### productOfferingPrice Objects

#### Object: [urn:ngsi-ld:product-offering-price:24934d22-46b7-44b7-a250-c74e8ea443d1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:24934d22-46b7-44b7-a250-c74e8ea443d1)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:d989cd04-4d33-41a9-a5b2-f5e0839db9f9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:d989cd04-4d33-41a9-a5b2-f5e0839db9f9)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:43afdc36-6981-4019-8f58-d69f56f40f6e](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:43afdc36-6981-4019-8f58-d69f56f40f6e)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:5cce5f34-9a42-4a9d-991e-b72845ded1a9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:5cce5f34-9a42-4a9d-991e-b72845ded1a9)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:b3eb4c12-803f-4fec-8925-9a333d6f587a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:b3eb4c12-803f-4fec-8925-9a333d6f587a)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:a824e4b5-b235-434b-acc5-5db0199432f3](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:a824e4b5-b235-434b-acc5-5db0199432f3)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:a0f8fe96-f382-4f56-aae6-6d90cec6797e](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:a0f8fe96-f382-4f56-aae6-6d90cec6797e)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:16a1dc71-7e91-40d2-b07e-d8e5e275cf8a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:16a1dc71-7e91-40d2-b07e-d8e5e275cf8a)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:fa293088-a161-4640-9f5d-869072853b84](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:fa293088-a161-4640-9f5d-869072853b84)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:1f66f58d-6a2b-4014-aa89-be103f992dea](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:1f66f58d-6a2b-4014-aa89-be103f992dea)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:4bffd57e-6868-44d2-a750-15eb3ef19a94](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:4bffd57e-6868-44d2-a750-15eb3ef19a94)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:fba7585e-2fbb-4c29-a54d-902340ad158a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:fba7585e-2fbb-4c29-a54d-902340ad158a)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:3a0fbcbb-d241-4692-8a4a-045f8c9a459c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:3a0fbcbb-d241-4692-8a4a-045f8c9a459c)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:3ae20fb5-4c93-4e28-8803-fb08cdb495c6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:3ae20fb5-4c93-4e28-8803-fb08cdb495c6)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:dc88b199-207f-4f21-8f92-e16470a10b02](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:dc88b199-207f-4f21-8f92-e16470a10b02)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:61d36718-e1af-40af-9dd4-d46ba5f39ad4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:61d36718-e1af-40af-9dd4-d46ba5f39ad4)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:6e13c06d-c2a4-49c9-99f5-5d5b7fb2c3fd](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:6e13c06d-c2a4-49c9-99f5-5d5b7fb2c3fd)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:9f9a4fbe-b6cc-4cdf-be9e-418fa25ff7f6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:9f9a4fbe-b6cc-4cdf-be9e-418fa25ff7f6)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:50124c9d-4cd8-4a4d-ba7e-2a49dd08e951](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:50124c9d-4cd8-4a4d-ba7e-2a49dd08e951)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:0fe122dd-0dbd-4502-8cc9-de9d50359fd0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:0fe122dd-0dbd-4502-8cc9-de9d50359fd0)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:4f74eb07-202c-40f9-bbb8-c7d276e71df0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:4f74eb07-202c-40f9-bbb8-c7d276e71df0)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:d4cc9f2f-73d5-417d-9a54-2da4a45281cd](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:d4cc9f2f-73d5-417d-9a54-2da4a45281cd)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:bae86ed8-38d4-4cd4-98fa-193d47a7c39d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:bae86ed8-38d4-4cd4-98fa-193d47a7c39d)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:5764025c-0b6a-4634-91fc-54e139397ccd](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:5764025c-0b6a-4634-91fc-54e139397ccd)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:c50488b4-bd60-40ad-af06-837d76065d28](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:c50488b4-bd60-40ad-af06-837d76065d28)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:2d533789-dca5-4158-bb5b-2bf48c61c738](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:2d533789-dca5-4158-bb5b-2bf48c61c738)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:3da6a9ac-6d05-4225-936c-95ff20d6314a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:3da6a9ac-6d05-4225-936c-95ff20d6314a)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:d56ef6d2-5450-4699-b487-f62582c4e005](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:d56ef6d2-5450-4699-b487-f62582c4e005)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:a935eb24-c8a2-4b85-844c-8d72c89f4448](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:a935eb24-c8a2-4b85-844c-8d72c89f4448)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:fd1c14f0-6a1f-4119-88f1-ae2b16a31b27](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:fd1c14f0-6a1f-4119-88f1-ae2b16a31b27)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:7159ac41-6541-41af-9bde-7a8f1f4b6504](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:7159ac41-6541-41af-9bde-7a8f1f4b6504)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:f3b33b3e-d6de-4ff0-a8f4-8c049a4c4b83](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:f3b33b3e-d6de-4ff0-a8f4-8c049a4c4b83)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:af5f1f67-c4ab-4ddf-bf42-f9ace2975b05](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:af5f1f67-c4ab-4ddf-bf42-f9ace2975b05)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:21de9359-96c9-4274-bfde-2351324ed426](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:21de9359-96c9-4274-bfde-2351324ed426)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:6523ecb7-b6c4-47ef-ab86-1f827c9e99d0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:6523ecb7-b6c4-47ef-ab86-1f827c9e99d0)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:ac33232f-d8f5-4388-a705-b4fbbdc96c48](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:ac33232f-d8f5-4388-a705-b4fbbdc96c48)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:889ae01f-a833-44ce-aa08-ecc1b0158931](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:889ae01f-a833-44ce-aa08-ecc1b0158931)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:b6e9523f-f259-4574-aa2f-1630b120a171](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:b6e9523f-f259-4574-aa2f-1630b120a171)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:646a7334-2ae2-4182-8ae6-4e24f8ddb21d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:646a7334-2ae2-4182-8ae6-4e24f8ddb21d)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:258cbab9-c6b8-4435-8bfe-0288ead01108](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:258cbab9-c6b8-4435-8bfe-0288ead01108)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:c4d80434-af55-4483-916f-7df7be8eac3c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:c4d80434-af55-4483-916f-7df7be8eac3c)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:49648693-b36b-4eb2-954d-75438ed8fff8](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:49648693-b36b-4eb2-954d-75438ed8fff8)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:6ccf2ee9-6ae2-4019-b5c9-8d7b64025f98](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:6ccf2ee9-6ae2-4019-b5c9-8d7b64025f98)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:012db45a-5e82-4738-aff0-ff3d065ee194](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:012db45a-5e82-4738-aff0-ff3d065ee194)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:ddd90524-e862-49af-b01e-22e906a18e27](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:ddd90524-e862-49af-b01e-22e906a18e27)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:21e2b57f-1512-4053-b08e-c3d309580c24](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:21e2b57f-1512-4053-b08e-c3d309580c24)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:86f7d405-fada-4bf3-97c3-1afa8b671d8e](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:86f7d405-fada-4bf3-97c3-1afa8b671d8e)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:d46a935e-ff10-4b16-95c2-4c00897c1c89](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:d46a935e-ff10-4b16-95c2-4c00897c1c89)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:7c337e51-20da-4083-8241-28d5be7a5887](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:7c337e51-20da-4083-8241-28d5be7a5887)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:775bc3c7-e63d-4ee8-8c90-d0d0c18dadc7](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:775bc3c7-e63d-4ee8-8c90-d0d0c18dadc7)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:d65d6d85-bb29-4d10-88b0-bcfdb98db24a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:d65d6d85-bb29-4d10-88b0-bcfdb98db24a)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:19a4f8a2-fc72-4cf0-90b8-b272eaf1a098](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:19a4f8a2-fc72-4cf0-90b8-b272eaf1a098)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:1c049cbd-4307-447f-8f12-277f43f14d34](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:1c049cbd-4307-447f-8f12-277f43f14d34)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:6584eca7-5d04-4234-8e27-1754286b7cf4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:6584eca7-5d04-4234-8e27-1754286b7cf4)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:75773dfb-3159-4463-858d-2f46be394770](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:75773dfb-3159-4463-858d-2f46be394770)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:7e103d66-34d8-42b9-bb2f-ed7d581756b2](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:7e103d66-34d8-42b9-bb2f-ed7d581756b2)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:dddd5496-be8a-4d7d-8c0f-2d1be7f2bd84](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:dddd5496-be8a-4d7d-8c0f-2d1be7f2bd84)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:5df8bd48-3dd9-4dbf-a343-ab6f6e10617f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:5df8bd48-3dd9-4dbf-a343-ab6f6e10617f)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:6055443d-785b-4644-bbda-4dd25c4108bb](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:6055443d-785b-4644-bbda-4dd25c4108bb)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:c1948bd6-2559-4146-ad61-681a83068283](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:c1948bd6-2559-4146-ad61-681a83068283)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:efa9c9a1-3a7e-4e87-ae8d-fea9ea2ba5e0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:efa9c9a1-3a7e-4e87-ae8d-fea9ea2ba5e0)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:b4aa8615-1743-4260-b334-aec163ce799d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:b4aa8615-1743-4260-b334-aec163ce799d)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:ce65f509-1d37-4f93-bde1-f897df1cc250](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:ce65f509-1d37-4f93-bde1-f897df1cc250)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:8d9338c8-6a43-4ae4-a57f-96deaba612db](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:8d9338c8-6a43-4ae4-a57f-96deaba612db)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:6eed089a-0fcb-4e07-8443-87500cc4086b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:6eed089a-0fcb-4e07-8443-87500cc4086b)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:5bfe47e3-2466-4381-a22c-da072b5a333c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:5bfe47e3-2466-4381-a22c-da072b5a333c)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:aa5dddd0-44bc-4edd-a07c-8a7e8a5c8219](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:aa5dddd0-44bc-4edd-a07c-8a7e8a5c8219)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:27c7220b-33b4-4f9a-b540-75a17d4a321a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:27c7220b-33b4-4f9a-b540-75a17d4a321a)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:4a6382b9-fc5f-4b72-85ef-853f20bc941a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:4a6382b9-fc5f-4b72-85ef-853f20bc941a)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:c798d017-8e6e-40be-9f09-ce2ae7f28ba6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:c798d017-8e6e-40be-9f09-ce2ae7f28ba6)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:3e563b0c-cc92-422b-a530-87927f5342d6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:3e563b0c-cc92-422b-a530-87927f5342d6)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:4a65a9f9-037d-4694-9bcc-1206487485ff](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:4a65a9f9-037d-4694-9bcc-1206487485ff)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:80d5fe58-79a7-4691-a011-5d6d7efd0681](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:80d5fe58-79a7-4691-a011-5d6d7efd0681)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:3bb60c49-65de-4a77-bdbe-4a6ded9637f5](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:3bb60c49-65de-4a77-bdbe-4a6ded9637f5)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:08cc66ce-1df6-4a70-98fc-10f94336a732](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:08cc66ce-1df6-4a70-98fc-10f94336a732)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:c40d71ec-4a8e-4ecf-a1dc-50ed537cb915](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:c40d71ec-4a8e-4ecf-a1dc-50ed537cb915)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:5456d2c3-bd4d-4283-b49d-b5286ed5dacf](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:5456d2c3-bd4d-4283-b49d-b5286ed5dacf)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:df04f82d-08d6-44ab-a8c5-65a3108b0b6b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:df04f82d-08d6-44ab-a8c5-65a3108b0b6b)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:0ddc0dd1-467d-4292-8325-bcd727db0ce4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:0ddc0dd1-467d-4292-8325-bcd727db0ce4)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:b7663735-496f-42d0-ba20-e792e14eacd4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:b7663735-496f-42d0-ba20-e792e14eacd4)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:acd98be5-13b5-4ddf-9dc6-d6331bcab0b8](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:acd98be5-13b5-4ddf-9dc6-d6331bcab0b8)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:37b0a2bc-daa5-4f04-9b0d-5eb1ee2c7034](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:37b0a2bc-daa5-4f04-9b0d-5eb1ee2c7034)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:7b534ee7-0e93-4f33-b34c-0c6502c382b7](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:7b534ee7-0e93-4f33-b34c-0c6502c382b7)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:9b27d33c-0856-400c-ba91-36ca0669c0c7](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:9b27d33c-0856-400c-ba91-36ca0669c0c7)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:13a1d807-012c-4e7a-bd46-1ed1422e057d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:13a1d807-012c-4e7a-bd46-1ed1422e057d)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:9c17d6a9-264b-4245-a0dd-96b7b791d41f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:9c17d6a9-264b-4245-a0dd-96b7b791d41f)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:0b2dcaa4-2c1d-4d50-9bca-ca69e79facf0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:0b2dcaa4-2c1d-4d50-9bca-ca69e79facf0)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:c4b5bbf8-cac3-4477-b6a5-9a5cb50d5210](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:c4b5bbf8-cac3-4477-b6a5-9a5cb50d5210)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:c0642c81-b162-48f1-9d08-42cffe7769ce](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:c0642c81-b162-48f1-9d08-42cffe7769ce)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:f346907c-e792-4ca0-830d-21772439bfaa](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:f346907c-e792-4ca0-830d-21772439bfaa)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:7b60dfbc-dffe-40da-8c62-3dc410402a51](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:7b60dfbc-dffe-40da-8c62-3dc410402a51)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:9541b92a-8422-43b8-8bc3-2191a80c4db0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:9541b92a-8422-43b8-8bc3-2191a80c4db0)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:33358d97-bc25-45ce-96ed-6aabd2ed6fa0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:33358d97-bc25-45ce-96ed-6aabd2ed6fa0)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:f026d149-b29e-4d15-b710-5cc785808c98](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:f026d149-b29e-4d15-b710-5cc785808c98)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:e2416ee0-7778-4708-b905-5146d5376c8e](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:e2416ee0-7778-4708-b905-5146d5376c8e)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:30d168c5-9537-490d-8dfa-eb352d4d8c9b](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:30d168c5-9537-490d-8dfa-eb352d4d8c9b)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:96b1e4cb-b8b3-4fa6-acd7-9e1f47794ba0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:96b1e4cb-b8b3-4fa6-acd7-9e1f47794ba0)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:63578d82-7280-4b2d-9e85-6379f7b17d58](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:63578d82-7280-4b2d-9e85-6379f7b17d58)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:6f4fd197-816f-4ab8-988d-1e89c866d445](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:6f4fd197-816f-4ab8-988d-1e89c866d445)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:653a42f3-a031-400d-88eb-a56fa03015d8](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:653a42f3-a031-400d-88eb-a56fa03015d8)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:18 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:f1a14d42-aa5c-4197-b326-75b999e5e7a0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:f1a14d42-aa5c-4197-b326-75b999e5e7a0)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:ce3d9d28-7d35-42c9-87e4-686342e0aab0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:ce3d9d28-7d35-42c9-87e4-686342e0aab0)

- **Type:** productOfferingPrice
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:37ccf3dd-f04d-4e8f-a9c0-986ded9a06e8](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:37ccf3dd-f04d-4e8f-a9c0-986ded9a06e8)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:4c26e6ae-31f5-45d3-9e8a-1d7c39dea282](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:4c26e6ae-31f5-45d3-9e8a-1d7c39dea282)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:259c0fcc-7139-4b1f-8db1-c1578cf75bc7](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:259c0fcc-7139-4b1f-8db1-c1578cf75bc7)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:41a88f38-1d47-42f5-90b3-7b76237f2e41](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:41a88f38-1d47-42f5-90b3-7b76237f2e41)

- **Type:** productOfferingPrice
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:f45ab3ef-dcd3-4d7c-aca1-05afe98ebb47](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:f45ab3ef-dcd3-4d7c-aca1-05afe98ebb47)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:719d14ea-374b-4e90-8a6f-e5547122f25a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:719d14ea-374b-4e90-8a6f-e5547122f25a)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:a6760111-3b5b-4b03-a2b3-1af9cde04cf0](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:a6760111-3b5b-4b03-a2b3-1af9cde04cf0)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:9ebc3664-5ddd-44d8-9e0c-96c25c2efb54](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:9ebc3664-5ddd-44d8-9e0c-96c25c2efb54)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:406bcc32-a7cd-4d04-9731-20daf4b288a8](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:406bcc32-a7cd-4d04-9731-20daf4b288a8)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:da85b64f-9704-4bb5-8656-606ff5a373ce](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:da85b64f-9704-4bb5-8656-606ff5a373ce)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:81f47905-a478-448c-8dd7-2fd90fdf3904](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:81f47905-a478-448c-8dd7-2fd90fdf3904)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:3c1e391f-ccc3-4532-aa84-0577de42bfc6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:3c1e391f-ccc3-4532-aa84-0577de42bfc6)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:57cf158f-ef29-4c2a-a9a0-7e0e0717478c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:57cf158f-ef29-4c2a-a9a0-7e0e0717478c)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:b55cc65d-2c12-436c-ba02-d2c64687bdd8](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:b55cc65d-2c12-436c-ba02-d2c64687bdd8)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:d5770a00-12ee-4c43-a38d-95b13a8a75ad](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:d5770a00-12ee-4c43-a38d-95b13a8a75ad)

- **Type:** productOfferingPrice
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:47feb2d8-3879-4e7c-9634-b0c31b0c1352](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:47feb2d8-3879-4e7c-9634-b0c31b0c1352)

- **Type:** productOfferingPrice
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:338eda68-c59f-4595-9563-de1a2bfe1ccc](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:338eda68-c59f-4595-9563-de1a2bfe1ccc)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:ad722f06-991c-44eb-867d-90f7d84a904d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:ad722f06-991c-44eb-867d-90f7d84a904d)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:dcb20903-1d01-4b74-8c0e-46a2f2b920dd](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:dcb20903-1d01-4b74-8c0e-46a2f2b920dd)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:bd04cdb6-7f13-4f41-bfcd-aa65d1978c3c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:bd04cdb6-7f13-4f41-bfcd-aa65d1978c3c)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:acbd99be-2f4e-4dea-9a81-6cb797d4e1ae](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:acbd99be-2f4e-4dea-9a81-6cb797d4e1ae)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:f141d1d1-9629-4309-ae40-b8b8eb8ffeae](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:f141d1d1-9629-4309-ae40-b8b8eb8ffeae)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:0e860097-38b5-4643-a2be-5e881ae44ed1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:0e860097-38b5-4643-a2be-5e881ae44ed1)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:31a62e79-42e0-4138-a8b5-b2c23fb90f96](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:31a62e79-42e0-4138-a8b5-b2c23fb90f96)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:00c8b914-9b16-4b2f-8558-021ed2938c8e](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:00c8b914-9b16-4b2f-8558-021ed2938c8e)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:290e9b72-4ebd-42c0-99c0-c594836de666](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:290e9b72-4ebd-42c0-99c0-c594836de666)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:99bab231-81cb-4b64-81aa-7983d5d743db](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:99bab231-81cb-4b64-81aa-7983d5d743db)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:9ad9c089-efdd-473a-a744-06b477f6d230](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:9ad9c089-efdd-473a-a744-06b477f6d230)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:a4830d79-4469-4971-b695-de83143b1103](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:a4830d79-4469-4971-b695-de83143b1103)

- **Type:** productOfferingPrice
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:9f8c70a3-dde9-4925-b1f4-66baacaf5c91](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:9f8c70a3-dde9-4925-b1f4-66baacaf5c91)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:66c4f736-f668-44cb-a018-8588e07c1d59](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:66c4f736-f668-44cb-a018-8588e07c1d59)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:c0263817-5961-4164-b8f4-95042817975f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:c0263817-5961-4164-b8f4-95042817975f)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:e7d00ccb-fbca-4677-9caf-b351dbeecfd4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:e7d00ccb-fbca-4677-9caf-b351dbeecfd4)

- **Type:** productOfferingPrice
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:7694ea3b-eb1a-4125-bb27-25ca9ddfd4f4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:7694ea3b-eb1a-4125-bb27-25ca9ddfd4f4)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:b065b729-7520-4e7f-af97-cc2797dac32d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:b065b729-7520-4e7f-af97-cc2797dac32d)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:e5ec47b1-7bf9-4822-bad7-3cc3b55dc3a2](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:e5ec47b1-7bf9-4822-bad7-3cc3b55dc3a2)

- **Type:** productOfferingPrice
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:d4eb9f12-39f3-4f20-b2ec-8b1ec9fd288f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:d4eb9f12-39f3-4f20-b2ec-8b1ec9fd288f)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:56296e5a-e0b4-4e64-a99d-ce3c8c45280d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:56296e5a-e0b4-4e64-a99d-ce3c8c45280d)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:fd9a8e89-188c-4c7f-b2b5-0e6956d7f67c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:fd9a8e89-188c-4c7f-b2b5-0e6956d7f67c)

- **Type:** productOfferingPrice
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:29083f04-c3ae-4c3a-9d4f-dfe8d6350a05](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:29083f04-c3ae-4c3a-9d4f-dfe8d6350a05)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:4b0a1e05-5504-42e7-a5de-f2e04345516f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:4b0a1e05-5504-42e7-a5de-f2e04345516f)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOfferingPrice (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-offering-price:55fbbbc5-bad4-45ca-bda4-82acede8a479](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:55fbbbc5-bad4-45ca-bda4-82acede8a479)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-offering-price:85baa837-ef18-4ecc-85a2-2145b57a1cf3](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productOfferingPrice/urn:ngsi-ld:product-offering-price:85baa837-ef18-4ecc-85a2-2145b57a1cf3)

- **Type:** productOfferingPrice
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:27 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)

### productOrder Objects

#### Object: [urn:ngsi-ld:product-order:fdc85cc5-6e74-4e67-a9d0-1f3d7a79dce3](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:fdc85cc5-6e74-4e67-a9d0-1f3d7a79dce3)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:4902aa01-8949-4a46-9be4-1cf98aa4a4f7](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:4902aa01-8949-4a46-9be4-1cf98aa4a4f7)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:06350c8a-4238-4284-a9b4-f5c047b91292](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:06350c8a-4238-4284-a9b4-f5c047b91292)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:abee6b6d-f3e0-4465-bdac-bea275ddecc2](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:abee6b6d-f3e0-4465-bdac-bea275ddecc2)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:1c4401c3-4770-403e-af95-6b9737bc087a](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:1c4401c3-4770-403e-af95-6b9737bc087a)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:525f2198-45a7-44a9-a0d3-413972bb5f56](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:525f2198-45a7-44a9-a0d3-413972bb5f56)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:bfdd1be4-a32b-4017-855d-d4fdaa95818a](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:bfdd1be4-a32b-4017-855d-d4fdaa95818a)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:0c6cc039-21bd-462b-9a45-b6ec77245e96](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:0c6cc039-21bd-462b-9a45-b6ec77245e96)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:367cc7f9-2ea7-4fc8-b9d4-1f2aff2e57d0](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:367cc7f9-2ea7-4fc8-b9d4-1f2aff2e57d0)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:4ffa78f5-2b85-4c9e-b09f-00d0ecad3a44](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:4ffa78f5-2b85-4c9e-b09f-00d0ecad3a44)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:18777b58-f7d2-4570-ab6d-2917f86b3c55](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:18777b58-f7d2-4570-ab6d-2917f86b3c55)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:740e7b80-672d-4e6a-9f29-67c16469a4e1](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:740e7b80-672d-4e6a-9f29-67c16469a4e1)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:95f1cf2c-48b1-4f6c-a844-accbb3c8816c](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:95f1cf2c-48b1-4f6c-a844-accbb3c8816c)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:fe85000e-ad28-441c-94ac-e5648df09280](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:fe85000e-ad28-441c-94ac-e5648df09280)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:898c190e-94d6-486d-a9d5-d19efb3d0c07](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:898c190e-94d6-486d-a9d5-d19efb3d0c07)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:803f018a-e174-4871-b87f-0c348a0a5b94](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:803f018a-e174-4871-b87f-0c348a0a5b94)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:88870dfa-14be-4a22-98d1-3186b78f1778](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:88870dfa-14be-4a22-98d1-3186b78f1778)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:d4277dff-1a6d-4907-9862-5fe0f1479469](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:d4277dff-1a6d-4907-9862-5fe0f1479469)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:dbd270d5-355d-4ad0-b3ab-1224b31e6445](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:dbd270d5-355d-4ad0-b3ab-1224b31e6445)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:f0cb34b1-3d90-4b40-8f75-d02481114b77](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:f0cb34b1-3d90-4b40-8f75-d02481114b77)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:eff32662-fe9c-4790-8453-6854fae46f1c](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:eff32662-fe9c-4790-8453-6854fae46f1c)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:6b541f51-1e2c-4b94-82e4-ce3f84291b12](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:6b541f51-1e2c-4b94-82e4-ce3f84291b12)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:4706b999-549d-43c8-ad67-0993854a77c8](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:4706b999-549d-43c8-ad67-0993854a77c8)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:38b7c870-ac61-4f83-b318-a50974141de6](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:38b7c870-ac61-4f83-b318-a50974141de6)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:93e1a2cf-59fa-4894-a4ef-553ee0cdc9b7](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:93e1a2cf-59fa-4894-a4ef-553ee0cdc9b7)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:46f10f36-8e34-42be-9d0d-9222545375bd](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:46f10f36-8e34-42be-9d0d-9222545375bd)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:e3270bdb-eb80-4786-a31b-8d8e15f8e9da](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:e3270bdb-eb80-4786-a31b-8d8e15f8e9da)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:75c36489-3505-4720-954c-85978149052c](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:75c36489-3505-4720-954c-85978149052c)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:2513eb2e-4019-4d21-a6cb-01e6195a4391](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:2513eb2e-4019-4d21-a6cb-01e6195a4391)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:8de7dd6b-2b3b-475d-942f-37948e44381c](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:8de7dd6b-2b3b-475d-942f-37948e44381c)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:c081d3a4-d6c2-425e-ad7a-d83584aeecff](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:c081d3a4-d6c2-425e-ad7a-d83584aeecff)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:686aced4-03f6-4f7d-838b-e5813fbbb6fc](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:686aced4-03f6-4f7d-838b-e5813fbbb6fc)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:a5af6327-3557-4527-a4b3-eecd23c9601b](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:a5af6327-3557-4527-a4b3-eecd23c9601b)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:9167c4c4-c9d7-4dd1-bab8-bdaa1e97232b](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:9167c4c4-c9d7-4dd1-bab8-bdaa1e97232b)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:822acf8c-4b70-4608-8289-47de3f55cf40](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:822acf8c-4b70-4608-8289-47de3f55cf40)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:932d989e-9129-40d0-8d7f-3acc042312cb](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:932d989e-9129-40d0-8d7f-3acc042312cb)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:9a9f16d8-2b81-4ef8-ba4e-36228f33f36c](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:9a9f16d8-2b81-4ef8-ba4e-36228f33f36c)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:51678d2f-c987-4b7c-840c-785a8aecce55](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:51678d2f-c987-4b7c-840c-785a8aecce55)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:3b9bf611-738e-4d28-9fba-5d32dc6c6bb1](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:3b9bf611-738e-4d28-9fba-5d32dc6c6bb1)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:1567676a-d3c5-4ca9-b464-abed2f0742a5](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:1567676a-d3c5-4ca9-b464-abed2f0742a5)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:1a745f6d-bcdb-40b1-8532-b0fd638e2ec7](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:1a745f6d-bcdb-40b1-8532-b0fd638e2ec7)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:ab616fcd-0b62-4aed-9138-2c7aad0b2d42](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:ab616fcd-0b62-4aed-9138-2c7aad0b2d42)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:1c3655bc-df51-4d65-9508-7d075ffa3d33](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:1c3655bc-df51-4d65-9508-7d075ffa3d33)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:ab734040-739c-4ead-9a4b-1b3dd7c92e7c](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:ab734040-739c-4ead-9a4b-1b3dd7c92e7c)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:47811485-15a5-4a32-83d2-1e045d66418d](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:47811485-15a5-4a32-83d2-1e045d66418d)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:65046acc-e7a6-42a8-b9b4-037f6864ea78](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:65046acc-e7a6-42a8-b9b4-037f6864ea78)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:9bbbb640-f6c2-4ffa-9ffa-2ccbfb4960cd](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:9bbbb640-f6c2-4ffa-9ffa-2ccbfb4960cd)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:ffa828ba-1f6a-43ac-b6fc-4bb0f3c91b6b](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:ffa828ba-1f6a-43ac-b6fc-4bb0f3c91b6b)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:44dd81dc-7b13-45bf-9939-3148b5b3cea7](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:44dd81dc-7b13-45bf-9939-3148b5b3cea7)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:90cd0e3b-5c96-4490-96fc-cf242fcb517c](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:90cd0e3b-5c96-4490-96fc-cf242fcb517c)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:d5c8d11b-b638-4240-a554-357183250d92](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:d5c8d11b-b638-4240-a554-357183250d92)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:d0d52d66-ff36-49cd-bb59-017771e03395](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:d0d52d66-ff36-49cd-bb59-017771e03395)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:33b43e7a-cff2-4e69-b879-9ed9e0904838](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:33b43e7a-cff2-4e69-b879-9ed9e0904838)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:667f766c-9f7e-4699-af59-edc6537ba4a7](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:667f766c-9f7e-4699-af59-edc6537ba4a7)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:56081401-5159-432c-b59b-1da51815fba1](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:56081401-5159-432c-b59b-1da51815fba1)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:f9583989-3f7f-4a63-a7d5-e1e29de5e259](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:f9583989-3f7f-4a63-a7d5-e1e29de5e259)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:d9ba0c19-68d2-4bdc-ae3e-e578e579d84b](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:d9ba0c19-68d2-4bdc-ae3e-e578e579d84b)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:9b00eecc-c2f6-4544-8e31-748d61867c06](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:9b00eecc-c2f6-4544-8e31-748d61867c06)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:3c5cf5e3-3d86-4469-a9ac-23f2d28dbda6](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:3c5cf5e3-3d86-4469-a9ac-23f2d28dbda6)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:304f90fc-42e7-4fce-a8c3-60d031548c81](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:304f90fc-42e7-4fce-a8c3-60d031548c81)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:90f607ca-4c54-401b-9976-36f85d1308bb](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:90f607ca-4c54-401b-9976-36f85d1308bb)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:84126d35-3052-4250-9510-be0f5bc976cc](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:84126d35-3052-4250-9510-be0f5bc976cc)

- **Type:** productOrder
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:b443cf29-005d-483e-ae3a-76a4b5af1319](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:b443cf29-005d-483e-ae3a-76a4b5af1319)

- **Type:** productOrder
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:44e0c7b6-0902-48a3-9401-c2400b12f3e9](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:44e0c7b6-0902-48a3-9401-c2400b12f3e9)

- **Type:** productOrder
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:92e87662-5f08-4bb0-b0ae-2e55101ca33e](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:92e87662-5f08-4bb0-b0ae-2e55101ca33e)

- **Type:** productOrder
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:ac861a2b-ab81-4a15-b6e9-13718d7eea46](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:ac861a2b-ab81-4a15-b6e9-13718d7eea46)

- **Type:** productOrder
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-order:607ac88a-15ff-41dc-b6df-b379af2caa1e](https://tmf.dome-marketplace-sbx.org/tmf-api/productOrderingManagement/v4/productOrder/urn:ngsi-ld:product-order:607ac88a-15ff-41dc-b6df-b379af2caa1e)

- **Type:** productOrder
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:50 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productOrder (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### productSpecification Objects

#### Object: [urn:ngsi-ld:product-specification:bf72e349-03f0-4e88-965a-73815d8881b4](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:bf72e349-03f0-4e88-965a-73815d8881b4)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:55158c3d-ef8f-4f1c-b9d0-82dd3138b2ae](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:55158c3d-ef8f-4f1c-b9d0-82dd3138b2ae)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:5e2ced54-45f1-4687-b9f9-ee13cb318a66](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:5e2ced54-45f1-4687-b9f9-ee13cb318a66)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:ba4123f5-77f2-4b80-8c8d-13c01d3a6e72](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:ba4123f5-77f2-4b80-8c8d-13c01d3a6e72)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:534697ce-c774-4cc2-a8f4-d4f2ae6cf4f9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:534697ce-c774-4cc2-a8f4-d4f2ae6cf4f9)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:bfe7418d-2614-4e6a-920c-6d6711171f10](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:bfe7418d-2614-4e6a-920c-6d6711171f10)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:351bbc6e-515f-4159-9082-e60563c927da](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:351bbc6e-515f-4159-9082-e60563c927da)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:1cb811e6-4661-41ff-935c-26176e209dab](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:1cb811e6-4661-41ff-935c-26176e209dab)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:32096043-6ce0-49c0-acb6-4ffde182b254](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:32096043-6ce0-49c0-acb6-4ffde182b254)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:36f45313-8f8d-49c4-bbf2-bd2816934e6d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:36f45313-8f8d-49c4-bbf2-bd2816934e6d)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:1226966e-795f-4508-a876-6c67c5cb1059](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:1226966e-795f-4508-a876-6c67c5cb1059)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:8e867c80-2a58-49c7-9502-30f8373802ad](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:8e867c80-2a58-49c7-9502-30f8373802ad)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:9f3eebce-ddfd-40a4-9227-a62f98f94344](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:9f3eebce-ddfd-40a4-9227-a62f98f94344)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:839e37f8-5f9d-48fc-b2c9-3e5a32d90424](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:839e37f8-5f9d-48fc-b2c9-3e5a32d90424)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC

#### Object: [urn:ngsi-ld:product-specification:2adb577d-ec29-4406-b2d5-86b295c2c434](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:2adb577d-ec29-4406-b2d5-86b295c2c434)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC

#### Object: [urn:ngsi-ld:product-specification:64c19187-4f24-4dcb-bfa2-a06afd3b5b11](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:64c19187-4f24-4dcb-bfa2-a06afd3b5b11)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:6a8476a3-88e5-49de-873b-4ad36ebf6db5](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:6a8476a3-88e5-49de-873b-4ad36ebf6db5)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:cb3d1a1a-802a-4463-bc2d-056014051201](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:cb3d1a1a-802a-4463-bc2d-056014051201)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:9f141090-01ef-4988-a639-97d84f2d76ba](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:9f141090-01ef-4988-a639-97d84f2d76ba)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:1fd76f44-79c6-46d6-9fb1-11899181e905](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:1fd76f44-79c6-46d6-9fb1-11899181e905)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:e4794956-d42e-46c9-a2ce-3df53e2df26d](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:e4794956-d42e-46c9-a2ce-3df53e2df26d)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:411816fd-3f8b-4e6f-8c35-02e8cada5ce9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:411816fd-3f8b-4e6f-8c35-02e8cada5ce9)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:3c2ea42e-77de-4012-8d12-2e760facca23](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:3c2ea42e-77de-4012-8d12-2e760facca23)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:a45a592d-480d-429d-8ad8-f81b1bf528bb](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:a45a592d-480d-429d-8ad8-f81b1bf528bb)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:ace61c97-0f51-4601-8359-59b3987ff3f7](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:ace61c97-0f51-4601-8359-59b3987ff3f7)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:ccaec925-9fad-40c0-8015-5b9087f92aff](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:ccaec925-9fad-40c0-8015-5b9087f92aff)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:2532e67f-0a84-4aed-b31f-7654984daac9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:2532e67f-0a84-4aed-b31f-7654984daac9)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:10ebf2c1-fe79-4191-81a3-b58207307c5a](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:10ebf2c1-fe79-4191-81a3-b58207307c5a)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:7b61b736-d15c-411c-90fa-649508d2a9f5](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:7b61b736-d15c-411c-90fa-649508d2a9f5)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:021517fe-650f-4834-92f1-4bf29487c5e3](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:021517fe-650f-4834-92f1-4bf29487c5e3)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:90962671-9c9d-4328-b78b-b551b74fdc92](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:90962671-9c9d-4328-b78b-b551b74fdc92)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:e84e6c6c-7791-40f1-8904-b14134e3cbcb](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:e84e6c6c-7791-40f1-8904-b14134e3cbcb)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:e9ac6275-bb21-47d7-89bd-187f71f55e3c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:e9ac6275-bb21-47d7-89bd-187f71f55e3c)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:95332c87-ccb7-4ab2-bce9-78b21295e06f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:95332c87-ccb7-4ab2-bce9-78b21295e06f)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:d881ea40-8069-4973-9bea-b99f4d0a2a07](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:d881ea40-8069-4973-9bea-b99f4d0a2a07)

- **Type:** productSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:8561a66d-9875-4bf9-8c92-6819bc6bb3d6](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:8561a66d-9875-4bf9-8c92-6819bc6bb3d6)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:cb0f8c88-23e2-409d-949d-4c6e4b9c45f1](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:cb0f8c88-23e2-409d-949d-4c6e4b9c45f1)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:1ab721ea-f7c1-4547-8635-c14fe8d0d02f](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:1ab721ea-f7c1-4547-8635-c14fe8d0d02f)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:5bc93ac0-0a8a-4bb7-9117-1e22b5f5a887](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:5bc93ac0-0a8a-4bb7-9117-1e22b5f5a887)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:ba185539-9f21-489c-99fb-2e59d155d3a9](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:ba185539-9f21-489c-99fb-2e59d155d3a9)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:d3096832-57f3-4bb9-b2f6-139f0300aaac](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:d3096832-57f3-4bb9-b2f6-139f0300aaac)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:3b838aa6-ec3f-4380-8e30-5615ddd5c693](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:3b838aa6-ec3f-4380-8e30-5615ddd5c693)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:e8171d50-4d38-4c10-b517-933221bf3eba](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:e8171d50-4d38-4c10-b517-933221bf3eba)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:7c9f00b2-980c-48fb-b096-4a925888fbdf](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:7c9f00b2-980c-48fb-b096-4a925888fbdf)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:d7004acf-7839-40ff-bdef-e9010df264fe](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:d7004acf-7839-40ff-bdef-e9010df264fe)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:b5200e80-9016-400a-a020-fc2c467228a2](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:b5200e80-9016-400a-a020-fc2c467228a2)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:bc96b48c-94d1-47b0-be7e-086f5578c51c](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:bc96b48c-94d1-47b0-be7e-086f5578c51c)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:6ab0392b-9c3f-4571-9256-4ea257b43812](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:6ab0392b-9c3f-4571-9256-4ea257b43812)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)

#### Object: [urn:ngsi-ld:product-specification:3c0438b3-9800-4814-9838-bdfcbf61b7f5](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:3c0438b3-9800-4814-9838-bdfcbf61b7f5)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:product-specification:bb50d49b-96e7-492c-aabf-1f48012c4582](https://tmf.dome-marketplace-sbx.org/tmf-api/productCatalogManagement/v4/productSpecification/urn:ngsi-ld:product-specification:bb50d49b-96e7-492c-aabf-1f48012c4582)

- **Type:** productSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:30 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to productSpecification (Code: MISSING_RECOMMENDED_FIELD)

### quote Objects

#### Object: [urn:ngsi-ld:quote:91333dfb-bf4c-442c-8072-26ea2940b7ec](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:91333dfb-bf4c-442c-8072-26ea2940b7ec)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:745edf57-9c8a-488d-8059-a2616bd743b7](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:745edf57-9c8a-488d-8059-a2616bd743b7)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:294c4f48-e350-453d-952c-9132ec06bd0a](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:294c4f48-e350-453d-952c-9132ec06bd0a)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:410e6d9c-da52-4894-bef5-5acb546a4bc2](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:410e6d9c-da52-4894-bef5-5acb546a4bc2)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:014f8da2-2a39-4c99-a5d2-e22ce06de8bf](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:014f8da2-2a39-4c99-a5d2-e22ce06de8bf)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:b1d1e81c-d152-4a4a-8e97-8f92dd502d9b](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:b1d1e81c-d152-4a4a-8e97-8f92dd502d9b)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:ebc5fd0b-ec81-40ca-acf8-5b39fe79c01c](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:ebc5fd0b-ec81-40ca-acf8-5b39fe79c01c)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:ae0219c0-a236-4b6d-9cda-892c7ddda824](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:ae0219c0-a236-4b6d-9cda-892c7ddda824)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:b8401b74-d7c7-4797-83d5-05e66d9a4419](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:b8401b74-d7c7-4797-83d5-05e66d9a4419)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:0b44e55f-6690-4ac6-925a-bd34d534a6ca](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:0b44e55f-6690-4ac6-925a-bd34d534a6ca)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:6d6d5811-6b33-4e99-a1dd-15d439e21f76](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:6d6d5811-6b33-4e99-a1dd-15d439e21f76)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:13ef89b4-c186-4ea3-8371-12b95aa63910](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:13ef89b4-c186-4ea3-8371-12b95aa63910)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:c5a21f3c-0d87-493e-a92f-c3317c62f64d](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:c5a21f3c-0d87-493e-a92f-c3317c62f64d)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:569aba0e-ad22-4801-9f25-12f60b19b9d5](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:569aba0e-ad22-4801-9f25-12f60b19b9d5)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:fadc6cd0-1f8c-40d3-8977-dc08ea9321f9](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:fadc6cd0-1f8c-40d3-8977-dc08ea9321f9)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Buyer' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:5045c7b7-034c-45ce-9ddf-51a9ddc00893](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:5045c7b7-034c-45ce-9ddf-51a9ddc00893)

- **Type:** quote
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:2dcd113a-4cbd-4465-b9b7-99be654773c6](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:2dcd113a-4cbd-4465-b9b7-99be654773c6)

- **Type:** quote
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:98575f6c-ddfd-4a01-9072-1b7e295bc754](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:98575f6c-ddfd-4a01-9072-1b7e295bc754)

- **Type:** quote
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:quote:c2075d25-a08d-4cec-b72a-93c3d29b26b6](https://tmf.dome-marketplace-sbx.org/tmf-api/quoteManagement/v4/quote/urn:ngsi-ld:quote:c2075d25-a08d-4cec-b72a-93c3d29b26b6)

- **Type:** quote
- **Valid:** true
- **Timestamp:** 2025-11-28 10:40:55 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to quote (Code: MISSING_RECOMMENDED_FIELD)
  - name: Recommended field 'name' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### resource Objects

#### Object: [urn:ngsi-ld:resource:8e58861a-5f65-4873-b0d4-d74296160870](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:8e58861a-5f65-4873-b0d4-d74296160870)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:2abad639-11bc-4dff-a554-d5c4a8a175b5](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:2abad639-11bc-4dff-a554-d5c4a8a175b5)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:1c06d20b-302f-43d2-8928-3df67e96eb7f](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:1c06d20b-302f-43d2-8928-3df67e96eb7f)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:e21b848b-74ca-4b93-9127-e1f043da1660](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:e21b848b-74ca-4b93-9127-e1f043da1660)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:94e4c43b-9a49-4880-9144-53db38b69083](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:94e4c43b-9a49-4880-9144-53db38b69083)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:c56a4d6c-43a0-45b6-b61e-b9ff13aed81f](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:c56a4d6c-43a0-45b6-b61e-b9ff13aed81f)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:bb198be7-01b5-4c40-837b-b1b97b2ab5bb](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:bb198be7-01b5-4c40-837b-b1b97b2ab5bb)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:80fe9ef6-c5df-4403-89f9-fcea27e8157b](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:80fe9ef6-c5df-4403-89f9-fcea27e8157b)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:b706d1c7-0ec5-4e6f-a11d-0ca1e3f5ceea](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:b706d1c7-0ec5-4e6f-a11d-0ca1e3f5ceea)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:0a3bdcff-f809-45de-8abd-72e197478580](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:0a3bdcff-f809-45de-8abd-72e197478580)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:7465525d-582d-4b7b-928a-c389de3c5808](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:7465525d-582d-4b7b-928a-c389de3c5808)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:a7bcfbf8-7692-4ea7-ae20-03f01a2568aa](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:a7bcfbf8-7692-4ea7-ae20-03f01a2568aa)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:0541b853-2bdf-4774-9ecd-29bdab473475](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:0541b853-2bdf-4774-9ecd-29bdab473475)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:fe949971-f5eb-4f6d-bd83-37208e808cad](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:fe949971-f5eb-4f6d-bd83-37208e808cad)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:1d6a9d07-b4b1-48ec-8a72-efe9fbc476ff](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:1d6a9d07-b4b1-48ec-8a72-efe9fbc476ff)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:876f576f-c686-48f9-a5ce-d24bf2ff6343](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:876f576f-c686-48f9-a5ce-d24bf2ff6343)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:8e4d2ad7-fc63-4d4a-9b2e-5a3514c3a56a](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:8e4d2ad7-fc63-4d4a-9b2e-5a3514c3a56a)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:c714add4-d818-4a23-ae1d-f770cf56ccb3](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:c714add4-d818-4a23-ae1d-f770cf56ccb3)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:d41ca912-91ae-4bab-be0f-e2ce3419d33f](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:d41ca912-91ae-4bab-be0f-e2ce3419d33f)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:a6f30dbd-8a74-4427-b5d5-abe19dc61d79](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:a6f30dbd-8a74-4427-b5d5-abe19dc61d79)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:a700af5a-f59e-4ba0-b801-4ba09c3d2115](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:a700af5a-f59e-4ba0-b801-4ba09c3d2115)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:1cb497c3-6212-4fee-a042-11af0e15dda7](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:1cb497c3-6212-4fee-a042-11af0e15dda7)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:47494568-4ca8-4fbd-9a02-484f368b9558](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:47494568-4ca8-4fbd-9a02-484f368b9558)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:27d89a1a-fbac-4c1d-b4c6-e585b49f2d2f](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:27d89a1a-fbac-4c1d-b4c6-e585b49f2d2f)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:3a6ab23e-a3c1-45ab-91cc-a4f4dedeac24](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:3a6ab23e-a3c1-45ab-91cc-a4f4dedeac24)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:ce133ff0-0eb5-46db-a837-63c0af515aba](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:ce133ff0-0eb5-46db-a837-63c0af515aba)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:9accc80d-1490-4994-a1fa-8624bcf968c8](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:9accc80d-1490-4994-a1fa-8624bcf968c8)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource:8d70ccb9-5f54-42b4-aeb2-14a15348ba51](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceInventoryManagement/v4/resource/urn:ngsi-ld:resource:8d70ccb9-5f54-42b4-aeb2-14a15348ba51)

- **Type:** resource
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:15 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resource (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### resourceSpecification Objects

#### Object: [urn:ngsi-ld:resource-specification:9bd04c66-97a5-489a-ae93-7dddb4cd341b](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:9bd04c66-97a5-489a-ae93-7dddb4cd341b)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:f0153609-77d6-4464-9352-679f8d0e015f](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:f0153609-77d6-4464-9352-679f8d0e015f)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:e84e77c9-55e1-4c2f-953a-09dd52003f92](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:e84e77c9-55e1-4c2f-953a-09dd52003f92)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:59cf3608-2879-4f38-a8f7-5baf61653c92](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:59cf3608-2879-4f38-a8f7-5baf61653c92)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:46e91850-687d-4454-a53a-b2211bc8f4b8](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:46e91850-687d-4454-a53a-b2211bc8f4b8)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:996d8528-7988-4698-a0c7-613e7e646de5](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:996d8528-7988-4698-a0c7-613e7e646de5)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:ff1e8458-12e5-4c2f-9b10-27f0111c76eb](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:ff1e8458-12e5-4c2f-9b10-27f0111c76eb)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:31c96384-4fca-49ac-b67b-e37e9ba17ad5](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:31c96384-4fca-49ac-b67b-e37e9ba17ad5)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:cac71f92-58a7-4eeb-b7ef-a65f017de86d](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:cac71f92-58a7-4eeb-b7ef-a65f017de86d)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:d3d44ad6-691d-4456-8e87-014cb9cceceb](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:d3d44ad6-691d-4456-8e87-014cb9cceceb)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:5338b9dd-5faf-4085-b63d-df2885e87bd4](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:5338b9dd-5faf-4085-b63d-df2885e87bd4)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:cea066f1-a03b-401e-81ca-17c4e34b57da](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:cea066f1-a03b-401e-81ca-17c4e34b57da)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:98e53881-0968-455f-8ca2-ca22bab21cc5](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:98e53881-0968-455f-8ca2-ca22bab21cc5)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:167a0638-cdd8-4535-abe8-07d903e673e9](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:167a0638-cdd8-4535-abe8-07d903e673e9)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:2411f1cb-f15e-4c7c-a391-55d1377bf602](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:2411f1cb-f15e-4c7c-a391-55d1377bf602)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:0d389ed9-44c7-4d11-9afd-4ccf467943bd](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:0d389ed9-44c7-4d11-9afd-4ccf467943bd)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:resource-specification:928e640b-d768-49dd-ba5f-06594786aa51](https://tmf.dome-marketplace-sbx.org/tmf-api/resourceCatalog/v4/resourceSpecification/urn:ngsi-ld:resource-specification:928e640b-d768-49dd-ba5f-06594786aa51)

- **Type:** resourceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:52 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to resourceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

### service Objects

#### Object: [urn:ngsi-ld:service:7c4c95cf-0b7d-40d0-890a-4dc72833bb93](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:7c4c95cf-0b7d-40d0-890a-4dc72833bb93)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:8da6974f-43e3-4cb8-9dd0-16c7235845be](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:8da6974f-43e3-4cb8-9dd0-16c7235845be)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:46da6440-ab04-40a5-829d-1e0733e20dce](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:46da6440-ab04-40a5-829d-1e0733e20dce)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:3d8a197f-d247-4a51-a93b-ebfe97589258](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:3d8a197f-d247-4a51-a93b-ebfe97589258)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:f0477ba9-7d87-4ed9-a7e1-2835b31196dc](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:f0477ba9-7d87-4ed9-a7e1-2835b31196dc)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:1f25b49d-b116-4348-837c-85b6dffaa323](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:1f25b49d-b116-4348-837c-85b6dffaa323)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:4913d3de-fa4f-4e69-9e09-d8cb7bf1ca03](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:4913d3de-fa4f-4e69-9e09-d8cb7bf1ca03)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:c16510b6-291f-4b8a-a1a7-5d4c614568e2](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:c16510b6-291f-4b8a-a1a7-5d4c614568e2)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:e5b86a59-e684-4063-8db2-92e08a003f16](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:e5b86a59-e684-4063-8db2-92e08a003f16)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:11ada031-6eed-4385-814b-0d0e18a2fab0](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:11ada031-6eed-4385-814b-0d0e18a2fab0)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:5410fce1-2c30-4e04-8849-8b171ff80250](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:5410fce1-2c30-4e04-8849-8b171ff80250)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:1659addd-fd42-41fc-92ad-0216619b0d38](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:1659addd-fd42-41fc-92ad-0216619b0d38)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:d4a44923-72b3-4181-92b6-cdf8cf77b097](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:d4a44923-72b3-4181-92b6-cdf8cf77b097)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:c7af8f17-aaa6-4016-b3ec-37b05013bbeb](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:c7af8f17-aaa6-4016-b3ec-37b05013bbeb)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:4c633ebc-f5e4-470b-8232-2690d1299f6e](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:4c633ebc-f5e4-470b-8232-2690d1299f6e)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:89d65206-4e9e-44d2-b599-5f421bd27035](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:89d65206-4e9e-44d2-b599-5f421bd27035)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:b0fe3d04-5383-4eb4-a2a7-21567bd04a8e](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:b0fe3d04-5383-4eb4-a2a7-21567bd04a8e)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:4624e43f-9d3f-432f-9276-a24876a4343d](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:4624e43f-9d3f-432f-9276-a24876a4343d)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:6d0509ff-d999-4c18-b789-695f585a26d9](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:6d0509ff-d999-4c18-b789-695f585a26d9)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:a8b86ff8-c985-4c14-a511-d28014b5f619](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:a8b86ff8-c985-4c14-a511-d28014b5f619)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:694594f9-c1eb-404b-bc88-6eb730e3721e](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:694594f9-c1eb-404b-bc88-6eb730e3721e)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:a362767d-c4c1-421c-88ee-bc30d2789fa8](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:a362767d-c4c1-421c-88ee-bc30d2789fa8)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:9d2e3dad-680a-4eed-8522-1872a7d6cef8](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:9d2e3dad-680a-4eed-8522-1872a7d6cef8)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:cdd2bfc2-4358-44f4-af9f-22f1557761c0](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:cdd2bfc2-4358-44f4-af9f-22f1557761c0)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:68c7911b-7d29-447f-80d3-b8a7d893d671](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:68c7911b-7d29-447f-80d3-b8a7d893d671)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:e29b32ad-0cc5-4c0b-b82b-d064777fd69d](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:e29b32ad-0cc5-4c0b-b82b-d064777fd69d)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:421ceae5-3635-4797-a28a-92d2f337aab6](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:421ceae5-3635-4797-a28a-92d2f337aab6)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:efe10698-a942-415d-af3e-bce1fdf02562](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:efe10698-a942-415d-af3e-bce1fdf02562)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:f843d6ae-b369-4913-a85c-6d996de7d5cd](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:f843d6ae-b369-4913-a85c-6d996de7d5cd)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:9e80e0cb-2388-433a-81e9-5e62e5086293](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:9e80e0cb-2388-433a-81e9-5e62e5086293)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:30812ea8-8da9-4563-be81-515e5d732d1c](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:30812ea8-8da9-4563-be81-515e5d732d1c)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:43b03329-9231-45af-8c34-9595f2db5749](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:43b03329-9231-45af-8c34-9595f2db5749)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:6477e357-1175-4892-89ef-d59ca4c8d129](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:6477e357-1175-4892-89ef-d59ca4c8d129)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:0a5a2a4f-622b-4800-b85a-de07cb45f1da](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:0a5a2a4f-622b-4800-b85a-de07cb45f1da)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:00a9d53d-c2b8-413c-a5df-dad0753fccee](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:00a9d53d-c2b8-413c-a5df-dad0753fccee)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:66b48b0e-9f8e-48c1-b26d-4363e423ee70](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:66b48b0e-9f8e-48c1-b26d-4363e423ee70)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:0598499d-ae4e-479e-8a37-cb20390bf47f](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:0598499d-ae4e-479e-8a37-cb20390bf47f)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:76b41627-731b-40a6-917c-98143156aeec](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:76b41627-731b-40a6-917c-98143156aeec)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:e1848935-7aaa-4894-a14c-f0ae5497763f](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:e1848935-7aaa-4894-a14c-f0ae5497763f)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:3bb1adf7-f7df-40b8-a961-48fd8920628b](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:3bb1adf7-f7df-40b8-a961-48fd8920628b)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:e69da896-6874-4431-a6f0-0f011cc7a3d3](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:e69da896-6874-4431-a6f0-0f011cc7a3d3)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:c90151d4-d176-466e-b2e8-d9248f65ecbe](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:c90151d4-d176-466e-b2e8-d9248f65ecbe)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:d1e316ed-6f50-42f1-8f94-7cd22bdc3ae4](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:d1e316ed-6f50-42f1-8f94-7cd22bdc3ae4)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:7378ccbd-4cf1-4536-ac90-a8b651eee300](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:7378ccbd-4cf1-4536-ac90-a8b651eee300)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:798ad965-6955-4f10-9113-3ef76efa9ace](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:798ad965-6955-4f10-9113-3ef76efa9ace)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:d4d981b3-925b-42af-b060-f7fbaee178d0](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:d4d981b3-925b-42af-b060-f7fbaee178d0)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:73fad827-19d7-4aeb-afad-bb07e6fc1d3e](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:73fad827-19d7-4aeb-afad-bb07e6fc1d3e)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:b2db24c7-c520-412b-9881-0b5b130195e0](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:b2db24c7-c520-412b-9881-0b5b130195e0)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:c6b30737-1bd9-41af-9b35-70d1d2fdead0](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:c6b30737-1bd9-41af-9b35-70d1d2fdead0)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:25bd5bdf-c46c-4af9-92fe-bbf8b8570295](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:25bd5bdf-c46c-4af9-92fe-bbf8b8570295)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:7dbeef12-eb5b-409e-9acf-d9800198974f](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:7dbeef12-eb5b-409e-9acf-d9800198974f)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:f4b83327-b60d-45be-9853-ae347dd7965f](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:f4b83327-b60d-45be-9853-ae347dd7965f)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:d09e3723-7471-43ce-99be-92473b1b8e23](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:d09e3723-7471-43ce-99be-92473b1b8e23)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:4e6b7e95-f622-4cd3-965b-87b67c18fa7b](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:4e6b7e95-f622-4cd3-965b-87b67c18fa7b)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:d8be7dcd-6585-42c5-8104-eadbde259c02](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:d8be7dcd-6585-42c5-8104-eadbde259c02)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:673a1a4b-8fa6-4b6e-8b75-eb960103aafe](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:673a1a4b-8fa6-4b6e-8b75-eb960103aafe)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:47a0eeb6-92d8-4ddf-a060-f6a4c9ed5fc1](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:47a0eeb6-92d8-4ddf-a060-f6a4c9ed5fc1)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:718dc9cb-1b02-411f-8fa8-63a7961bb563](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:718dc9cb-1b02-411f-8fa8-63a7961bb563)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:d257497c-f703-484d-8dec-82e01321072d](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:d257497c-f703-484d-8dec-82e01321072d)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:69254f62-2af0-4931-8d5a-f949708b3974](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:69254f62-2af0-4931-8d5a-f949708b3974)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:ed6eed98-3f29-4f18-a93f-6db2ca4735c8](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:ed6eed98-3f29-4f18-a93f-6db2ca4735c8)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:f67e1b72-72ad-4a84-8603-322aaf2fb55a](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:f67e1b72-72ad-4a84-8603-322aaf2fb55a)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:db2d6070-3c20-4c66-85f1-a4ce41377823](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:db2d6070-3c20-4c66-85f1-a4ce41377823)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:2c5f61f4-5faf-45eb-a9c1-234d8615c9a5](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:2c5f61f4-5faf-45eb-a9c1-234d8615c9a5)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:f62c0a94-3314-4f93-a1a5-297d55e20b5f](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:f62c0a94-3314-4f93-a1a5-297d55e20b5f)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:b90a8a01-2886-4113-996c-ba398b210c39](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:b90a8a01-2886-4113-996c-ba398b210c39)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:e98f8a5e-7574-4e39-9610-ae150027557d](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:e98f8a5e-7574-4e39-9610-ae150027557d)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:abe6375c-7732-4470-b471-5da39ff214ed](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:abe6375c-7732-4470-b471-5da39ff214ed)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:e1a9680f-f415-49c4-aad4-ca00d87cce83](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:e1a9680f-f415-49c4-aad4-ca00d87cce83)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:f410a722-b15f-4553-8a56-fedb8b306921](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:f410a722-b15f-4553-8a56-fedb8b306921)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:0139f0a7-6696-4de9-b257-e6f13cd9137a](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:0139f0a7-6696-4de9-b257-e6f13cd9137a)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:e8f0dd0b-9c3d-445e-8b96-c2fd16ab12e4](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:e8f0dd0b-9c3d-445e-8b96-c2fd16ab12e4)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:f7a59980-663f-4607-9b8a-faa91e1300ed](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:f7a59980-663f-4607-9b8a-faa91e1300ed)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:3d3648e6-635c-4371-9a6b-81e16643e53b](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:3d3648e6-635c-4371-9a6b-81e16643e53b)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:007ea371-828c-4e46-9941-d9486fa44b7a](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:007ea371-828c-4e46-9941-d9486fa44b7a)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:86d17dbe-2075-42d5-bb30-41f4bd555d98](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:86d17dbe-2075-42d5-bb30-41f4bd555d98)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:169aa5c7-e738-468f-96ce-2b15569890d9](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:169aa5c7-e738-468f-96ce-2b15569890d9)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:f99033ce-1b9a-4e75-bf3c-c2a4c93dc7f5](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:f99033ce-1b9a-4e75-bf3c-c2a4c93dc7f5)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:ba0ce9fc-ade9-47ed-8a9b-f70760339707](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:ba0ce9fc-ade9-47ed-8a9b-f70760339707)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:6af744e0-c4fa-4153-85a5-cb60a6bd6551](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:6af744e0-c4fa-4153-85a5-cb60a6bd6551)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:4c83d495-e0da-4aa7-94c3-8c4d184f5c56](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:4c83d495-e0da-4aa7-94c3-8c4d184f5c56)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service:80609802-f167-4fa9-b8f0-657f887a2dec](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceInventory/v4/service/urn:ngsi-ld:service:80609802-f167-4fa9-b8f0-657f887a2dec)

- **Type:** service
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to service (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### serviceSpecification Objects

#### Object: [urn:ngsi-ld:service-specification:ab1f9684-e04f-4692-bb2d-20827f1bb759](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:ab1f9684-e04f-4692-bb2d-20827f1bb759)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:8f5f2d0c-9af4-47ad-a932-387455fc11df](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:8f5f2d0c-9af4-47ad-a932-387455fc11df)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:69a374ff-97c5-417b-8b31-2bd36798006b](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:69a374ff-97c5-417b-8b31-2bd36798006b)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:80b2ba93-5d5d-4753-a29f-b80114a01333](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:80b2ba93-5d5d-4753-a29f-b80114a01333)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:5ff52024-ea17-4f17-aa39-0499f57fc7d1](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:5ff52024-ea17-4f17-aa39-0499f57fc7d1)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:8a8741bb-c559-46a8-9ae8-d2f00c7504ca](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:8a8741bb-c559-46a8-9ae8-d2f00c7504ca)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:6ea578e6-ff2e-418b-993f-5169d271d78e](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:6ea578e6-ff2e-418b-993f-5169d271d78e)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:8ac3638e-1800-4530-b0a4-61bc73ae869a](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:8ac3638e-1800-4530-b0a4-61bc73ae869a)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:79ac0a54-ab0e-4018-a892-be1e54e8b2be](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:79ac0a54-ab0e-4018-a892-be1e54e8b2be)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:b8e690b3-3a24-4273-b569-7270128e1bc2](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:b8e690b3-3a24-4273-b569-7270128e1bc2)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:1e0f2ebf-e89a-4996-8ca8-e24eebbe3a7a](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:1e0f2ebf-e89a-4996-8ca8-e24eebbe3a7a)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:18a977ba-160a-4aef-a55f-ecff6a86e9a2](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:18a977ba-160a-4aef-a55f-ecff6a86e9a2)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:d612a81a-b154-4ca4-8ed0-28c13233e268](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:d612a81a-b154-4ca4-8ed0-28c13233e268)

- **Type:** serviceSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:89d6bddb-7805-4042-a60a-030ef09ed816](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:89d6bddb-7805-4042-a60a-030ef09ed816)

- **Type:** serviceSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:f70f5f90-14d2-4442-a459-dae184f233e4](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:f70f5f90-14d2-4442-a459-dae184f233e4)

- **Type:** serviceSpecification
- **Valid:** true
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:7cda71b5-24b0-4c71-b650-749ca7615531](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:7cda71b5-24b0-4c71-b650-749ca7615531)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:service-specification:ffa1b9e8-cf77-49ea-8554-1ac8c3ce10af](https://tmf.dome-marketplace-sbx.org/tmf-api/serviceCatalogManagement/v4/serviceSpecification/urn:ngsi-ld:service-specification:ffa1b9e8-cf77-49ea-8554-1ac8c3ce10af)

- **Type:** serviceSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:41:11 UTC
- **Errors:**
  - relatedParty: Missing or invalid 'name' field in 'relatedParty' object for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Seller' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to serviceSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)

### settlementAccount Objects

#### Object: [urn:ngsi-ld:settlement-account:4b322ca1-3fdc-4806-a54d-39b972c2e7fb](https://tmf.dome-marketplace-sbx.org/tmf-api/accountManagement/v4/settlementAccount/urn:ngsi-ld:settlement-account:4b322ca1-3fdc-4806-a54d-39b972c2e7fb)

- **Type:** settlementAccount
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:16 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' object (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to settlementAccount (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

### usageSpecification Objects

#### Object: [urn:ngsi-ld:usageSpecification:21333496-4652-4bbf-be85-a897278d4ee9](https://tmf.dome-marketplace-sbx.org/tmf-api/usageManagement/v4/usageSpecification/urn:ngsi-ld:usageSpecification:21333496-4652-4bbf-be85-a897278d4ee9)

- **Type:** usageSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:16 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to usageSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:usageSpecification:24abecd5-bf1f-42e0-a34f-1657f39dffe1](https://tmf.dome-marketplace-sbx.org/tmf-api/usageManagement/v4/usageSpecification/urn:ngsi-ld:usageSpecification:24abecd5-bf1f-42e0-a34f-1657f39dffe1)

- **Type:** usageSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:16 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to usageSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:usageSpecification:156985fe-69c9-4f2f-a906-cbdc01d4d427](https://tmf.dome-marketplace-sbx.org/tmf-api/usageManagement/v4/usageSpecification/urn:ngsi-ld:usageSpecification:156985fe-69c9-4f2f-a906-cbdc01d4d427)

- **Type:** usageSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:16 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to usageSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:usageSpecification:3aacf05a-838b-4160-a810-4447fc58695e](https://tmf.dome-marketplace-sbx.org/tmf-api/usageManagement/v4/usageSpecification/urn:ngsi-ld:usageSpecification:3aacf05a-838b-4160-a810-4447fc58695e)

- **Type:** usageSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:16 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to usageSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:usageSpecification:fd5da80e-fb29-45e8-8636-46b46dc2973a](https://tmf.dome-marketplace-sbx.org/tmf-api/usageManagement/v4/usageSpecification/urn:ngsi-ld:usageSpecification:fd5da80e-fb29-45e8-8636-46b46dc2973a)

- **Type:** usageSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:16 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to usageSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:usageSpecification:e16ff3ad-0bf6-4b8c-95d9-0d2e69b4c12a](https://tmf.dome-marketplace-sbx.org/tmf-api/usageManagement/v4/usageSpecification/urn:ngsi-ld:usageSpecification:e16ff3ad-0bf6-4b8c-95d9-0d2e69b4c12a)

- **Type:** usageSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:16 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to usageSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

#### Object: [urn:ngsi-ld:usageSpecification:7f9a65f1-3a08-43a0-bbc4-5ca8ec9f5ce5](https://tmf.dome-marketplace-sbx.org/tmf-api/usageManagement/v4/usageSpecification/urn:ngsi-ld:usageSpecification:7f9a65f1-3a08-43a0-bbc4-5ca8ec9f5ce5)

- **Type:** usageSpecification
- **Valid:** false
- **Timestamp:** 2025-11-28 10:40:16 UTC
- **Errors:**
  - relatedParty: Missing 'relatedParty' info for 'Seller' and 'SellerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
  - relatedParty: Missing 'relatedParty' info for 'Buyer' and 'BuyerOperator' role (Code: MISSING_RELATED_PARTY_INFO)
- **Warnings:**
  - @type: Recommended field '@type' is missing, setting it to usageSpecification (Code: MISSING_RECOMMENDED_FIELD)
  - version: Recommended field 'version' is missing (Code: MISSING_RECOMMENDED_FIELD)
  - lastUpdate: Recommended field 'lastUpdate' is missing (Code: MISSING_RECOMMENDED_FIELD)

---

*Report generated by TMForum Proxy Validator*
*Generated at: 2025-11-28 10:41:13 UTC*
