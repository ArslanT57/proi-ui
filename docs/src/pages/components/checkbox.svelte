<script>
  import { Checkbox } from '.../../../../src';
  import Docs from '../../components/Docs.svelte';
  import { config } from '../../configs/components/checkbox';

  let checked = true;
</script>

<Docs {config}>
  <Checkbox bind:checked>{checked ? 'Checked' : 'Unchecked'}</Checkbox>
  <Checkbox checked={true} disabled>Checked disabled</Checkbox>
  <Checkbox checked={false} disabled>Unchecked disabled</Checkbox>
</Docs>