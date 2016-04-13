#Big data analysis HW1 - Collect data
Using `Elasticsearch` + `logstash` and `TwitterAPI` to collect twitter's search result.
My keyword is `hello`
and this is one of the result
```js
{
    "_index": "twitter_hello",        # Elasticsearch store index
    "_type": "logs",
    "_id": "AVQKJo2bep7DICRoCRvo",
    "_version": 1,
    "_score": 1,
    "_source": {
        "created_at": "Tue Apr 12 11:06:18 +0000 2016",  # created date
        "id": 719844084769169400,
        "id_str": "719844084769169408",
        "text": "Hello to our new friends @FOODtoPLANT @PrysmDan @Security_Access @xysywefovyr @dennisrockman via https://t.co/rgi9xLgDgT",    # posting content and have keyword `hello`
        "source": "<a href="https://statusbrew.com" rel="nofollow">Statusbrew</a>",
        "truncated": false,
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 3390669917,
            "id_str": "3390669917",
            "name": "StartingPPCFPB",    # User name
            "screen_name": "StartingPPCFPB",
            "location": "UK",  # User location
            "url": "http://www.gettingstartedwithppc.com/ppc1-sme/guides/",
            "description": "Heard about Pay Per Click Marketing but not sure where to start. Download our FREE Guide and find out. http://bit.ly/1BwYVp9",
            "protected": false,
            "verified": false,
            "followers_count": 1130,    # followers number
            "friends_count": 1391,      # friends number
            "listed_count": 5,
            "favourites_count": 0,
            "statuses_count": 726,
            "created_at": "Fri Jul 24 08:36:19 +0000 2015",     # sign up date
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "lang": "en-gb",    # using language
            "contributors_enabled": false,
            "is_translator": false,
            # profile setting
            "profile_background_color": "C0DEED",
            "profile_background_image_url": "http://abs.twimg.com/images/themes/theme1/bg.png",
            "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme1/bg.png",
            "profile_background_tile": false,
            "profile_link_color": "0084B4",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "profile_image_url": "http://pbs.twimg.com/profile_images/624502382383206400/1vhgjQe4_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/624502382383206400/1vhgjQe4_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/3390669917/1437728010",
            "default_profile": true,
            "default_profile_image": false,
            "following": null,
            "follow_request_sent": null,
            "notifications": null
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 0,
        "favorite_count": 0,
        "entities": {
            "hashtags": [ ],
            "urls": [
                {
                    "url": "https://t.co/rgi9xLgDgT",
                    "expanded_url": "https://Statusbrew.com?r=wl",
                    "display_url": "Statusbrew.com/?r=wl",
                    "indices": [
                        97
                        ,
                        120
                    ]
                }
            ],
            "user_mentions": [
                {
                    "screen_name": "FOODtoPLANT",
                    "name": "FOOD to PLANT",
                    "id": 3198301603,
                    "id_str": "3198301603",
                    "indices": [
                        25
                        ,
                        37
                    ]
                }
                ,
                {
                    "screen_name": "PrysmDan",
                    "name": "Dan Trimble",
                    "id": 3247983773,
                    "id_str": "3247983773",
                    "indices": [
                        38
                        ,
                        47
                    ]
                }
                ,
                {
                    "screen_name": "Security_Access",
                    "name": "Security Access",
                    "id": 125463840,
                    "id_str": "125463840",
                    "indices": [
                        48
                        ,
                        64
                    ]
                }
                ,
                {
                    "screen_name": "xysywefovyr",
                    "name": "Qubad Bray",
                    "id": 2163904423,
                    "id_str": "2163904423",
                    "indices": [
                        65
                        ,
                        77
                    ]
                }
                ,
                {
                    "screen_name": "dennisrockman",
                    "name": "dennisrockman",
                    "id": 4496601404,
                    "id_str": "4496601404",
                    "indices": [
                        78
                        ,
                        92
                    ]
                }
            ],
            "symbols": [ ]
        },
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "filter_level": "low",
        "lang": "en",
        "timestamp_ms": "1460459178522",
        "@version": "1",
        "@timestamp": "2016-04-12T11:06:18.000Z"
    }

}
```
