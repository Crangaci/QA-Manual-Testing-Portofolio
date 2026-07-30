# Test Execution Report 

## Project Information

Project Name:  
Online Gadget Store

Testing Type:  
Manual Testing

Test Environment:
- Browser: Google Chrome
- Operating System: Windows

Testing Period:  
July 2026


# Test Execution Summary

| Metric | Result |
|--------|--------|
| Total Test Cases | 24 |
| Executed Test Cases | 24 |
| Passed | 21 |
| Failed | 3 |
| Blocked | 0 |
| Open Bugs | 3 |

---

# Test Results

| Test Case ID | Test Scenario | Status |
|--------------|---------------|--------|
| TC_001 | Create a new account | Passed |
| TC_002 | Login with valid credentials | Passed |
| TC_003 | Login with invalid credentials | Passed |
| TC_004 | User logout | Passed |
| TC_005 | Search for a product | Failed |
| TC_006 | Open product details | Passed |
| TC_007 | Add product to shopping cart | Passed |
| TC_008 | Remove product from shopping cart | Passed |
| TC_009 | Update product quantity | Passed |
| TC_010 | Checkout process | Passed |
| TC_011 | View product reviews | Passed |
| TC_012 | Submit product review | Failed |
| TC_013 | Check website navigation | Passed |
| TC_014 | Check website images | Passed |
| TC_015 | Search with invalid product name | Passed |
| TC_016 | Verify product information | Failed |
| TC_017 | Verify empty shopping cart | Passed |
| TC_018 | Verify quantity limit | Passed |
| TC_019 | Checkout validation | Passed |
| TC_020 | Order confirmation message | Passed |
| TC_021 | Review validation | Passed |
| TC_022 | Buttons functionality | Passed |
| TC_023 | Mobile layout testing | Passed |
| TC_024 | Browser compatibility | Passed |



# Failed Test Cases

## TC_005 - Search for a product

Status: Failed

Related Bug: BUG_SEARCH_001

Issue:  
Search button does not display search results.


## TC_012 - Submit product review

Status: Failed

Related Bug: BUG_REVIEW_001

Issue:  
Website review cannot be edited after submission.


## TC_016 - Verify product information

Status: Failed

Related Bug: BUG_PRODUCT_001

Issue:  
Product details page does not display all product information.


# Defect Summary

| Bug ID | Severity | Status |
|--------|----------|--------|
| BUG_SEARCH_001 | Medium | Open |
| BUG_REVIEW_001 | Low | Open |
| BUG_PRODUCT_001 | Medium | Open |



# Conclusion

Testing was completed for the main features of the Online Gadget Store website.

Most tested functionalities worked correctly. Three issues were identified and reported. Further testing should be performed after the bugs are fixed.
