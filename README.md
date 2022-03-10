# meteor_LinkedIn Project Instructions / Points

<p>This assignment will be your own recreation of <strong>LinkedIn.com</strong> using components and scss in conjunction with imports in a <strong>_main.scss</strong> . The following are tentative requirements:</p>
<ul>
<li>Allow all users to view posted topics</li>
<li>Allow users to add their own topic</li>
<li>Allow users to provide a thumbs up for any topic and keep a running total of thumbs up&nbsp;</li>
<li>Newest on top for topics&nbsp;</li>
<li>Allow users to reply to topics (replies show up directly under topic the reply is related to)
<ul>
<li>Allow users to vote up or down replies&nbsp;</li>
</ul>
</li>
<li>Allow users to provide links to external sources<span style="text-decoration: line-through;"></span></li>
</ul>
<p><strong>Possible Bonus</strong></p>
<ul>
<li>Allow users to sign in / sign up with google, facebook, twitter, or something similar</li>
<li>When users are logged in with social account (e.g., twitter) - provide username and post and have username linked to their respective account</li>
<li>Do something that is cool / impressive that without a doubt, someone (like your instructor) would say wow, that is cool.</li>
</ul>
<p>While style is not listed as a requirement, it is expected that you make some effort using scss in conjunction with imports in a _main.scss.</p>
<p>Lastly, it is expected that you write your own code vs. cloning the gitHub lecture code and then modifying it to "fit" the assignment.</p>
<p>As a reminder - any time you create and export a new collection in your api directory - you will need to import that collection into your server/main.js (it handles the mongoDB interaction and need to know about the collection). If it is not there, you will not be able to .find().fetch or .insert anywhere in your program (especially on client side b/c it communitates with the ddp which synchs with the db).</p>
<ul>
<li>in replies_to_posts.js - export const UP_Collection_Access = new Mongo.Collection('user_replies_collection');</li>
<li>in server/main.js - import {User_Replies_Collection_Access} from './../imports/api/replies_to_posts.js';</li>
</ul>
<h3>Tentative Points</h3>
<table border="1">
<tbody>
<tr>
<td>Points</td>
<td>Requirements</td>
</tr>
<tr>
<td>40</td>
<td>Allow users to: post new topics, view posted topics, and provide thumbs up and thumbs down or like/dis-like (or something similar) for a topic with a running total <span style="text-decoration: line-through;">for each</span>. Newest topics go on top (<span style="text-decoration: line-through;">with time stamp</span>). Style using imports in _main.scss is expected.</td>
</tr>
<tr>
<td>2</td>
<td>Allow users to reply to posts (reply shows up under the topic being replied to)</td>
</tr>
<tr>
<td>2</td>
<td>Allow users to vote up or down replies</td>
</tr>
<tr>
<td>2</td>
<td>Allow users to provide usable (clickable) links to external sources</td>
</tr>
  
<tr>
<td>2</td>
<td>Deployed on google server</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>

<tr>
<td>48</td>
<td>Total</td>
</tr>
<tr>
<td colspan="2"><strong>Tentative Bonus</strong></td>
</tr>
<tr>
<td>2</td>
<td>Allow users to sign in with google, facebook (needs https), twitter, or something similar</td>
</tr>
<tr>
<td>2</td>
<td>When users are logged in with social account (e.g., twitter) - provide username&nbsp;with post and have username linked to their respective account</td>
</tr>
<tr>
<td>2</td>
<td>Do something that is cool / impressive that without a doubt, someone (like your instructor) would say wow, that is cool.</td>
</tr>
</tbody>
</table>
<h3>Submissions</h3>
<ul>
<li>push this project up to github classroom </li>
  <li>Submit the url of your project on google</li>
</ul>
