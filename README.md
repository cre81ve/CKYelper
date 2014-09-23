CKYelper
========
Yelp Sample Application to demonstrate Auto Layout capabilities
And Table View Animations 

GIF 
<img src="https://github.com/cre81ve/CKYelper/blob/master/yelp_lcap_2.gif" />

- [x] Table rows should be dynamic height according to the content height
- [x] Custom cells should have the proper Auto Layout constraints
- [x] Search bar should be in the navigation bar (doesn't have to expand to show location like the real Yelp app does).
- [ ] Optional: infinite scroll for restaurant results
- [ ] Optional: Implement map view of restaurant results


- [x] The filters you should actually have are: category, sort (best match, distance, highest rated), radius (meters), deals (on/off).
- [x] The filters table should be organized into sections as in the mock.
- [x] You can use the default UISwitch for on/off states. [ ] Optional: implement a custom switch
- [x] Radius filter should expand as in the real Yelp app
- [x] Categories should show a subset of the full list (Did not implement See All)
- [x] Clicking on the "Search" button should dismiss the filters page and trigger the search w/ the new filter settings.
- [ ] Optional: Implement the restaurant detail page.

<b>Time Spent</b> :  15-16 h

<b>Comments</b>  : 

- Auto layout - with initial iOS6 way took a good amount of time for table view. 
- Did implement - android way of yelp filters. Like below 
- - <img src="https://github.com/cre81ve/CKYelper/blob/master/yelp_lcap_1.gif" />
- (took 8h) 
- Created new filter view controller with table/sections today.

<b>License </b>
=======
MIT

<b>Third Party</b>
===================
Yelp - API v2
Pods
pod 'BDBOAuth1Manager'
pod 'AFNetworking'
pod 'MBProgressHUD', '~> 0.5'

