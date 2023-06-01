<script>
  import "../app.css";
  import { Client } from 'appwrite';

  const client = new Client();

  client
    .setEndpoint('https://cloud.appwrite.io/v1')
    .setProject('6478ebe17706254309ad');
</script>
  
<slot />