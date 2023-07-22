# WNBA-expected-points
These repository evaluates the expected points that each team generates and concedes in a WNBA game.

The first notebook titled 'df_editor_dtwom_FINAL.ipynb' organizes each WNBA players' shooting efficiency from different regions of the floor. This will be used to calculate and expected point value for each shot attempt based on who attempts the field goal and where they shoot it.

The second notebook iterates through the game events and generates an expected score for each team based on the quantity and quality of shots each team produces. A feature of this model is that each possession can only max out at 3 points. So if a team shoots a three and gets an offensive rebound and attempts another three, the expected point value of the second three is discounted. If not, then gettting multiple offensive rebounds and attempts could yield an expected point value of 4, 5 or 6 points which is not realistic. This code can be run iteratively to generate retroactive win probabilities and determine the extent that each team deserved to win.
