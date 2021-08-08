# Changes

## Released

### Features

- install helmet 3.21.3
- hide X-Powered-By header with helmet.hidePoweredBy()
- disable app framing with helmet.frameguard({ action: 'deny'})
- enable xssFilter with helmet.xssFilter()
- prevent browsers from bypassing the provided Content-Type helmet.noSniff()
- set X-Download-Options to noopen with helmet.ieNoOpen()
- set Strict Transport Security header with helmet.hsts()
- disable DNS prefetching with helmet.dnsPrefetchControl({allow: false})