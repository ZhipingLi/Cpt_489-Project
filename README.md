# CptS 489 Team Project: *Team Name*
This repository implements SpeedScore, a web app that enables users to log, analyze, share, and discuss their speedgolf rounds and experiences. SpeedScore is built using MongoDB, Express.js, React.js, and Node.js.

## Link to Deployed App
You can access our team's deployed app at [this Heroku site](https://go-lakers123123.herokuapp.com/)

## Team members
1. **Team leader:** *Jianqiao Liu (Jianqiao-WSU)*
1. *Team member 2 Wen-Chih Li (Jimmy-WSU)*
1. *Team member 3 Guang-Zheng Lee (zheng0258)*
1. *Team member 4 Zicheng Gu (gzcccc1)*
1. *Team member 5 Zhiping Li (ZhipingLi)*

## Milestone 0 (Due 11/19)

### Progress
#### Issues and Story Points
<table> 
  <thead>
    <tr>
      <th colspan="2"></th><th colspan="6">Story Point Counts</th><th colspan="2"></th>
    </tr> 
    <tr>
      <th>Issue</th><th>Linked PR</th><th>Total</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th><th>% Complete</th><th>Notes</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td><a href="https://github.com/issue">Issue #</a></td><td><a href="https://github.com/PR">PR #</a></td><td>5</td><td>3</td><td>1</td><td>1</td><td>0</td><td>0</td><td>100</td><td></td>
    </tr>
    <tr>
     <td><a href="https://github.com/issue">Issue #</a></td><td><a href="https://github.com/PR">PR #</a></td><td>3</td><td>0</td><td>0</td><td>0</td><td>0.8</td><td>0.4</td><td>40</td><td>Updated database schema. Updated server routes. Did not implement UI.</td>
    </tr>
    <tr><td colspan="2" align="right"><b>Totals:</b></td><td><b>8</b></td><td><b>3</b></td><td><b>1</b></td><td><b>1</b></td><td><b>0.8</b></td><td><b>0.4</b></td><td colspan="2"></td>
    </tr>
  </tbody>
</table>

#### Context Statements
| Team Member | Context Statement |
|-------------|-------------------|
|Jianqiao Liu| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Wen-Chih Li| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Guang-Zheng Lee| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Zicheng Gu| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Zhiping Li| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |

### Testing

|Issue | Test File | Feature Tested | Results Summary | 
|------|-----------|----------------|-----------------|
|[Issue #5](https://github.com/wsu-cpts489-fa21/tp-go-lakers/projects/2#card-72740989)| [profileSettings.js](https://github.com/wsu-cpts489-fa21/tp-go-lakers/blob/78b377195960e2b75244aec84d96f0891315e5a1/tests/ProfileSettings/profileSettings.js)|Profile Settings| [3/3 tests passed](https://github.com/wsu-cpts489-fa21/tp-go-lakers/blob/78b377195960e2b75244aec84d96f0891315e5a1/tests/ProfileSettings/testcafe%20test.gif) | [
|[Issue #6](https://github.com/wsu-cpts489-fa21/tp-go-lakers/projects/2#card-72740987)| [delete.js](https://github.com/wsu-cpts489-fa21/tp-go-lakers/blob/78b377195960e2b75244aec84d96f0891315e5a1/tests/DeleteRoundsTests/delete.js)|DELETE rounds | [1/1 tests passed](https://github.com/wsu-cpts489-fa21/tp-go-lakers/blob/78b377195960e2b75244aec84d96f0891315e5a1/tests/DeleteRoundsTests/testcafe%20test.gif) |
|[Issue #7](https://github.com/wsu-cpts489-fa21/tp-go-lakers/projects/2#card-72740982)| [updateRoundsTest.js](https://github.com/wsu-cpts489-fa21/tp-go-lakers/blob/78b377195960e2b75244aec84d96f0891315e5a1/tests/UpdateRoundsTests/UpdateRoundsTest.js)|UPDATE rounds | [1/1 tests passed](https://github.com/wsu-cpts489-fa21/tp-go-lakers/blob/f1f68584ac5a1c10b34d0acee6de0e6b693036de/tests/UpdateRoundsTests/UpdateRoundsTest.gif) |
  
### Communication
 
#### Slack Messages
<table> 
  <thead>
    <tr>
      <th></th><th colspan="6">Post/Reply Counts</th>
    </tr> 
    <tr>
      <th>Date</th><th>Total</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td>11/10/21</td><td>2</td><td>0</td><td>1</td><td>1</td><td>0</td><td>0</td>
    </tr>
    <tr>
     <td>11/12/21</td><td>1</td><td>0</td><td>1</td><td>0</td><td>0</td><td>0</td>
    </tr>
    <tr>
     <td>11/15/21</td><td>20</td><td>1</td><td>10</td><td>5</td><td>1</td><td>3</td>
    </tr>
    <tr>
     <td>11/16/21</td><td>9</td><td>4</td><td>0</td><td>0</td><td>2</td><td>3</td>
    </tr>
    <tr>
     <td>11/17/21</td><td>5</td><td>0</td><td>3</td><td>1</td><td>1</td><td>0</td>
    </tr>
    <tr>
     <td>11/17/21</td><td>2</td><td>1</td><td>0</td><td>1</td><td>0</td><td>0</td>
    </tr>
    <tr><td align="right"><b>Totals:</b></td><td><b>39</b></td><td><b>6</b></td><td><b>15</b></td><td><b>9</b></td><td><b>4</b></td><td><b>6</b></td>
    </tr>
  </tbody>
</table>

#### Zoom Meetings
<table> 
  <thead>
    <tr>
      <th colspan="2"></th><th colspan="5">In attendance?</th>
    </tr> 
    <tr>
      <th>Date</th><th>Duration (min)</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td>11/15/21</td><td>7</td><td>&check;</td><td>&check;</td><td>&check;</td><td></td><td>&check;</td>
    </tr>
    <tr>
      <td>11/17/21</td><td>9</td><td>&check;</td><td>&check;</td><td>&check;</td>&check;<td>&check;</td><td>&check;</td>
    </tr>
    <tr><td align="right"><b>Totals:</b></td><td><b>16</b></td><td><b>2</b></td><td><b>2</b></td><td><b>2</b></td><td><b>1</b></td><td><b>2</b></td>
    </tr>
  </tbody>
</table>
  


#### Context Statements
| Team Member | Context Statement |
|-------------|-------------------|
|Jianqiao Liu| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Wen-Chih Li| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Guang-Zheng Lee| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Zicheng Gu| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Zhiping Li| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |

### Retrospective
[11/15/2021](https://drive.google.com/file/d/1qyPbl5Z8MhrwLcovys6oPZXovPbFZxbn/view?usp=sharing)
[11/17/2021](https://drive.google.com/file/d/1Mnyb7-d4S5b2lyS94KciQGZ4KxA3B6-y/view?usp=sharing)


#### What went well
  - Item 1
  - Item 2
  - Item x
  
 #### What we'd like to improve
  - Item 1
  - Item 2
  - Item x
  
#### Changes we plan to implement in next milestone period
  - Item 1
  - Item 2
  - Item x

## Milestone 1 (Due 12/3)

### Progress
#### Issues and Story Points
<table> 
  <thead>
    <tr>
      <th colspan="2"></th><th colspan="6">Story Point Counts</th><th colspan="2"></th>
    </tr> 
    <tr>
      <th>Issue</th><th>Linked PR</th><th>Total</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th><th>% Complete</th><th>Notes</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td><a href="https://github.com/issue">Issue #</a></td><td><a href="https://github.com/PR">PR #</a></td><td>5</td><td>3</td><td>1</td><td>1</td><td>0</td><td>0</td><td>100</td><td></td>
    </tr>
    <tr>
     <td><a href="https://github.com/issue">Issue #</a></td><td><a href="https://github.com/PR">PR #</a></td><td>3</td><td>0</td><td>0</td><td>0</td><td>0.8</td><td>0.4</td><td>40</td><td>Updated database schema. Updated server routes. Did not implement UI.</td>
    </tr>
    <tr><td colspan="2" align="right"><b>Totals:</b></td><td><b>8</b></td><td><b>3</b></td><td><b>1</b></td><td><b>1</b></td><td><b>0.8</b></td><td><b>0.4</b></td><td colspan="2"></td>
    </tr>
  </tbody>
</table>

#### Context Statements
| Team Member | Context Statement |
|-------------|-------------------|
|Jianqiao Liu| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Wen-Chih Li| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Guang-Zheng Lee| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Zicheng Gu| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Zhiping Li| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |

### Testing

|Issue | Test File | Feature Tested | Results Summary | 
|------|-----------|----------------|-----------------|
|[Issue #](https://github.com/issue)| [Google.js](https://www.github.com/)|Google Authentication| [3/3 tests passed](https://yoursite.com/animated.gif) | [
|[Issue #](https://github.com/issue)| [routes.js](https://www.github.com/)|PUT and DELETE routes for rounds | [15/15 tests passed](https://yoursite.com/animated.gif) |
  
### Communication
 
#### Slack Messages
<table> 
  <thead>
    <tr>
      <th></th><th colspan="6">Post/Reply Counts</th>
    </tr> 
    <tr>
      <th>Date</th><th>Total</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td>11/9/21</td><td>5</td><td>2</td><td>1</td><td>1</td><td>1</td><td>0</td>
    </tr>
    <tr>
     <td>11/12/21</td><td>4</td><td>1</td><td>1</td><td>0</td><td>0</td><td>1</td>
    </tr>
    <tr><td align="right"><b>Totals:</b></td><td><b>9</b></td><td><b>3</b></td><td><b>2</b></td><td><b>1</b></td><td><b>1</b></td><td><b>1</b></td>
    </tr>
  </tbody>
</table>

#### Zoom Meetings
<table> 
  <thead>
    <tr>
      <th colspan="2"></th><th colspan="5">In attendance?</th>
    </tr> 
    <tr>
      <th>Date</th><th>Duration (min)</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td>11/9/21</td><td>17</td><td>&check;</td><td>&check;</td><td></td><td>&check;</td><td>&check;</td>
    </tr>
     <tr>
      <td>11/12/21</td><td>31</td><td>&check;</td><td>&check;</td><td></td><td></td><td>&check;</td>
    </tr>
    <tr><td align="right"><b>Totals:</b></td><td><b>48</b></td><td><b>2</b></td><td><b>2</b></td><td><b>0</b></td><td><b>1</b></td><td><b>2</b></td>
    </tr>
  </tbody>
</table>
  
#### Face-to-Face Meetings
<table> 
  <thead>
    <tr>
      <th colspan="2"></th><th colspan="5">In attendance?</th><th></th>
    </tr> 
    <tr>
      <th>Date</th><th>Duration (min)</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th><th>Notes</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td>11/10/21</td><td>45</td><td>&check;</td><td>&check;</td><td></td><td>&check;</td><td>&check;</td><td>We met in CUB conference room</td>
    </tr>
     <tr>
      <td>11/14/21</td><td>20</td><td>&check;</td><td>&check;</td><td></td><td></td><td>&check;</td><td>We met at Starbucks for coffee</td>
    </tr>
    <tr><td align="right"><b>Totals:</b></td><td><b>65</b></td><td><b>2</b></td><td><b>2</b></td><td><b>0</b></td><td><b>1</b></td><td><b>2</b></td><td></td>
    </tr>
  </tbody>
</table>

#### Context Statements
| Team Member | Context Statement |
|-------------|-------------------|
|Jianqiao Liu| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Wen-Chih Li| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Guang-Zheng Lee| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Zicheng Gu| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Zhiping Li| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |

### Retrospective

[Link to Recording](https://wsu.zoom.us/recording)

#### What went well
  - Item 1
  - Item 2
  - Item x
  
 #### What we'd like to improve
  - Item 1
  - Item 2
  - Item x
  
#### Changes we plan to implement in next milestone period
  - Item 1
  - Item 2
  - Item x
  
## Milestone 2 (Due 12/10)

### Progress
#### Issues and Story Points
<table> 
  <thead>
    <tr>
      <th colspan="2"></th><th colspan="6">Story Point Counts</th><th colspan="2"></th>
    </tr> 
    <tr>
      <th>Issue</th><th>Linked PR</th><th>Total</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th><th>% Complete</th><th>Notes</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td><a href="https://github.com/issue">Issue #</a></td><td><a href="https://github.com/PR">PR #</a></td><td>5</td><td>3</td><td>1</td><td>1</td><td>0</td><td>0</td><td>100</td><td></td>
    </tr>
    <tr>
     <td><a href="https://github.com/issue">Issue #</a></td><td><a href="https://github.com/PR">PR #</a></td><td>3</td><td>0</td><td>0</td><td>0</td><td>0.8</td><td>0.4</td><td>40</td><td>Updated database schema. Updated server routes. Did not implement UI.</td>
    </tr>
    <tr><td colspan="2" align="right"><b>Totals:</b></td><td><b>8</b></td><td><b>3</b></td><td><b>1</b></td><td><b>1</b></td><td><b>0.8</b></td><td><b>0.4</b></td><td colspan="2"></td>
    </tr>
  </tbody>
</table>

#### Context Statements
| Team Member | Context Statement |
|-------------|-------------------|
|Jianqiao Liu| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Wen-Chih Li| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Guang-Zheng Lee| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Zicheng Gu| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |
|Zhiping Li| <*Optional but encouraged*: Brief statement explaining your contribution to this milestone> |

### Testing

|Issue | Test File | Feature Tested | Results Summary | 
|------|-----------|----------------|-----------------|
|[Issue #](https://github.com/issue)| [Google.js](https://www.github.com/)|Google Authentication| [3/3 tests passed](https://yoursite.com/animated.gif) | [
|[Issue #](https://github.com/issue)| [routes.js](https://www.github.com/)|PUT and DELETE routes for rounds | [15/15 tests passed](https://yoursite.com/animated.gif) |
  
### Communication
 
#### Slack Messages
<table> 
  <thead>
    <tr>
      <th></th><th colspan="6">Post/Reply Counts</th>
    </tr> 
    <tr>
      <th>Date</th><th>Total</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td>11/9/21</td><td>5</td><td>2</td><td>1</td><td>1</td><td>1</td><td>0</td>
    </tr>
    <tr>
     <td>11/12/21</td><td>4</td><td>1</td><td>1</td><td>0</td><td>0</td><td>1</td>
    </tr>
    <tr><td align="right"><b>Totals:</b></td><td><b>9</b></td><td><b>3</b></td><td><b>2</b></td><td><b>1</b></td><td><b>1</b></td><td><b>1</b></td>
    </tr>
  </tbody>
</table>

#### Zoom Meetings
<table> 
  <thead>
    <tr>
      <th colspan="2"></th><th colspan="5">In attendance?</th>
    </tr> 
    <tr>
      <th>Date</th><th>Duration (min)</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td>11/9/21</td><td>17</td><td>&check;</td><td>&check;</td><td></td><td>&check;</td><td>&check;</td>
    </tr>
     <tr>
      <td>11/12/21</td><td>31</td><td>&check;</td><td>&check;</td><td></td><td></td><td>&check;</td>
    </tr>
    <tr><td align="right"><b>Totals:</b></td><td><b>48</b></td><td><b>2</b></td><td><b>2</b></td><td><b>0</b></td><td><b>1</b></td><td><b>2</b></td>
    </tr>
  </tbody>
</table>
  
#### Face-to-Face Meetings
<table> 
  <thead>
    <tr>
      <th colspan="2"></th><th colspan="5">In attendance?</th><th></th>
    </tr> 
    <tr>
      <th>Date</th><th>Duration (min)</th><th>Jianqiao Liu</th><th>Wen-Chih Li</th><th>Guang-Zheng Lee</th><th>Zicheng Gu</th><th>Zhiping Li</th><th>Notes</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td>11/10/21</td><td>45</td><td>&check;</td><td>&check;</td><td></td><td>&check;</td><td>&check;</td><td>We met in CUB conference room</td>
    </tr>
     <tr>
      <td>11/14/21</td><td>20</td><td>&check;</td><td>&check;</td><td></td><td></td><td>&check;</td><td>We met at Starbucks for coffee</td>
    </tr>
    <tr><td align="right"><b>Totals:</b></td><td><b>65</b></td><td><b>2</b></td><td><b>2</b></td><td><b>0</b></td><td><b>1</b></td><td><b>2</b></td><td></td>
    </tr>
  </tbody>
</table>

#### Context Statements
| Team Member | Context Statement |
|-------------|-------------------|
|Jianqiao Liu| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Wen-Chih Li| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Guang-Zheng Lee| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Zicheng Gu| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |
|Zhiping Li| <*Optional but encouraged*: Brief statement explaining your communication to this milestone> |

### Retrospective

[Link to Recording](https://wsu.zoom.us/recording)

#### What went well
  - Item 1
  - Item 2
  - Item x
  
 #### What we'd like to improve
  - Item 1
  - Item 2
  - Item x
  
#### Changes we plan to implement in next milestone period
  - Item 1
  - Item 2
  - Item x
