# Flipkart Home Page Test Cases

## Test Scenarios

| TC ID | Type | Scenario | URL | Steps | Expected Result |
|---|---|---|---|---|---|
| TC_POS_01 | Positive | Verify the Flipkart home page loads successfully | https://www.flipkart.com/ | 1. Open the Flipkart home page URL<br>2. Observe the landing page elements | The home page loads without errors and displays the search bar, category icons, login menu, and promotional banners. |
| TC_POS_02 | Positive | Verify the search bar accepts valid product input | https://www.flipkart.com/ | 1. Open the Flipkart home page URL<br>2. Click the search bar<br>3. Enter a valid product name such as `mobile`<br>4. Submit the search | Search input is accepted and relevant search results or suggestions are displayed. |
| TC_POS_03 | Positive | Verify category navigation works from the homepage | https://www.flipkart.com/ | 1. Open the Flipkart home page URL<br>2. Click any visible category icon such as `Mobiles` or `Electronics`<br>3. Wait for the next page to load | User is navigated to the selected category page successfully. |
| TC_NEG_01 | Negative | Verify the search bar handles empty search submission | https://www.flipkart.com/ | 1. Open the Flipkart home page URL<br>2. Click the search bar<br>3. Leave it empty<br>4. Try to submit search | The application should not crash; it should either show a validation message or remain on the homepage without performing a search. |
| TC_NEG_02 | Negative | Verify invalid text input in the search bar is handled gracefully | https://www.flipkart.com/ | 1. Open the Flipkart home page URL<br>2. Click the search bar<br>3. Enter special characters or an invalid query such as `@@@@@`<br>4. Submit the search | The system should handle the input gracefully by showing no results or a suitable message instead of failing. |
| TC_EDGE_01 | Edge | Verify homepage behavior on a slow or partially loaded connection | https://www.flipkart.com/ | 1. Open the Flipkart home page URL with a slow network<br>2. Observe loading of banners, category icons, and top navigation | The page should still render core elements progressively without breaking layout or showing fatal errors. |

## Notes
- These test cases are based on the visible Flipkart homepage UI in the provided screenshot.
- The scenarios cover page load, search, navigation, invalid input handling, and loading conditions.
