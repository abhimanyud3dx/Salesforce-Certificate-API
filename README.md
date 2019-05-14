# SuperQbit - Salesforce Certificate Unofficial API

Get Realtime salesforce certification information of you and your team.

## Salesforce Certificate Public API and UI ScoreCard
Salesforce Certificate and JSON data

Follow the steps mention in this blog http://superqbit.com/2019/03/25/salesforce-certification-custom-api-and-ui-card/ to get the certificateID

use the following URL for Salesforce Trailhead Public API data
```
https://api-superqbit.herokuapp.com/salesforce/certificateJSON/{certificateID}
```

use the following URL for Score Card
```
https://api-superqbit.herokuapp.com/salesforce/certificate/{certificateID}
```


To get embed the scorecard in your own website
```
<iframe src="https://api-superqbit.herokuapp.com/salesforce/certificate/{certificateID}" style="border:none;overflow:hidden;" width="100%" height="350px" scrolling="no"></iframe>
```
