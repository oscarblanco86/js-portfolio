# js-portfolio

Variable de entorno en uso:
 API=https://randomuser.me/api/



Clase 20 webpack bundle analyzer

npm install webpack-bundle-analyzer -D

webpack dev

                Consts:
                const BundleAnalyzerPlugin = require('webpack-bundle-analyzer');


                Plugins: 
                new BundleAnalyzerPlugin(),


npx webpack --profile --json > stats
npx webpack-bundle-analyzer