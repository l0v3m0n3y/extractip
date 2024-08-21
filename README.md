# extractip
JavaScript library for extractip.com
# main
```js
async function main(){
    const {extractip} = require('./extractip');
    const extract= new extractip();
    let req=await extract.my_geolocate()
    console.log(req)
}
main()
```
