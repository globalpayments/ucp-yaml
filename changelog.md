# 2025-12-04
## UPDATED
### Access Token
- Added partner permission MER_PMT_SINGLE_USE to x-gp-partner-permissions-enum.

# 2025-09-11
## UPDATED
### Authentications
- Added empty string as valid enum for status_reason field
- Added acs_reference_number to GET single Authentications


# 2025-08-18
## ADDED
### Initiate Version 1 of YAML for all files

## UPDATED
### Authentications
- Update typo in enum to MORE_THAN_SIXTY_DAYS and added new object acct_info
### Payment Methods
- Added new field auto_updater for TAAS integration 
### Transactions
- Large set of updates to fields and examples

 # 2025-09-22

## UPDATED
### Authentications
- Fixing typo in payment_account_age_indicator field
- Updated all instances of MORE_THEN_SIXTY_DAYS enum to MORE_THAN_SIXTY_DAYS
- updating authentications yaml version to 1.2

# 2025-09-22

## UPDATED
### Authentications
- Marked order.time_created reference as mandatory 
- removed empty field in initiate request 
- fixed issue with payer.work_phone field not being used
- updating authentications yaml version to 1.3

# 2025-10-02

## UPDATED
### Access Token
- Updated min and max values for field seconds_to_expire

 # 2025-10-13

## UPDATED
### Authentications
- updated the min and max length for a couple of fields 
- Made challenge_return_url and three_ds_method_return_url required in initiate request
- updating authentications yaml version to 1.4

### Transactions
- Added a new field for recurring transactions in Mexico called contract_reference 
- Added new digital wallet enum CLICK_TO_PAY
- Fixed typo in payer_verifications
- added two new enums for device object
- updating transactions yaml version to 1.1
 # 2025-11-17

## UPDATED
### Authentications
- updated the description for empty status reason. 
- updating authentications yaml version
