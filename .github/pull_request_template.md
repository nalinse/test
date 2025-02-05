### Summary Of Changes :fire:

<!-- Add a brief description of changes here and explain why we want to make these changes. If you are bumping a version please include a link to the changelog if one is available or link to the PR that describes the changes in the dependency. -->

#### Please make sure to follow the module guidelines before making any changes to an existing module. :bulb:

Figma reference https://www.figma.com/file/F0Bsc08Dk4iH5eRyzfSn6j/Framework-modules?node-id=1028%3A5962&t=T2wRZwDAuAwAEpLV-0


Jira/ClickUp card:  

### How can someone else test this change? :mag:

<!-- 
Give clear reproducible steps on how someone else can test this change once it hits production.
All unit tests must be written using React Testing Library
https://testing-library.com/docs/react-testing-library/intro
All feature tests must be written using Cypress Testing Library
https://testing-library.com/docs/cypress-testing-library/intro
-->

### Please Make Sure The PR Title Has PR Type PreFix: [module, feat,fix, docs, lint, refactor, test, chore, revert] Ex: feat: add new feature

### Screenshots (If Visual Change) :camera:

#### Before

#### After

### Accessibility  `Requirements`

- What is the scope of change in your pull request?
  	- [ ] [Styling](https://github.expedia.biz/Brand-Expedia/Accessible_PR#visual-updates)
	- [ ] [Layout, component, or attribution changes](https://github.expedia.biz/Brand-Expedia/Accessible_PR#markup-or-attribution-updates)
	- [ ] [Logic/behavior changes](https://github.expedia.biz/Brand-Expedia/Accessible_PR#logic-or-functionality-updates)

### Contributing/Merging Checklist :heavy_check_mark:


#### Design Testing
* [ ] Availability of required header & footer
* [ ] Availability of required modules as in the design
* [ ] Fonts/Colors consistency with the design
* [ ] Element alignment-vertical/horizontal with the design
* [ ] Element size consistency with the design
* [ ] Availability of required overlays and hover states on page elements
* [ ] Usage of images from the media server
* [ ] Default hotel/package/flight image set for missing images
* [ ] All image width and height is  in the correct scale as the original image
* [ ] All UITK components and shared ui components have their standard styles
* [ ] Make sure not to write any styling base on the pure html element. 

#### Responsive Testing
* [ ] Chrome simulator iPhone
* [ ] Chrome simulator iPad (Both Orientation)
* [ ] Chrome simulator big screen sizes
* [ ] Browser resize testing with Chrome (Increasing width & decreasing width)

#### Functionality Testing
* [ ] Wizard validations
* [ ] Wizard Typeahead and Calander
* [ ] Wizard  basic search in available LOBs
* [ ] Links-if a hyper link on the expedia web page is linked to external web site, it should opened the link in new tab. if it is expedia site link it should open inside same tab
* [ ] Buttons functionality
* [ ] Deal filter functionality
* [ ] Default sorting criteria of deals and drop downs
* [ ] Sorting functionality of deals
* [ ] Form field level data validations and passing
* [ ] Map functionality
* [ ] Footer and Social media links
* [ ] No JS errors on browser console at page load/Remove unwanted console logs
* [ ] Deal link should not directed to disambig pages or not give 404
* [ ] Page body content accuracy (Copy/Links/Images)
* [ ] Proper messaging for no deals available situations & error conditions

#### SEO and Tracking Verification
* [ ] URL format
* [ ] Page title
* [ ] H1
* [ ] H2
* [ ] Meta description
* [ ] Meta keywords
* [ ] Canonical tags
* [ ] ALT attributes
* [ ] Omniature page name
* [ ] Tracking verification (GA/RFRR/ MCICID tracking for deals, check whether a unique classname exists for GA4, links etc.…)

#### Cypress Test Automation
* [ ] e2e 
* [ ] components
* [ ] api