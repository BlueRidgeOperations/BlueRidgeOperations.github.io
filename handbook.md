<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
    document.addEventListener("adobe_dc_view_sdk.ready", function () {
        var adobeDCView = new AdobeDC.View({ clientId: "2b04cb01f3cc447a9120b2580b9ee13f", divId: "adobe-dc-view" });
        adobeDCView.previewFile({
            content: { location: { url: "Parent Student Handbook 2021-2022.pdf"} },
            metaData: { fileName: "Parent_Student_Handbook.pdf" }
        }, { embedMode: "SIZED_CONTAINER" });
    });
</script>