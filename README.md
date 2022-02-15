# OKC_Thunder
# Data Science & Solutions Technical Assessment
## Outline
In the programing language of your choice (preferably R or Python), provide a solution to the following problem: <br/>
**For the provided shot coordinate and outcome dataset, determine the effective field goal percentage (eFG%) and percentage of team shots attempted (shot distribution) within the following shot zones: Two Point (2PT), Non Corner 3 (NC3) and Corner 3 (C3).** <br/>
You have been provided the necessary data to complete this project via the Box folder link provided in the email which accompanied this brief. The data provided is artificial and does not represent real player coordinates or locations. Please spend no more than 1 hour on the assignment. Your work must be your own and original.
The following is an outline of the provided datasets: <br/>
1) court_diagram.jpg <br/>
• An annotated diagram of the official NBA Court. All markers are measured in feet relative to the center of the hoop <br/>
• For all “Non Corner” 3’s (where Y > 7.8), the 3PT line is 23.75 ft from the center of the hoop <br/>
• For all “Corner” 3’s (where Y <= 7.8), the 3PT line is 22 feet from the court’s Y-axis at all <br/>
points (note the definition of “Corner” 3 is not determined by the “break” in the arc) 
2) shots_data.csv  <br/>
• team: name of team (Team A, Team B) <br/>
• x: X-coordinate of the shot, measured in feet <br/>
• y: Y-coordinate of the shot, measured in feet <br/>
• fgmade: boolean value indicating the outcome of the shot (0=Miss, 1=Make) <br/>
## Deliverables
1) Determinetheshotzones(2PT,NC3orC3)andcalculateforeachteamthe:<br/>
• Shot Distribution: the percentage of team shots attempted within a zone <br/>
• eFG%: the effective field goal percentage of team shots within a zone <br/>
2) Theprogrammingscriptusedtoproduceyouranswers.Youmayuseaprogramming 
language of your choice (preferably R or Python). 
3) Submityourresponsesbycarefullyfollowingtheinstructionsprovidedintheemailwhich accompanied this brief. Please submit only once. Multiple submissions will be ignored.
