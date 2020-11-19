# Overview

A simple package for breaking down the japanese address

# Instalation

        npm install japanese-prefecture-city
        or
        npm i japanese-prefecture-city

## examples

        const address = require("japanese-prefecture-city");
        const allAddress = "東京都相模原市南区";
        const addresses = address(allAddress);

        console.log(addresses);

        //{ prefecture: '東京都', city: '相模原市南区' }


# nuxtJs Project

        import japanesePrefectureCity from "japanese-prefecture-city";

        export default{
                mounted() {
                        var address = "東京都相模原市南区";
                        console.log(japanesePrefectureCity(address));
                }
        }

<br>
        
        { prefecture: '東京都', city: '相模原市南区' }

you can break down all 47 prefecture address by this package


# github

https://github.com/a-moksh/japanese-prefecture-city
