# Platforms

|Problem|Solution|
|---|---|
|Proramming Language|Go|
|Database|Postgres|
|Cache|Redis|

# Entities

* User

|Attribute|Type|More|
|---|---|---|
|User ID|64 bit||
|Username|50 ascii char||
|Join Date|time||
|Last Seen|time||
|Phone Number|15 ascii char||


* Chat

|Attribute|Type|More|
|---|---|---|
|Chat ID|64 bit||

* Messages

|Attribute|Type|More|
|---|---|---|
|Message ID|64 bit||
|Chat ID|64 bit||
|Sender ID|64 bit||
|Reply To|64 bit||
|Send Time|time||
|Receive Time|time||
|Read Time|time||
|Text|4096 unicode char||
