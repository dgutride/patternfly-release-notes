# 2019.04 release notes

These releases are part of the PatternFly 2019.3 milestone:
@patternfly/react-charts@4.7.1
@patternfly/react-core@3.75.2
@patternfly/react-docs@4.9.2
@patternfly/react-inline-edit-extension@2.9.49
@patternfly/react-styled-system@3.6.17
@patternfly/react-styles@3.5.7
@patternfly/react-table@2.14.23
@patternfly/react-tokens@2.6.13
@patternfly/react-topology@2.6.20
@patternfly/react-virtualized-extension@1.1.82
@patternfly/react-icons@3.10.14


## Core

**About modal:** Updated break-word on content area instead of break-all ([#2035](https://github.com/patternfly/patternfly-next/pull/2035))

**App launcher**
* Added button example to menu item    ([#2006](https://github.com/patternfly/patternfly-next/pull/2006)) 
* Added support for right and top alignment ([#2081](https://github.com/patternfly/patternfly-next/pull/2081))

**Charts**
-   Adjusted chart vars for react-charts ([#2020](https://github.com/patternfly/patternfly-next/pull/2020), [#2024](https://github.com/patternfly/patternfly-next/pull/2024))
-   Adjusted 3 chart tooltip color vars and adds two new ones. This will ensure tooltips can be seen over the current background color. ([#2038](https://github.com/patternfly/patternfly-next/pull/2038))    
-   Added individual padding vars for donut charts ([#2068](https://github.com/patternfly/patternfly-next/pull/2068))

**Chip:** updated padding on chip label ([#2063](https://github.com/patternfly/patternfly-next/pull/2063))

**Chore:** Updated release notes for latest milestones ([#2014](https://github.com/patternfly/patternfly-next/pull/2014))

**Divider:** Added divider component ([#2080](https://github.com/patternfly/patternfly-next/pull/2080))

**Drawer:** Added drawer component ([#2069](https://github.com/patternfly/patternfly-next/pull/2069))

**Dropdown:**
-   Added space-between when width of dropdown grows ([#2050](https://github.com/patternfly/patternfly-next/pull/2050))
-   Centered plain button content ([#2071](https://github.com/patternfly/patternfly-next/pull/2071))
    
**Experimental features:** Added experimental feature support ([#2031](https://github.com/patternfly/patternfly-next/pull/2031))

**Icons:** Changed selector that wraps extend for lower specificity ([#2018](https://github.com/patternfly/patternfly-next/pull/2018))

**Login:** Unset the link color text so that its white. ([#2032](https://github.com/patternfly/patternfly-next/pull/2032))

**Navigation:** Changed max-height to 100% for subnav  ([#2061](https://github.com/patternfly/patternfly-next/pull/2061))

**Options menu:** Centered plain button content ([#2071](https://github.com/patternfly/patternfly-next/pull/2071))
    
**Page:** Removed toggle from horizontal nav page demo ([#2004](https://github.com/patternfly/patternfly-next/pull/2004))

**Pagination:** Added disabled variation ([#2015](https://github.com/patternfly/patternfly-next/pull/2015))

**Red Hat font:** Added opt-in option to use Red Hat font ([#1813](https://github.com/patternfly/patternfly-next/pull/1813))

**Select**
-   Added plain variation ([#2053](https://github.com/patternfly/patternfly-next/pull/2053))
-   Updated class selector, stacking context for typeahead input ([#2075](https://github.com/patternfly/patternfly-next/pull/2075))
    
**Switch:** Removed dependency on font-size for switch's height ([#2049](https://github.com/patternfly/patternfly-next/pull/2049))

**Table**
-   Renamed data table to table ([#2051](https://github.com/patternfly/patternfly-next/pull/2051))
-   Wrapped button icons in demo with button icon class to add space ([#1978](https://github.com/patternfly/patternfly-next/pull/1978))
-   Fixed data-label attr in table demos ([#2060](https://github.com/patternfly/patternfly-next/pull/2060))
-   Added example of pf-m-wrap modifier for use in thead cells ([#2065](https://github.com/patternfly/patternfly-next/pull/2065))
    
**Tooltip:** Broke words in a place to fit in tooltip ([#2033](https://github.com/patternfly/patternfly-next/pull/2033))

## React

**About modal**: AboutModal and Modal both now trap focus in the browser. ([#2428](https://github.com/patternfly/patternfly-react/pull/2428))

**Accordion**: Added prop to heading level of parent component ([#2290](https://github.com/patternfly/patternfly-react/pull/2290))

**Application launcher**: Allowed custom icon for application launcher toggle ([#2492](https://github.com/patternfly/patternfly-react/pull/2492))
    
**Badges**
-   Temporarily disabled problematic badges ([#2530](https://github.com/patternfly/patternfly-react/pull/2530))    
-   Added space between badges in the examples ([#2556](https://github.com/patternfly/patternfly-react/pull/2556))
    
**Breadcrumb switcher:** Fixed Autocomplete camelCase ([#2457](https://github.com/patternfly/patternfly-react/pull/2457))

**Build**
-   We hashed the folder name before we recursively call hashDir again.  ([#2377)](https://github.com/patternfly/patternfly-react/pull/2377)    
-   Added PR comment on publish ([#2433](https://github.com/patternfly/patternfly-react/pull/2433))    
-   Added check for breaking change to lint ([#2462](https://github.com/patternfly/patternfly-react/pull/2462))   
-   Made a few fixes were necessary for Windows support. ([#2471](https://github.com/patternfly/patternfly-react/pull/2471))
    
**Charts**
-   Fixed runtime errors related to theme padding ([#2430](https://github.com/patternfly/patternfly-react/pull/2430))    
-   Added charts to react-integration tests ([#2354](https://github.com/patternfly/patternfly-react/pull/2354))    
-   Updated chart theme to use pf-core variables ([#2439](https://github.com/patternfly/patternfly-react/pull/2439))    
-   Removed invalid pf-core var ([#2463](https://github.com/patternfly/patternfly-react/pull/2463))    
-   Adjusted pf-core vars & added tooltip examples ([#2497](https://github.com/patternfly/patternfly-react/pull/2497))    
-   Updated pf-core vars ([#2480](https://github.com/patternfly/patternfly-react/pull/2480))   
-   Provided an accessible title and description ([#2500](https://github.com/patternfly/patternfly-react/pull/2500))    
-   Added bottom-left legend position ([#2442](https://github.com/patternfly/patternfly-react/pull/2442))    
-   Tweaked aria title for area chart ([#2510](https://github.com/patternfly/patternfly-react/pull/2510))    
-   Replaced prop `titleComponent` by `subTitleComponent` on donut charts ([#2488](https://github.com/patternfly/patternfly-react/pull/2488))
-   Added individual padding vars for donut charts ([#2529](https://github.com/patternfly/patternfly-react/pull/2529))  
-   Added new mutil-color theme for ordered charts ([#2552](https://github.com/patternfly/patternfly-react/pull/2552))    
-   Added fixed point notation into percentage donut charts ([#2375](https://github.com/patternfly/patternfly-react/pull/2375))
-   Used vars to enable Red Hat fonts ([#2584](https://github.com/patternfly/patternfly-react/pull/2584))
    
**Chore**
-   Updated release notes for milestone  ([#2448](https://github.com/patternfly/patternfly-react/pull/2448)) 
-   Removed tippy-react dependency ([#2505](https://github.com/patternfly/patternfly-react/pull/2505))
-   Updated react-docs to use Red Hat font ([#2563](https://github.com/patternfly/patternfly-react/pull/2563))
  
**Datalist:** Added hidden and visible breakpoints ([#2251](https://github.com/patternfly/patternfly-react/pull/2251))

**Docs:** Updated link to react-tokens page in the readme ([#2453](https://github.com/patternfly/patternfly-react/pull/2453))

**Dropdown:** Provided option to not autofocus on first item ([#2473](https://github.com/patternfly/patternfly-react/pull/2473))

**Empty state:** Updated EmptyStateBody to use div instead of p ([#2499](https://github.com/patternfly/patternfly-react/pull/2499))

**Experimental features:** Added POC for experimental button and badge ([#2363](https://github.com/patternfly/patternfly-react/pull/2363))

**Gallery:** Converted gallery to typescript ([#2432](https://github.com/patternfly/patternfly-react/pull/2432))

**Login page:** Removed ariaLabel from checkbox ([#2455](https://github.com/patternfly/patternfly-react/pull/2455))

**Modal:** Modal now traps screen reader focus ([#2406](https://github.com/patternfly/patternfly-react/pull/2406))

**Options menu:** Updated examples to trigger select on the whole item ([#2513](https://github.com/patternfly/patternfly-react/pull/2513))

**Pagination**
-   Dropdown closes on click outside of menu area ([#2235](https://github.com/patternfly/patternfly-react/pull/2235))  
-   Added ability to allow users to enter numbers into the input field ([#2417](https://github.com/patternfly/patternfly-react/pull/2417))
    
**Select**
-   Removed ariaLabel from grouped checkbox select ([#2456](https://github.com/patternfly/patternfly-react/pull/2456))  
-   Added optional display via children to option ([#2419](https://github.com/patternfly/patternfly-react/pull/2419)) 
-   Updated typeahead filtered list when children change ([#2518](https://github.com/patternfly/patternfly-react/pull/2518))
    
**Styles:** Added pickProperties to react-styles utils exports ([#2481](https://github.com/patternfly/patternfly-react/pull/2481))

**Switch:** Added OUIA compatibility to Switch ([#2304](https://github.com/patternfly/patternfly-react/pull/2304))

**Table**
-   Checked empty array in areAllRowsSelected ([#2527](https://github.com/patternfly/patternfly-react/pull/2527))
-   Added exports for compoundExpand ([#2554](https://github.com/patternfly/patternfly-react/pull/2554))
    
**Tabs**
-   Allowed eventKey to accept a string ([#2493](https://github.com/patternfly/patternfly-react/pull/2493)) 
-   Implemented overflow styles for secondary tabs ([#2512](https://github.com/patternfly/patternfly-react/pull/2512))

**Tooltip:** Added support for aria prop from Tippy library ([#2539](https://github.com/patternfly/patternfly-react/pull/2539))

**Typescript**
-   Bullseye ([#2427](https://github.com/patternfly/patternfly-react/pull/2427)) 
- Gallery ([#2432](https://github.com/patternfly/patternfly-react/pull/2432))
-   Grid ([#2443](https://github.com/patternfly/patternfly-react/pull/2443))    
-   Level ([#2450](https://github.com/patternfly/patternfly-react/pull/2450))
-   Pagination ([#2256](https://github.com/patternfly/patternfly-react/pull/2256))  
-   Split ([#2466](https://github.com/patternfly/patternfly-react/pull/2466))
-   Stack ([#2412](https://github.com/patternfly/patternfly-react/pull/2412))
-   Switch ([#2311](https://github.com/patternfly/patternfly-react/pull/2311))
-   Toolbar ([#2475](https://github.com/patternfly/patternfly-react/pull/2475))
    
**Unit tests**: Fixed keyHandler tests in util.test.js -- tests are now passing. ([#2489](https://github.com/patternfly/patternfly-react/pull/2489))





<!--stackedit_data:
eyJoaXN0b3J5IjpbNTg4MzcwNzc1LDY3NDU1NjcxNiw4ODgzMz
U2MjcsLTIxMjE5MzYzMzUsLTgxNTU2MDk0OCw3MDU0Mjg4NTQs
LTIwOTE3MTA2NjgsODY4OTA2MDJdfQ==
-->