## Overview
The data is provided by Udacity as a part of Explore and Summarize Data.

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, borrower employment status, borrower credit history, and the latest payment information.


## Data variable explanation

**ListingKey**

Unique key for each listing, same value as the 'key' used in the listing object in the API.

**ListingNumber**

The number that uniquely identifies the listing to the public as displayed on the website.

**ListingCreationDate**

The date the listing was created.

**CreditGrade**

The Credit rating that was assigned at the time the listing went live. Applicable for listings pre-2009 period and will only be populated for those listings.

**Term**

The length of the loan expressed in months.

**LoanStatus**

The current status of the loan:

* Cancelled
* Charged off
* Completed
* Current
* Defaulted
* FinalPaymentInProgress
* PastDue.

The PastDue status will be accompanied by a delinquency bucket.

**ClosedDate**

Closed date is applicable for Cancelled, Completed, Charged off and Defaulted loan statuses. 

**BorrowerAPR**
		
The Borrower's Annual Percentage Rate (APR) for the loan.

**BorrowerRate**

The Borrower's interest rate for this loan. 

**LenderYield**

The Lender yield on the loan. Lender yield is equal to the interest rate on the loan less the servicing fee.

**EstimatedEffectiveYield**

Effective yield is equal to the borrower interest rate (i) minus the servicing fee rate, (ii) minus estimated uncollected interest on charge-offs, (iii) plus estimated collected late fees.  Applicable for loans originated after July 2009.

**EstimatedLoss**

Estimated loss is the estimated principal loss on charge-offs. Applicable for loans originated after July 2009.

**EstimatedReturn**

The estimated return assigned to the listing at the time it was created. Estimated return is the difference between the Estimated Effective Yield and the Estimated Loss Rate. Applicable for loans originated after July 2009.

**ProsperRating (numeric)**

The  Prosper Rating assigned at the time the listing was created:

* 0 - N/A
* 1 - HR
* 2 - E
* 3 - D
* 4 - C
* 5 - B
* 6 - A
* 7 - AA

Applicable for loans originated after July 2009.

**ProsperRating (Alpha)**

The Prosper Rating assigned at the time the listing was created between AA - HR.  Applicable for loans originated after July 2009.

**ProsperScore**

A custom risk score built using historical Prosper data. The score ranges from 1-10, with 10 being the best, or lowest risk score.  Applicable for loans originated after July 2009.

**ListingCategory**

The category of the listing that the borrower selected when posting their listing: 

* 0 - Not Available
* 1 - Debt Consolidation
* 2 - Home Improvement
* 3 - Business
* 4 - Personal Loan
* 5 - Student Use
* 6 - Auto
* 7- Other
* 8 - Baby&Adoption
* 9 - Boat
* 10 - Cosmetic Procedure
* 11 - Engagement Ring
* 12 - Green Loans
* 13 - Household Expenses
* 14 - Large Purchases
* 15 - Medical/Dental
* 16 - Motorcycle
* 17 - RV
* 18 - Taxes
* 19 - Vacation
* 20 - Wedding Loans

**BorrowerState**

The two letter abbreviation of the state of the address of the borrower at the time the Listing was created.

**Occupation**

The Occupation selected by the Borrower at the time they created the listing.

**EmploymentStatus**

The employment status of the borrower at the time they posted the listing.

**EmploymentStatusDuration**

The length in months of the employment status at the time the listing was created.

**IsBorrowerHomeowner**

A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.

**CurrentlyInGroup**

Specifies whether or not the Borrower was in a group at the time the listing was created.

**GroupKey**

The Key of the group in which the Borrower is a member of. Value will be null if the borrower does not have a group affiliation.

**DateCreditPulled**

The date the credit profile was pulled. 

**CreditScoreRangeLower**

The lower value representing the range of the borrower's credit score as provided by a consumer credit rating agency.

**CreditScoreRangeUpper**

The upper value representing the range of the borrower's credit score as provided by a consumer credit rating agency. 

**FirstRecordedCreditLine**

The date the first credit line was opened.

**CurrentCreditLines**

Number of current credit lines at the time the credit profile was pulled.

**OpenCreditLines**

Number of open credit lines at the time the credit profile was pulled.

**TotalCreditLinespast7years**

Number of credit lines in the past seven years at the time the credit profile was pulled.

**OpenRevolvingAccounts**

Number of open revolving accounts at the time the credit profile was pulled.

**OpenRevolvingMonthlyPayment**

Monthly payment on revolving accounts at the time the credit profile was pulled.

**InquiriesLast6Months**

Number of inquiries in the past six months at the time the credit profile was pulled.

**TotalInquiries**

Total number of inquiries at the time the credit profile was pulled.

**CurrentDelinquencies**

Number of accounts delinquent at the time the credit profile was pulled.

**AmountDelinquent**

Dollars delinquent at the time the credit profile was pulled.

**DelinquenciesLast7Years**

Number of delinquencies in the past 7 years at the time the credit profile was pulled.

**PublicRecordsLast10Years**

Number of public records in the past 10 years at the time the credit profile was pulled.

**PublicRecordsLast12Months**

Number of public records in the past 12 months at the time the credit profile was pulled.

**RevolvingCreditBalance**

Dollars of revolving credit at the time the credit profile was pulled.

**BankcardUtilization**

The percentage of available revolving credit that is utilized at the time the credit profile was pulled.

**AvailableBankcardCredit**

The total available credit via bank card at the time the credit profile was pulled.

**TotalTrades**

Number of trade lines ever opened at the time the credit profile was pulled.

**TradesNeverDelinquent**

Number of trades that have never been delinquent at the time the credit profile was pulled.

**TradesOpenedLast6Months**

Number of trades opened in the last 6 months at the time the credit profile was pulled.

**DebtToIncomeRatio**

The debt to income ratio of the borrower at the time the credit profile was pulled. This value is Null if the debt to income ratio is not available. This value is capped at 10.01 (any debt to income ratio larger than 1000% will be returned as 1001%).

**IncomeRange**

The income range of the borrower at the time the listing was created.

**IncomeVerifiable**

The borrower indicated they have the required documentation to support their income.

**StatedMonthlyIncome**

The monthly income the borrower stated at the time the listing was created.

**LoanKey**

Unique key for each loan. This is the same key that is used in the API. 

**TotalProsperLoans**

Number of Prosper loans the borrower at the time they created this listing. This value will be null if the borrower had no prior loans. 

**TotalProsperPaymentsBilled**

Number of on time payments the borrower made on Prosper loans at the time they created this listing. This value will be null if the borrower had no prior loans.

**OnTimeProsperPayments**

Number of on time payments the borrower had made on Prosper loans at the time they created this listing. This value will be null if the borrower has no prior loans.

**ProsperPaymentsLessThanOneMonthLate**

Number of payments the borrower made on Prosper loans that were less than one month late at the time they created this listing. This value will be null if the borrower had no prior loans. 

**ProsperPaymentsOneMonthPlusLate**

Number of payments the borrower made on Prosper loans that were greater than one month late at the time they created this listing. This value will be null if the borrower had no prior loans.

**ProsperPrincipalBorrowed**

Total principal borrowed on Prosper loans at the time the listing was created. This value will be null if the borrower had no prior loans.

**ProsperPrincipalOutstanding**

Principal outstanding on Prosper loans at the time the listing was created. This value will be null if the borrower had no prior loans.

**ScorexChangeAtTimeOfListing**

Borrower's credit score change at the time the credit profile was pulled. This will be the change relative to the borrower's last Prosper loan. This value will be null if the borrower had no prior loans.

**LoanCurrentDaysDelinquent**

The number of days delinquent. 

**LoanFirstDefaultedCycleNumber**

The cycle the loan was charged off. If the loan has not charged off the value will be null. 

**LoanMonthsSinceOrigination**

Number of months since the loan originated.

**LoanNumber**

Unique numeric value associated with the loan.

**LoanOriginalAmount**

The origination amount of the loan.

**LoanOriginationDate**

The date the loan was originated.

**LoanOriginationQuarter**

The quarter in which the loan was originated.

**MemberKey**

The unique key that is associated with the borrower. This is the same identifier that is used in the API member object. 

**MonthlyLoanPayment**

The scheduled monthly loan payment.

**LP_CustomerPayments**

Pre charge-off cumulative gross payments made by the borrower on the loan. If the loan has charged off, this value will exclude any recoveries.

**LP_CustomerPrincipalPayments**

Pre charge-off cumulative principal payments made by the borrower on the loan. If the loan has charged off, this value will exclude any recoveries.

**LP_InterestandFees**

Pre charge-off cumulative interest and fees paid by the borrower. If the loan has charged off, this value will exclude any recoveries.

**LP_ServiceFees**

Cumulative service fees paid by the investors who have invested in the loan. 

**LP_CollectionFees**

Cumulative collection fees paid by the investors who have invested in the loan.

**LP_GrossPrincipalLoss**

The gross charged off amount of the loan.

**LP_NetPrincipalLoss**

The principal that remains uncollected after any recoveries.

**LP_NonPrincipalRecoverypayments**

The interest and fee component of any recovery payments. The current payment policy applies payments in the following order: Fees, interest, principal.

**PercentFunded**

Percent the listing was funded.

**Recommendations**

Number of recommendations the borrower had at the time the listing was created.

**InvestmentFromFriendsCount**

Number of friends that made an investment in the loan.

**InvestmentFromFriendsAmount**

Dollar amount of investments that were made by friends.

**Investors**

The number of investors that funded the loan.