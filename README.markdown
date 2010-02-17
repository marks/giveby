Give By ["Phone","Text","IM"]
=============================
A charity example by @Skram and @Tropo for GlobalGiving.org
-----------------------------------------------------------
This application is an open source sample of how you can use Tropo's WebAPI to voice/text/IM-enable any web service. In this case, I have decided to create an application to allow donors and potential donors to look up and donate to charities through GlobalGiving's new API.

Don't forget your ./config.yaml !
-----------------------------
In the application's root directory, create a file with:

	---
	globalgiving:
	  api:
	    url: https://api.globalgiving.org/api
	    key: YOUR_API_KEY
	  user:
	    id: YOUR_GLOBAL_GIVING_EMAIL
	    password: YOUR_GLOBAL_GIVING_PASSWORD
	  test:
	    giftcard: OPTIONAL_GIFT_CARD_FOR_TESTING
