# search-index-service-worker
Plain JavaScript attempt on running search-index through a service worker. As a PWA. Search-index as backend, service worker as the middleware. Easy access through `fetch(./?[search-index-function]={data object})`-endpoints

## Use

* Add as dependency
* `import { sidx-sw } from 'sidx.sw'`
* Set up listening for fetch(./?)-events
