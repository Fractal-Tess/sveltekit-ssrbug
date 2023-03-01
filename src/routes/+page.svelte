<script>
  import { browser } from '$app/environment';
  import 'vidstack/define/media-player.js';
  if (!browser) console.log('SSR');
  else console.log('CSR');
</script>

<div>
  The vidstack import should NOT be able to render on the dev server because it
  uses the document object
</div>
