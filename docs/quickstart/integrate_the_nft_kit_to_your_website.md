
Now that your NFT Kit is ready, you can start using it in your own website.

The steps are easy and straightforward:

### Import the integration script in the html code

All you have to do is to add this line in your html file:

```
<script src="[YOUR-INTEGRATION-SCRIPT-URL]"></script>
```

#### Remark

In case you are using the integration script to test the integration locally or via an http access, use http to call the integration script, example:
```
<script src="http://www.3563188.0x72ddbdc341bbfc00fe.4.my-nft.io/static/nft-integration.js"></script>
```

In case you are using it vi https, which is  generally the case in production, use https to call teh script, example:
```
<script src="https://www.3563188.0x72ddbdc341bbfc00fe.4.my-nft.io/static/nft-integration.js"></script>
```

Once integrated you well have access to a set of javascript methods to use NFT features.

A detailed documentation on the available methods is provided in the section "Documentation/The NFT ENV"
