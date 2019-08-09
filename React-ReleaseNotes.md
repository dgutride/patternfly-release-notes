
# 2019.06 release notes (2019-07-24)

These releases are part of the PatternFly 2019.05 milestone:
- [@patternfly/react-charts@4.7.1](https://www.npmjs.com/package/@patternfly/react-charts/v/4.7.1) 
- [@patternfly/react-core@3.75.2](https://www.npmjs.com/package/@patternfly/react-core/v/3.75.2)
- [@patternfly/react-styles@3.5.7](https://www.npmjs.com/package/@patternfly/react-styles/v/3.5.7)
- [@patternfly/react-table@2.14.23](https://www.npmjs.com/package/@patternfly/react-table/v/2.14.23)
- [@patternfly/react-tokens@2.6.13](https://www.npmjs.com/package/@patternfly/react-tokens/v/2.6.13)
- [@patternfly/react-topology@2.6.20](https://www.npmjs.com/package/@patternfly/react-topology/v/2.7.2)
- [@patternfly/react-icons@3.10.14](https://www.npmjs.com/package/@patternfly/react-icons/v/3.10.14)
- [@patternfly/react-virtualized-extension@1.1.82](https://www.npmjs.com/package/@patternfly/react-virtualized-extension/v/1.1.82) 
- [@patternfly/react-inline-edit-extension@2.9.49](%28https://www.npmjs.com/package/@patternfly/react-inline-edit-extension%29)

## Charts ([@patternfly/react-charts@4.7.1](%28https://www.npmjs.com/package/@patternfly/react-charts/v/4.7.1%29))
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
    
## Components ([@patternfly/react-core@3.75.2](https://www.npmjs.com/package/@patternfly/react-core/v/3.75.2))  
 - **About modal**: AboutModal and Modal both now trap focus in the browser. ([#2428](https://github.com/patternfly/patternfly-react/pull/2428))
 -   **Accordion**: Added prop to heading level of parent component ([#2290](https://github.com/patternfly/patternfly-react/pull/2290))
 - **Application launcher**: Allowed custom icon for application launcher toggle ([#2492](https://github.com/patternfly/patternfly-react/pull/2492))
 -  **Badges**
	  -   Temporarily disabled problematic badges ([#2530](https://github.com/patternfly/patternfly-react/pull/2530))    
	  -   Added space between badges in the examples ([#2556](https://github.com/patternfly/patternfly-react/pull/2556))
 - **Breadcrumb switcher:** Fixed Autocomplete camelCase ([#2457](https://github.com/patternfly/patternfly-react/pull/2457))
 -  **Datalist:** Added hidden and visible breakpoints ([#2251](https://github.com/patternfly/patternfly-react/pull/2251))
 - **Dropdown:** Provided option to not autofocus on first item ([#2473](https://github.com/patternfly/patternfly-react/pull/2473))
 - **Empty state:** Updated EmptyStateBody to use div instead of p ([#2499](https://github.com/patternfly/patternfly-react/pull/2499))
 - **Experimental features:** Added POC for experimental button and badge ([#2363](https://github.com/patternfly/patternfly-react/pull/2363))
 - **Gallery:** Converted gallery to typescript ([#2432](https://github.com/patternfly/patternfly-react/pull/2432))
 - **Login page:** Removed ariaLabel from checkbox ([#2455](https://github.com/patternfly/patternfly-react/pull/2455))
 - **Modal:** Modal now traps screen reader focus ([#2406](https://github.com/patternfly/patternfly-react/pull/2406))
 - **Options menu:** Updated examples to trigger select on the whole item ([#2513](https://github.com/patternfly/patternfly-react/pull/2513))
 - **Pagination**
	  - Dropdown closes on click outside of menu area ([#2235](https://github.com/patternfly/patternfly-react/pull/2235))  
	-   Added ability to allow users to enter numbers into the input field ([#2417](https://github.com/patternfly/patternfly-react/pull/2417))
- **Select**
	-	Removed ariaLabel from grouped checkbox select ([#2456](https://github.com/patternfly/patternfly-react/pull/2456))  
	-   Added optional display via children to option ([#2419](https://github.com/patternfly/patternfly-react/pull/2419)) 
	-   Updated typeahead filtered list when children change ([#2518](https://github.com/patternfly/patternfly-react/pull/2518))
- **Switch:** Added OUIA compatibility to Switch ([#2304](https://github.com/patternfly/patternfly-react/pull/2304)) 
- **Tabs**
	- Allowed eventKey to accept a string ([#2493](https://github.com/patternfly/patternfly-react/pull/2493)) 
	-   Implemented overflow styles for secondary tabs ([#2512](https://github.com/patternfly/patternfly-react/pull/2512))
- **Tooltip:** Added support for aria prop from Tippy library ([#2539](https://github.com/patternfly/patternfly-react/pull/2539))

## TypeScript conversion  
-   Bullseye ([#2427](https://github.com/patternfly/patternfly-react/pull/2427)) 
- Gallery ([#2432](https://github.com/patternfly/patternfly-react/pull/2432))
-   Grid ([#2443](https://github.com/patternfly/patternfly-react/pull/2443))    
-   Level ([#2450](https://github.com/patternfly/patternfly-react/pull/2450))
-   Pagination ([#2256](https://github.com/patternfly/patternfly-react/pull/2256))  
-   Split ([#2466](https://github.com/patternfly/patternfly-react/pull/2466))
-   Stack ([#2412](https://github.com/patternfly/patternfly-react/pull/2412))
-   Switch ([#2311](https://github.com/patternfly/patternfly-react/pull/2311))
-   Toolbar ([#2475](https://github.com/patternfly/patternfly-react/pull/2475))

## Table ([@patternfly/react-table@2.14.23](https://www.npmjs.com/package/@patternfly/react-table/v/2.14.23))
-   Checked empty array in areAllRowsSelected ([#2527](https://github.com/patternfly/patternfly-react/pull/2527))
-   Added exports for compoundExpand ([#2554](https://github.com/patternfly/patternfly-react/pull/2554))

## Styles ([@patternfly/react-styles@3.5.7](https://www.npmjs.com/package/@patternfly/react-styles/v/3.5.7))

 - Added pickProperties to react-styles utils exports ([#2481](https://github.com/patternfly/patternfly-react/pull/2481))

## Docs

 - Updated link to react-tokens page in the readme ([#2453](https://github.com/patternfly/patternfly-react/pull/2453))  

## Other

 - **Build**
	 - We hashed the folder name before we recursively call hashDir again.  ([#2377)](https://github.com/patternfly/patternfly-react/pull/2377)    
	 -   Added PR comment on publish ([#2433](https://github.com/patternfly/patternfly-react/pull/2433))    
	 -   Added check for breaking change to lint ([#2462](https://github.com/patternfly/patternfly-react/pull/2462))   
	 -   Made a few fixes were necessary for Windows support. ([#2471](https://github.com/patternfly/patternfly-react/pull/2471)) 
 - **Chore**
	 -   Updated release notes for milestone  ([#2448](https://github.com/patternfly/patternfly-react/pull/2448)) 
	 -   Removed tippy-react dependency ([#2505](https://github.com/patternfly/patternfly-react/pull/2505))
	 -   Updated react-docs to use Red Hat font ([#2563](https://github.com/patternfly/patternfly-react/pull/2563))  
 - **Unit tests**: Fixed keyHandler tests in util.test.js -- tests are now passing. ([#2489](https://github.com/patternfly/patternfly-react/pull/2489))

<!--stackedit_data:
eyJoaXN0b3J5IjpbNDg2MjQ4NDAzLC0xMjkzMDE2NTIsLTE0OT
U4MzcwNzEsMTMxNTgxNTMzNywtMTM5MDUxNzM0MywtNzY2MzEw
MTQzLC0xNDk1ODM3MDcxLDE2Mjk0NTczNjcsLTE1MTQ4NjI3NT
ksLTE1MzkyNzUwOTQsMjA4NjE1MDM2NCwxMTExMzQyODM2LDc3
NjMyNjA5MiwxNzIxNzgxMDU4LDQ5NDQxMDkxNiwtOTQwMjY4Nz
A0LC0xNTc2NTI1MjkyLC0xMjgxNTAzNzU5LDE0NjE2MTUyNjAs
LTI5NDA4NzYyMV19
-->