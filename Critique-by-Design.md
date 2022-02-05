## Selecting a visualization for redesign

The original data visualization I worked with in this assignment came from an [Urban Institute](https://apps.urban.org/features/education-equity-tool/) tool used to show the gap between white and Black students' access to critical education resources. Research shows that access to certain resources such as adequate counseling, AP classes, and experienced teachers have a significant impact on educational outcomes. However, this access isn't equally distributed across student groups, particularly when racially stratified. 



![Original Urban Institute Viz](/UrbanDataViz2.PNG) 





My first impression of this visualization was that it allowed for the size of the gaps to be evident, but the blue and yellow colors chosen (most likely a branding decision) were not contrasting enough to clearly show the difference between Black and white student data points. Further, displaying the states in an alphabetical list did not allow for the viewer to see any spatial trends. While these choices may have been appropriate for Urban Institute's audience--policy researchers looking to draw out their own subsets of data or policymakers searching for general trends--there seemed to be an aspect of the story missing here. I immediately noticed that in some states Black students had more access to these resources than white students. This is contrary to the popular narrative about discrepancies in access to quality education, and thus a story that should be highlighted by the visualization.

## Critique Method

I used Stephen Few's [Data Visualization Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) to perform a formal critique of the Urban Institute visualization. Below are a few key insights from that critique.

#### Usefulness
On a scale of 1-10, I rated this viz 6 for usefulness to the intended audience. While the features that allow for interaction and deeper data exploration are quite useful for researchers, the color selection and listing of states do not draw out useful conclusions that could dirve more targeted research. 

#### Completeness
I rated this viz an 8 for completeness--the visualization was very thorough in providing both state and district-level data, as well as data on multiple variables such as access to AP classes, adequate counselors, and experienced teachers. At the same time, this thoroughness led to a lot of eye travel for the viewer so that the data was not immediately understandable.

#### Perceptibility
Similar to the critique about completeness, I thought this visualization merited a 4 in perceptibility. The amount of eye travel required to fully understand the tool and the sheer number of features available distracted from any one key insight. 

#### Truthfulness
I gave this viz a 9 for truthfulness. I did not see any attempts to misrepresent data or indicators of false information. In fact, one nice feature of this viz was the ability to adjust the axis scale with each variable to represent the data more accurately. However, the metric used for the variables was different in 1 of 3 cases, an inconsistency that may cause an inattentive reader to misinterpret the data.

#### Intuitiveness
I gave this visualization a 5 out of 10 for intuitiveness. The number of features and formatting led to a lot of eye travel, and the listing of states felt counterintuitive for communicating spatial relationships. Because of the similarity of the colors used to represent Black and white students and the distance between the legend and the data points, it was difficult to keep track of what the colors represented.

#### Aesthetics
While this visualization was not ugly in any way, the color selection and design certainly were not chosen to wow readers. I therefore gave this a 5 out of 10 for aesthetics.

#### Engagement
Finally, on the point of engagement I gave this viz a 7 out of 10. The focus of access to educational resources certainly added a new dimension to the education gap debate. There were certain trends that stood out, in particular how regardless of racial gaps, students' access to adequate school counselors is concerningly low across the country. However, I felt that the most interesting aspect of the data--that the gap between white and Black students' access to these resources did not always flow in the same direction--did not immediately jump out and could have been featured more prominently.

## Wireframing a Redesign

Considering the above comments, I planned to execute a redesign of this visualization in three key ways:
1) Plot the data on a map to draw out any regional trends and allow viewers to explore data spatially, which is may increase intuitiveness,
2) Feature the gap between students' access as the main variable of interest, rather than including it with the raw data points, and
3) Use color effectively to show the clear contrast between states that advantage white students on these metrics as opposed to those that advantage Black students.

I also intended this redesign to highlight a trend and tell a story rather than to offer data points for exploration, which may impact what audience is drawn to it. To simplify the design, I also made the decision to focus on only two racial groups and to only show state-level data.

I initially sketched a rough redesign:

![](/Sketch1.PNG)


....which clearly demonstrated that I needed to use a digital tool because of the mapping element. 


I then used [Flourish](https://flourish.studio/) to sketch out three rough wireframe options. 

#### 1) Showing all gaps using a diverging color scale


![White-Black Access Gap to AP Classes v 1](https://user-images.githubusercontent.com/81482638/152626377-43900ed9-8b22-439a-aaef-f41a5da3df31.png)



#### 2) Featuring just the white-advantaged states


![White-Black Access Gap to AP Classes v 2](https://user-images.githubusercontent.com/81482638/152626385-85d8070b-21a2-4ee2-85cf-8ecc68dd6f5e.png)



#### 3) Featuring just the Black-advantaged states


![White-Black Access Gap to AP Classes v 3](https://user-images.githubusercontent.com/81482638/152626386-322a0250-2051-4403-98f1-98d07f4d975b.png)




