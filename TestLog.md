These are tests in which I look for bugs or errors.

Test 1.  Listings Purchased: 2 (+$0.46)
- 100 Queries
- 4 Viable Listings
- 3 Instances of Non-Filtration
- 1 XMLHttpRequest Error

Test 2.  Listings Purchased: 1 (+$0.05)
- 100 Queries
- 0 Viable Listings
- 5 Instances of Non-Filtration
- 5 Instances of slow server response
- Errors may be caused by a server-side issue at the time (outlier?)

Test 3. Listings Purchased: 0 (+$0.00)
-100 Queries
-2 Viable Listings
-5 Instances of Steam Errors involving pages not loading (server issue)
-Reduction in other errors after increasing polling time to 1000ms (not committed yet) and reducing delay to 1500ms.

Test 4. Listings Purchased: 2 (+$0.26)
-100 Queries
-5 Viable Listing
-1 Instance of tab loading slowly 



