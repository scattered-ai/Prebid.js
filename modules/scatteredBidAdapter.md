# Overview

```
Module Name: Scattered Adapter
Module Type: Bidder Adapter
Maintainer: prebid@scattered.pl
```

# Description

Module that connects to Scattered's demand sources. 
It uses OpenRTB standard to communicate between the adapter and bidding servers.

# Test Parameters

```javascript
    var adUnits = [
        {
            code: 'test-div',
            mediaTypes: {
                banner: {
                    sizes: [[300, 250]],  // a display size
                }
            },
            bids: [
                {
                    bidder: "scattered",
                    params: {
                        bidderDomain: "https://"
                        test: 0
                    }
                }
            ]
        }
    ];
```