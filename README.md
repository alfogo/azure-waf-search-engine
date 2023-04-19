# Azure WAF Search engine test site

Basic search engine developed for testing Azure WAF functionalities with Front Door or Application Gateway.

<img src="https://user-images.githubusercontent.com/8256455/232239487-a4b98fea-3c2b-4c3f-9853-cbeb5bb74be2.jpg" width="600" />

## Common attacks:

- ``` ' OR 1=1 ```
- ``` <script type="text/javascript"> anything </script> ```

### Instructions

1. Deploy web app to Azure App Service
1. Add an origin group to Azure Front Door pointing to the App Service
1. Test common attacks to see how Front Door offers detection and protection
