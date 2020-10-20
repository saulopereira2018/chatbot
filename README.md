# chatbot
<script>
  window.watsonAssistantChatOptions = {
      integrationID: "d9d1f8cf-5e57-4bad-ba90-1188c592c5a0", // The ID of this integration.
      region: "us-south", // The region your integration is hosted in.
      serviceInstanceID: "0b01a943-4807-4d34-b355-cd166fcdc4f9", // The ID of your service instance.
      onLoad: function(instance) { instance.render(); }
    };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/loadWatsonAssistantChat.js";
    document.head.appendChild(t);
  });
</script>
