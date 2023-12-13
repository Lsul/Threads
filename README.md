<div style="width: 100%; height: 100%;" id="VG_OVERLAY_CONTAINER">
<!-- Here is where Voiceglow renders the widget. -->
<!-- Set width, height for 500px as an example after changing render to 'full-width' -->
</div>

<!-- Remove 'defer' if you want widget to load faster (Will affect website loading) -->
<script defer>
(() => {
document.querySelector('html').style.fontSize = "16px"; // 16px is the default value, this is needed now for fully eliminating spacing issues.
window.VG_CONFIG = {
    ID: "aq6s4kylh",
    region: 'na', // 'eu' or 'na'corresponding to Europe and North America
    render: 'full-width', // popup or full-width
    stylesheets: [
        // Base Voiceglow CSS
        "https://storage.googleapis.com/speakwiz-app.appspot.com/vg_live_build/styles.css",
        // Add your custom css stylesheets, Can also add relative URL ('/public/your-file.css)
    ],
    // userID: 'USER_ID', // If you want to use your own user_id
    // autostart: true, // Whether to autostart the chatbot with the proactive message
}
var VG_SCRIPT = document.createElement("script");
VG_SCRIPT.src = "https://storage.googleapis.com/speakwiz-app.appspot.com/vg_live_build/vg_bundle.js";
document.body.appendChild(VG_SCRIPT);
})()
</script>
