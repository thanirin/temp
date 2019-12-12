# 2019-ITCS371-1-BackFromTianjin
## Group 4   

**Customer:** group 3 (RiseOfKingdom)  
**Biz domain:** Traveling (Talon)
## Business Introduction

<p>
    RiseOfKingdom discovered that Thai people who travel abroad encounter various problems during the trip, such as the rigorous timeline, disappointed attractions and activities, and unfamiliar transportation. Consequently, they were not satisfied with their trip and likely to spend a longer period planning the trip. From this problem, RiseOfKingdom believes that they can offer a service that is an intermediary between tourists and the local people in each country, which can change the way Thai people travel and experience their trips.
</p>
<p>
    Accordingly, RiseOfKingdom conceptualizes Talón, a platform for tourists who want to experience a flexible and customizable trip. This service allows tourists to enjoy their trip the way they desire and fully immerse themselves in the story of the hidden gem with the assistance of the local experts in each country. Talón provides functions based on two target groups including tourists and local guides. There are four main functions for Tourists covering from planning the trip (or buying the trip created by the local guide) to the experience during the trip. Besides, Talón provides three main functions for Local Tour Guides which assist them in creating their profile, creating the trip and communicate with their tourists at ease. 
</p>

## Problem and Concept
- Thai people are not happy with the trip
- The middle platform between <u>tourists</u> and <u>local guides</u>.

## Requirements
The platform is able to let the tourist customise their trip with the help of the local guide(s).

# Functional Requirements
## Local Guide
1. Registration
    1. The local guide must fill in essential information (e.g. Language proficiency, name, age, gender, skills, etc.) to register to the platform
2. Criminal record approval
    1. The local guide information is retrieved from the registration
    2. This information is sent to authoritative organization for the approval
3. Creation of the guide's profile
    1. Allow the guide to advertise themselves to the tourists
4. Creation of the trip 
    1. Allow the guide to create the trips for the tourist to choose from

5. Translation tool 
    1. Assist the foreign guides to smoothly interact with Thai users
6. Forum (blog)
    1. Allow the guide to recommend places / foods / activities
    2. Allow the guide to comment and/or answer in the forum
7. Wallet
    1. Allow the guide to receive the payment from the platform

## Tourist
1. Registration
    1. Tourist must register to the platform before using the service
2. Customizable trip
    1. Allow tourist to adjust/rearrange the trip that is created by the local guide
3. Recommendation system about the activity, food, place etc.
    1. based on the tourist's preference (personalised)
4. Search for the trip plan
    1. Allow tourist to search for the trip based on his/ her preference
5. Planning the trip
    1. Allow the tourist to arrange the trip by themselves
    2. Allow multiple users to collaborate on creating the trip
6. Chatting system
    1. Allow the tourist to chat with other users
    2. Allow the tourist to chat with the guide
7. Forum
    1. Allow the tourist to write a review for the trip in the forum
    2. Allow the tourist to ask questions in the forum 
    3. Allow the tourist to be able to search the trip review in the forum
8. Payment system
    1. Allow the tourist to purchase the trip created by the local guide via credit card, debit card, paypal, internet banking, counter payment.
    2. Allow the tourist to subscribe to the service via credit card, debit card, paypal, internet banking, counter payment.
9. Trip rating and review
    1. Allow the tourist to rate and review the trip after the trip ends

# Non-functional Requirement
## Local Guide
1. Create a friendly UI and UX
2. Allow the platform to Available on both PC and mobile
3. Let the platform be fast and Responsive
4. Multi-lingual option
    1. Provide the platform in different languages
5. uptime is guaranteed to be 99.95%.

## Tourist
1. Fast
    1. Able to immediately get the answer(s) from the system in case it is generic information
2. Allow the platform to be available on both PC and mobile
3. Interactive app
    1. Optimise the app to be able to engage with the user more
       > E.g. when the user arrives at the destination -> the app will notify the user of the arrival and provide necessary information
       >
       > E.g. when the user clicks the map -> the app will show the information about that place
4. Create a friendly and intuitive UI and UX
5. Multi-lingual option
    1. Provide the platform in different languages
6. uptime is guaranteed to be 99.95%.


# Requirements prioritization Table
<table>
    <tr>
        <th>Req. #</th>
        <th>Brief Req. Description</th>
        <th>Req. Source</th>
        <th>Req. Priority</th>
        <th>Req. Status</th>
    </tr>
    <tr>
        <td>#1</td>
        <td>Tourist must register to the platform before using the service</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#2</td>
        <td>Allow tourist to adjust/rearrange the trip that is created by the local guide</td>
        <td>Client</td>
        <td>High</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#3</td>
        <td>Recommendation system about the activity, food, place etc. based on the tourist&#39;s
            preference (personalised)</td>
        <td>Client</td>
        <td>High</td>
        <td>Postponed for next release</td>
    </tr>
    <tr>
        <td>#4</td>
        <td>Allow the tourist to arrange the trip by themselves</td>
        <td>Client</td>
        <td>Medium</td>
        <td>Postponed for next release</td>
    </tr>
    <tr>
        <td>#5</td>
        <td>Allow multiple users to collaborate on creating the trip</td>
        <td>Client</td>
        <td>Medium</td>
        <td>Postponed for next release</td>
    </tr>
    <tr>
        <td>#6</td>
        <td>Chatting system - Allow the tourist to chat with other users</td>
        <td>Client</td>
        <td>Medium</td>
        <td>Postponed for next release</td>
    </tr>
    <tr>
        <td>#7</td>
        <td>Chatting system - Allow the tourist to chat with the guide</td>
        <td>Client</td>
        <td>High</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#8</td>
        <td>Allow the tourist to write a review for the trip in the forum</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#9</td>
        <td>Allow the tourist to ask questions in the forum</td>
        <td>Client</td>
        <td>High</td>
        <td>Postponed for next release</td>
    </tr>
    <tr>
        <td>#10</td>
        <td>Allow the tourist to be able to search the trip review in the forum</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#11</td>
        <td>Allow the tourist to purchase the trip created by the local guide</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#12</td>
        <td>Allow the tourist to subscribe to the service</td>
        <td>Client</td>
        <td>Medium</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#13</td>
        <td>The local guide must fill in essential information (e.g. Language proficiency, name,
            age, gender, skills, etc.) to register to the platform</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#14</td>
        <td>The local guide information is retrieved from the registration</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#15</td>
        <td>The local guide information is sent to authoritative organization for the approval</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#16</td>
        <td>Allow the guide to advertise themselves to the tourists</td>
        <td>Client</td>
        <td>High</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#17</td>
        <td>Allow the guide to create the trips for the tourist to choose from</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#18</td>
        <td>Provide the platform in different languages</td>
        <td>Client</td>
        <td>Low</td>
        <td>Postponed for next release</td>
    </tr>
    <tr>
        <td>#19</td>
        <td>Assist the foreign guides to smoothly interact with Thai users</td>
        <td>Client</td>
        <td>Low</td>
        <td>Postponed for next release</td>
    </tr>
    <tr>
        <td>#20</td>
        <td>Allow the guide to recommend places / foods / activities</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#21</td>
        <td>Allow the guide to comment and/or answer in the forum</td>
        <td>Client</td>
        <td>High</td>
        <td>Postpone for next release</td>
    </tr>
    <tr>
        <td>#22</td>
        <td>Allow the guide to receive the payment from the platform</td>
        <td>Client</td>
        <td>Low</td>
        <td>Postponed for next release</td>
    </tr>
    <tr>
        <td>#23</td>
        <td>Able to immediately get the answer(s) from the system in case it is generic information
        </td>
        <td>Client</td>
        <td>High</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#24</td>
        <td>Allow the platform to be available on both PC and mobile</td>
        <td>Client</td>
        <td>Medium</td>
        <td>Postpone for next release</td>
    </tr>
        <td>#25</td>
        <td>Interactive app - Optimise the app to be able to engage with the user more</td>
        <td>Client</td>
        <td>High</td>
        <td>Postpone for next release</td>
    </tr>
    <tr>
        <td>#26</td>
        <td>Create a friendly and intuitive UI and UX</td>
        <td>Client</td>
        <td>Medium</td>
        <td>Postpone for next release</td>
    </tr>
    <tr>
        <td>#27</td>
        <td>Uptime guaranteed to be 99.9%</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#28</td>
        <td>Criminal record approval</td>
        <td>Client</td>
        <td>High</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#29</td>
        <td>Accept payment in various forms</td>
        <td>Client</td>
        <td>High</td>
        <td>Accepted for this release</td>
    </tr>
    <tr>
        <td>#30</td>
        <td>Allow the tourist to rate and review their trip</td>
        <td>Client</td>
        <td>Urgent</td>
        <td>Accepted for this release</td>
    </tr>
</table>


# Talon's Use Case diagram
![Use Case Diagram](https://github.com/ICT-Mahidol/2019-ITCS371-1-BackFromTianjin/blob/master/Images/Use%20Case.jpg "Use Case Diagram")

# Talon's Use Case Narrative
## Creation of Trip (Local Guide ver.)

<table style="float:left">
  <tr>
    <th align="left">Use Case Name</th><td>Create the trip</td>
  </tr>
  <tr>
    <th align="left">Goal in Context</th>
    <td>A local guide plan the trip by writing information about the destination and arrange the sequence of the trip</td>
  </tr>
  <tr>
    <th align="left">Primary Actor</th><td>Local Guide</td>
  </tr>
  <tr>
    <th align="left">Secondary Actor</th><td>Administrator</td>
  </tr>
  <tr>
    <th align="left">Precondition</th><td>The template for creating the destination and trip should be available.</td>
  </tr>
  <tr>
    <th align="left">Trigger</th>
    <td>Local guide would like to introduce local destination and recommend a trip for the tourist.</td>
  </tr>
  <tr>
    <th align="left">Scenario (Typical Flows of Events)</th>
    <td><ol>
      <li>Local guides click the button <code>create your own trip</code>.</li>
      <li>Local guides enter the details of the trip, which are trip date, details for destination, activity, and budge.t</li>
      <li>Local guides can start planning a trip by following steps<ol>
        <li>Local guides can add the details of destination including picture, description, essential information to the system.</li>
        <li>After adding destination, local guides can arrange the sequence of the trip.</li>
        <li>Finally, they can set the price and publish the trip to the system.</li>
      </ol></li>
    </ol></td>
  </tr>
  <tr>
    <th align="left">Exceptions</th>
    <td>
      <p><b>Exception 1:</b> If local guides do not have an account to log on, see use case register.</p>
      <p><b>Exception 2:</b> If the user name and password are incorrect, the system will prompt to local guides to retry to log on.</p>
      <p><b>Exception 3:</b> If the local guides have not created a profile, the system will prompt to local guides to complete the profile registration.</p>
      <p><b>Exception 4:</b> If the template is down, the system will be rolled back.</p>
    </td>
  </tr>
  <tr>
    <th align="left">Post - condition</th><td>Trip will be published to the system for the tourist to see.</td>
  </tr>
  <tr>
    <th align="left">Priority</th><td>To be implemented after basic functions</td>
  </tr>
  <tr>
    <th align="left">Channel to Actor</th><td>Via PC-based browser and Internet connection</td>
  </tr>
  <tr>
    <th align="left">Channel to secondary actor</th><td>PC-based system</td>
  </tr>
  <tr>
    <th align="left">Open Issues</th>
    <td>Is security sufficient? Hacking into this feature would represent a major invasion of privacy.</td>
  </tr>
</table>

## Creation of Trip (Tourist ver.)

<table style="float:left">
  <tr>
    <th align="left">Use Case Name</th><td>Create the trip</td>
  </tr>
  <tr>
    <th align="left">Goal in Context</th>
    <td>A tourist plan the trip by choosing the destination and sequence of the trip.</td>
  </tr>
  <tr>
    <th align="left">Primary Actor</th><td>Tourist</td>
  </tr>
  <tr>
    <th align="left">Secondary Actor</th><td>Administrator</td>
  </tr>
  <tr>
    <th align="left">Precondition</th>
    <td> <ol>
         <li> The template for creating the trip should be available.</li>
         <li> The data about destinations must be added to the system. </li>
    </ol></td>
  </tr>
  <tr>
    <th align="left">Trigger</th>
    <td>Tourists don't want to use the existing trip that was created by local guide and want to create their owntrip.</td>
  </tr>
  <tr>
    <th align="left">Scenario (Typical Flows of Events)</th>
    <td><ol>
      <li>Tourists subscribe the system and pay for the subscription.</li>
      <li>Tourists click the button <code>create your own trip</code></li>
      <li>Tourists enter the details of the trip, which are trip date, destination, activity, and budget.</li>
      <li>Tourists can start planning a trip by following steps</li>
        <ol type="a">
          <li>Tourist can search destination that already in the system if they don't have a destination in mind.</li>
          <li>After choosing the trip, tourists will add that place to the trip by clicking the button <code>add to the trip</code></li>
          <li>Tourist can add more details of destination such as time, activities, cautions.</li>
          <li>After tourists add all the destinations, they can arrange them sequentially.</li>
        </ol>
      <li>Tourists can add coraborative system by adding friend to join planning the trip.</li>
      <li>If tourists want more information, they can post questions on the forum and wait for the local guide to answer.</li>
      </ol></td>
  </tr>
  <tr>
    <th align="left">Exceptions</th>
    <td>
      <p><b>Exception 1:</b> If tourists do not have an account to log on, see use case register.</p>
      <p><b>Exception 2:</b> If the user name and password are incorrect, the system will prompt to tourist to retry to log on.</p>
      <p><b>Exception 3:</b> If the tourists have not subscribed before create the trip, the system will prompt to tourists to subscribe first.</p>
      <p><b>Exception 4:</b> If the template is down, the system will be rolled back.</p>
    </td>
  </tr>
  <tr>
    <th align="left">Post - condition</th><td>Trip will be created</td>
  </tr>
  <tr>
    <th align="left">Priority</th><td>To be implemented after basic functions</td>
  </tr>
  <tr>
    <th align="left">Channel to Actor</th><td>Via PC-based browser and Internet connection</td>
  </tr>
  <tr>
    <th align="left">Channel to Secondary Actor</th><td>PC-based system</td>
  </tr>
  <tr>
    <th align="left">Open Issues</th>
    <td>Is security sufficient? Hacking into this feature would represent a major invasion of privacy.</td>
  </tr>
</table>


# Talon's Functional Decomposition
![Functional Decomposition](https://github.com/ICT-Mahidol/2019-ITCS371-1-BackFromTianjin/blob/master/Images/functional%20decomposition.jpg "functional decomposition")


# Talon's Context Diagram
![context diagram](https://github.com/ICT-Mahidol/2019-ITCS371-1-BackFromTianjin/blob/master/Images/context%20diagram.jpg "Context Diagram")

# Talon's level 1 DFD
![level 1 DFD](https://github.com/ICT-Mahidol/2019-ITCS371-1-BackFromTianjin/blob/master/Images/DFD%20LV1.jpg "lvl 1 DFD")

# Talon's level 2 DFD
![level 2 DFD](https://github.com/ICT-Mahidol/2019-ITCS371-1-BackFromTianjin/blob/master/Images/DFD%20Level%202%20-%20Search%20Trip_new.jpeg "lvl 2 DFD search trip")

![level 2 DFD](https://github.com/ICT-Mahidol/2019-ITCS371-1-BackFromTianjin/blob/master/Images/DFD%20Level%202%20-%20Buy%20Trip_new.jpeg "lvl 2 DFD buy trip")

![level 2 DFD](https://github.com/ICT-Mahidol/2019-ITCS371-1-BackFromTianjin/blob/master/Images/DFD%20Level%202%20-%20Adjust%20the%20trip_new.jpeg "lvl 2 DFD adjust trip")
