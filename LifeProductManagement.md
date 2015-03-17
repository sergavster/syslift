Specifications and concerns for managing life endowment products in syslift

# Introduction #

...When a product's contribution is weekly, for a long term period of e.g.3 years, with claims benefits are linked to death of the policyholder/family member and/or refund of total or partial premium amount.

# Details #
To define the product in the software (product definition):
  * Basic Amount: is the basic component of the premium linked to the policy term.
    * n case of the endowment, the policy period may be at least 3 years for getting a share of the premium back, therefore the period to be considered is 3 years and the basic amount suggested is the premium calculated for 3 years. Should this amount varying for other reasons like the payment frequency, then other products should be created. In case of a weekly premium, the premium will be calculated as 52 times the weekly premium multiplied the number of years of the minimum commitment to get back a part of the premium.
    * in case of a term/credit life: the premium may be function of the loan amount and its term which are factors that can be entered in the product definition.
  * Admin fund%: represents here the management part of the premium or (must be equal to) the complementary part of the claim fund % part of the premium.
  * claim fund%: represents the portion of the premium to be allocated to the benefits. In an endowment product, these benefit can be almost certain (savings refund) and/or uncertain (normal insurance risk premium).
  * Sum Assured per member/per family: This is a limit that should not be informed in case of a unlimited sum insured. (e.g.: Benefit = 5000+ 50% of premium paid).
  * Benefits Definition: each case is to be listed with its corresponding limit amount. (capital alone or capital + partial premium after 3 years or capital + partial premium after 6 years...)

The benefit evaluation based on the time of the claim (e.g. if it varies after one year / 2 years...), or if it depends on the death type (natural/accidental), or if it varies depending on the age of the beneficiary, is manual and will require the claim settlement team to check / calculate before settling down a claim.
The period of the policy is important to monitor as the rights are the same during the policy and at its term.