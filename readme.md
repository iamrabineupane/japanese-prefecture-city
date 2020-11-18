# a simple package for breaking down the japanese address

        npm install japanese-prefecture-city

## examples

        const address = require("japanese-prefecture-city");
        const allAddress = "東京都相模原市南区";
        const addresses = poo(allAddress);

        console.log(addresses);

you can break down all 46 prefecture address by this package