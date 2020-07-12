const Fibery = require('fibery-unofficial');
const fibery = new Fibery({host: "darix.fibery.io", token: 1ac4af05.893e69e84418af1f8c9b31bb534ae9b2dc5});

const users = await fibery.entity.query({
    "q/from": "fibery/user",
    "q/select": ["fibery/id","user/name"],
    "q/limit": 1
});
