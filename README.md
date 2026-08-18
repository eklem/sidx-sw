# search-worker-server

Trying to be the browser version of [Norch](https://github.com/fergiemcdowall/norch/). Plain JavaScript attempt on running search-index through a service worker. As a PWA. Search-index as backend, service worker as the middleware. Easy access through `fetch(./?[search-index-function]={data object})`-endpoints.

## Use

* Add as dependency (
* `import { SearchIndex } from 'search-index'`
* `import { borch } from 'borch'`
* Set up listening for fetch(./?)-events
