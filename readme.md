# Overview

A simple package for breaking down the japanese address

# Instalation

        npm install japanese-prefecture-city

## examples

        const address = require("japanese-prefecture-city");
        const allAddress = "東京都相模原市南区";
        const addresses = poo(allAddress);

        console.log(addresses);

        //{ prefecture: '東京都', city: '相模原市南区' }

you can break down all 46 prefecture address by this package
