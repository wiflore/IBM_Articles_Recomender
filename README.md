<div class="_main--content-container--ILkoI"><div><div class="index--container--2OwOl"><div class="index--atom--lmAIo layout--content--3Smmq"><div class="ltr"><div class="index-module--markdown--2MdcR ureact-markdown "><h3 id="recommendations-with-ibm">Recommendations with IBM</h3>
  
<h4 id="introduction">Introduction</h4>
  
<p>For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles that they might will like.  Below there is an example of what the dashboard could look like displaying articles on the IBM Watson Platform.</p>

</div></div><span></span></div></div></div><div><div class="index--container--2OwOl"><div class="index--atom--lmAIo layout--content--3Smmq"><div><a href="#" class="image-atom--image-atom--1XDdu"><div class="index--image-atom-content--YoZVu"><div class="index--image-and-annotations-container--1o6QP"><img src="https://s3.amazonaws.com/video.udacity-data.com/topher/2018/September/5ba02d6d_screen-shot-2018-09-17-at-3.40.30-pm/screen-shot-2018-09-17-at-3.40.30-pm.png" alt="" width="891px" class="index--image--1wh9w"></div></div></a></div><span></span></div></div></div><div><div class="index--container--2OwOl"><div class="index--atom--lmAIo layout--content--3Smmq"><div class="ltr"><div class="index-module--markdown--2MdcR ureact-markdown ">
  
  <p>Though the above dashboard is just showing the newest articles, having a recommendation board available here that shows the articles that are most pertinent to a specific user.  </p>
  
<p>In order to determine which articles to show to each user, I performed a study of the data available on the IBM Watson Studio platform.  I created an account to become a part of their community, and get a better understanding of their data <a target="_blank" href="https://dataplatform.cloud.ibm.com/">by creating an account on the platform here</a>.</p>

<h3 id="your-tasks">Tasks</h3>

<p>I. <strong>Exploratory Data Analysis</strong><br></p>

<p>Before making recommendations of any kind, I explored the data.  There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. I Used this space to explore, before I dived into the details of the recommendation system in the later sections.</p>

<p>II. <strong>Rank Based Recommendations</strong><br></p>

<p>To get started in building recommendations, I first found the most popular articles simply based on the most interactions.  Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular.  These are then the articles we might recommend to new users (or anyone depending on what we know about them).</p>
<p>III. <strong>User-User Based Collaborative Filtering</strong><br></p>

<p>In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with.  These items could then be recommended to the similar users.  This would be a step in the right direction towards more personal recommendations for the users.</p>

<p>IV. <strong>Content Based Recommendations</strong><br></p>

<p>Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system.  Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system.  You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.</p>

<p>V. <strong>Matrix Factorization</strong><br></p>

<p>Finally, I completed a machine learning approach to building recommendations.  Using the user-item interactions, I built out a matrix decomposition.  Using the decomposition, I got an idea of how well I can predict new articles an individual might interact with (spoiler alert - it isn't great).  I finally discussed which methods I might use moving forward, and how I might test how well the recommendations are working for engaging users.</p>

</div></div><span></span></div></div></div></div>
