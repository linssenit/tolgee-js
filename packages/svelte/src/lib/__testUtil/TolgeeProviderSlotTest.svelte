<script lang="ts">
  import type { TolgeeInstance } from '@tolgee/web';
  import { TolgeeProvider } from '$lib';

  export let tolgee: TolgeeInstance;
</script>

<TolgeeProvider {tolgee}>
  <div slot="fallback">loading</div>
  <div slot="default">It's rendered!</div>
</TolgeeProvider>
