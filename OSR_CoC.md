

<div id="adobe-dc-view" style="height: 360px; width: 500px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
  document.addEventListener("adobe_dc_view_sdk.ready", function(){
    var adobeDCView = new AdobeDC.View({clientId: "<YOUR_CLIENT_ID>", divId: "adobe-dc-view"});
    adobeDCView.previewFile({
      content:{ location: 
        { url: "https://github.com/ohbm/osr2021/blob/main/OSR_code_of_conduct.pdf"}},
      metaData:{fileName: "OSR Code of Conduct.pdf"}
    },
    {
      embedMode: "SIZED_CONTAINER"
    });
  });
</script>
