### How to use your Twillio SMS API

<code>curl 'https://api.twilio.com/2010-04-01/Accounts/AC1a9702e6a727505d070433a6d7ae7dee/Messages.json' -X POST \
--data-urlencode 'To=+886928413007' \
--data-urlencode 'From=+12058803069' \
--data-urlencode 'Body=陈冠纶同学您好，恭喜您录取2020浙江大学计算机科学系，有关相关事宜，请联络港澳台招生网！' \
-u AC1a9702e6a727505d070433a6d7ae7dee:[AuthToken]
</code>


### You can use GET method to query history send messages
<code>curl 'https://api.twilio.com/2010-04-01/Accounts/AC1a9702e6a727505d070433a6d7ae7dee/Messages.json' -X GET \
-u AC1a9702e6a727505d070433a6d7ae7dee:[AuthToken]
</code>


