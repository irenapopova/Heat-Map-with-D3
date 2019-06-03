# Data Visualization Projects: Visualize Data with a Heat Map for freecodecamp.org

### Build a Heat Map with D3



#### Objective

Build a CodePen.io app that is functionally similar to this: https://codepen.io/freeCodeCamp/full/JEXgeY.

#### Fulfill the below user stories and get all of the tests to pass. Give it your own personal style. You can use HTML, JavaScript, CSS, and the D3 svg-based visualization library. Required (non-virtual) DOM elements are queried on the moment of each test. If you use a frontend framework (like Vue for example), the test results may be inaccurate for dynamic content. We hope to accommodate them eventually, but these frameworks are not currently supported for D3 projects.

1. User Story: My heat map should have a title with a corresponding id="title".
2. User Story: My heat map should have a description with a corresponding id="description".
3. User Story: My heat map should have an x-axis with a corresponding id="x-axis".
4. User Story: My heat map should have a y-axis with a corresponding id="y-axis".
5. User Story: My heat map should have rect elements with a class="cell" that represent the data.
6. User Story: There should be at least 4 different fill colors used for the cells.
7. User Story: Each cell will have the properties data-month, data-year, data-temp containing their corresponding month, year, and temperature values.
8. User Story: The data-month, data-year of each cell should be within the range of the data.
9. User Story: My heat map should have cells that align with the corresponding month on the y-axis.
10. User Story: My heat map should have cells that align with the corresponding year on the x-axis.
11. User Story: My heat map should have multiple tick labels on the y-axis with the full month name.
12. User Story: My heat map should have multiple tick labels on the x-axis with the years between 1754 and 2015.
13. User Story: My heat map should have a legend with a corresponding id="legend".
14. User Story: My legend should contain rect elements.
15. User Story: The rect elements in the legend should use at least 4 different fill colors.
16. User Story: I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
17. User Story: My tooltip should have a data-year property that corresponds to the data-year of the active area.

#### Here is the dataset you will need to complete this project:
* https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/global-temperature.json
