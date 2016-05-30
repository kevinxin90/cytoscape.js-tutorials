- Figure out why compound nodes are not being ordered correctly in grid layout
  - Grid layout ignores compound nodes
  - Now need to find a way to do single column layout except for DHAP/ GADP equilibrium
  - Look at using nodes.layoutPositions()
- Add a button to HTML page that animates a viewport change
  - Adding the button via HTML is difficult!
  - Can't do it in HTML because need to be able to see functions within glycolysis.js
  - Try adding a DOM element with JS in glycolysis.js
    - If this doesn't work, then use a special "advance" node in cy.js
- Get SVGs for each step
- Make SVGs background for the steps
- (Possibly?) Display information on edges
  - Would require hard-coding edges instead of dynamically generating them.