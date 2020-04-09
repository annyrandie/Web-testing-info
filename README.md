# Web-testing-info

## How to test a web-site :globe_with_meridians:
:heart_eyes:[incredible source of information](https://www.softwaretestinghelp.com/web-application-testing/)

![web-testing variety](https://cdn.softwaretestinghelp.com/wp-content/qa/uploads/2018/04/WebTesting-Overview.jpg)

### Functional testing

* User navigation to different pages of the website and completing the end-to-end workflow
* If the user can select/deselect checkboxes
* If the user can select values from Dropdown fields
* If the user can select/deselect Radio buttons
* Different navigation buttons like Submit, Next, Upload etc. buttons are working well
* Calendars are loading properly and allowing the user to select a date
* Calculations are happening as implemented
* Search functionality is working if any
* Correct Information display
* Various internal & external links to other pages
* Correct Tab Order of the fields on web pages
* Mandatory and Optional fields should be verified for the positive and negative inputs
* Default values for each web field should be verified
* Email functionality is implemented for some action on the website

```
Considering cookies, which are used to maintain login sessions, the website should be tested by enabling/disabling cookies or by using the mismatched domain. Testing can also be performed across sessions by resetting cookies to bring browsers back to the vanilla state.
QA should also validate that website cookies are always stored locally in an encrypted format.
Similarly, different functionalities like Login, Signup, Search Option, Filters, Sort Order, Add to Cart, etc. should be verified on different web pages like Login Page, Sign up Page, Product Details Page, Shopping Cart, Order Review, Payment, etc. The website should be checked for session/cookie management like session expiration and session storage etc.

```
### Usability testing

![usability testing](https://cdn.softwaretestinghelp.com/wp-content/qa/uploads/2018/04/Usability-testing-Overview.jpg)

* Website content should be informative, structured and linked logically so that user can understand easily
* Web page controls should be easy for users to navigate
* The website should have Help & Instruction documents uploaded
* The website should have the Search feature for end-user convenience
* Access to/from the Main menu to all pages should be there
* Website content should be verified for any spelling mistakes
* The website should follow defined guidelines in the context of background color, pattern, style, fonts, image placements,    frames, borders, etc.
* The website should be accustomed to the translation feature considering the fact that it can be accessed by users from different nations with different languages, currencies, etc.

```
Considering the increase in touchscreen-based interfaces we need to validate the accessibility of both key inputs and touch screen inputs. Similarly, images and website content should be validated for usability on different screen sizes (mobiles, laptops, and tabs, etc.).
```

### Compatibility testing


![Compatibility testing](https://cdn.softwaretestinghelp.com/wp-content/qa/uploads/2018/04/Compatability-Testing.jpg)

* Website screen size should be adjustable as per the device
* A device should be screen rotation featured
* The website should not show up any loading issues on different devices with different network speeds
* Verify the website behavior when the device is in/out of network range
* Verify the website behavior on low CPU and Memory to support different form factors

### Security testing

* The website should be accessible to only authenticated users
* Website users should be able to perform only those tasks for which they are authorized
* The website should be verified for CAPTCHA fields for user identification
* Browser security settings should be verified while moving from secure to insecure pages
* Web Server protection should be there for inaccessible web directories or files
* Ensure restricted files should not download without appropriate access
* Sessions which got inactive should automatically get killed after a certain period of time
* All invalid and unauthorized attempts by end-users or intermittent system errors/failures should get logged for analysis purpose

As a part of security testing, an e-commerce website should be validated for

* Website Access Controls.
* Any leakage of user personal info.
* Secured Payment Methods.

### Performance testing

* Website behavior should be observed under normal and peak load conditions
* Website’s performance should be examined by measuring response time, speed, scalability and resource utilization
* Proper RCA (root cause analysis) should be done with a solution if a system breaks down or gets unstable at any point in time
* Network latency issues should be identified if any

### Interface testing

```
Interface level testing is performed to check on the smooth interaction of the website with different interfaces like Web Server & Database Server.

During interface testing, the tester needs to make sure if the application requests are being sent properly to the database and correct information is displayed to the client as output. A webserver should not throw any denial exceptions at any point in time and the database should always stay in sync with the application.

```
