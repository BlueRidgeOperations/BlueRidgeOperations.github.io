<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en-us" lang="en-us">

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title>Handbook</title><meta name="author" content="Cathleen Hernandez"/>
<style>
        h1 { 
            color: black; 
            font-family: Calibri, sans-serif;
            font-style: normal; 
            font-weight: bold; 
            text-decoration: none; 
            font-size: 100%;
            text-align: center;
             }

        .p, p { 
            color: black; 
            font-family: Calibri, sans-serif; 
            font-style: normal; 
            font-weight: normal; 
            text-decoration: none; 
            font-size: 100%; 
            margin:0pt; 
            }
            
        .student {
            display: flex;
            flex-direction: row;
            font-family: Calibri, sans-serif;
        }
        input {
            width: 45%;
            height: 25px;
            font-family: Calibri, sans-serif;
            margin: auto;
        }
        
        #date {
            text-align: right;  
            padding-right: 8px;
            padding-left: 10px;
            width: auto;
            }
                    
        #content {
            justify-content: center;
            align-items: center;
            height: 100%;
            width: 90%;
            background-color: #FCFFFF;
            Margin: 0 auto;
            padding-top: 0%;
            padding-left: 5%;
            padding-right: 5%;
            padding-bottom: 3%;
        }

</style>
</head>
<body>
<div id="content">
<h1>Please review and sign the Parent Student Handbook below</h1>
<div id="adobe-dc-view" style="height: 800px; width: 800px;"></div>
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
<p>By signing, you are agreeing to the policies and procedures of the Parent Student Handbook including but not limited to:</p>
<ul>
    <li>Enrollment Requirements</li>
    <li>Academic Expectations</li>
    <li>Report Card & Grading</li>
    <li>Attendance</li>
    <li>Non-Compliance</li>
    <li>Work Samples</li>
    <li>Technology Usage</li>
    <li>Testing & Assessments</li>
    <li>Behavioral Expectations</li>
    <li>Instructional Funding</li>
    <li>Academy Integrity</li>
    </ul>
<br>
    <form class="student">
        <label for="sname">Student Name:</label>
        <input type="text" id="sname" name="sname"><br>
        <label for="date">Date:</label>
        <input type="text" id="date" name="date">
    </form>
</div>
    </body>