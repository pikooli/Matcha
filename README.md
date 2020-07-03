<p align="center"><strong>Matcha</strong></p><br/>
<p align="center"><strong>*******IN PRODUCTION, NOT FINISH *******<strong></p><br/>

<p>Matcha is the dating website of the school 42.<br/><br/>
  We did it with react for the front and nodejs with express for the back<br/>
  The whole project have to be secure again SQL injection and XSS injections.<br/>
  It should have the following system: <br/>
  - Like a user<br/>
  - Message a user<br/>
  - See the profile of a user<br/>
  - Edit the profile<br/>
  - Block a user<br/>
  - Report a user<br/>
  - Notification for specific action<br/><br/>
  To launch this app you will need to use docker with docker-compose. <br/>
  If everything is installed, you can just do a "sh start.sh" or follow the setup guide
</p>
<img src="loginPage.png" width="400" heigth="500"/>
<img src="searchPage.png" width="400" heigth="500"/>
<img src="Profile.png" width="400" heigth="500"/>

## SETUP
- `$> docker-compose -f docker-compose.build.yaml up`
- `$> docker-compose -f docker-compose.seed.yaml up --abort-on-container-exit`

## LAUNCH
- `$> docker-compose up`
