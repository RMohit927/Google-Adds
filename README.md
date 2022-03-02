# Google-Adds

Tickets Types:
--------------
1. Broad Match: Keywords added as BM by default
-  Searches for "Chocolate gifts"
-  Resulting As "Chocolate", "Chocolate gifts", "cadbury assorted set", "Chocolate gift Delivery", "Chocolate shop chicago"

2. Phrase Match: Keywords in quotation marks that we are searching
-  Searches for "Chocolate gifts"
-  Resulting As "Chocolate gifts for father day", "best chocolate gifts", "chocolate gifts"
-  Wrong Result As "Chocolate delivery and gifts"

3. Exact Match: Keywords in square brackets - means Exactly match which what we are searching
-  Searches for "Chocolate gifts"
-  Resulting As "Chocolate gifts"
-  Wrong Result As "unique Chocolate gifts"

4. Close Varients: Apply to EM, PM, BM modified keywords, includes sigular & plural, misspellings, and other close variations
-  Searches for "Chocolate gifts"
-  Resulting As "Chocolate gifts", "Chocolate gift", "chokolate gifts"
-  Keywords will ignore function words (like to, for, the) and recordered words with same meaning
-  will match search queries with the same intent
-  Searches for "Chocolate gifts"
-  Resulting As "Chocolate for gifts", "gifts chocolate"

5. Broad Match Modifier: words with a plus sign preceding them
-  Searches for "+Chocolate gifts"
-  Resulting As "Chocolate gifts", "chocolate gift delivery", "chocolate shop chicago", "gifts of chocolate"
-  Wrong Result As "cadbury assorted set"
