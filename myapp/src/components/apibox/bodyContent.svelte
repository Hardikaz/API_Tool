<script>
  import { Textarea } from 'flowbite-svelte';
  let textareaprops = {
    id: 'message',
    name: 'message',
    label: 'Your message',
    rows: 4,
    placeholder: `{
      "Sample":"sample",
      "contact_email":"xyz@gmail.com",
}`
  };
</script>

<p class="bodyContentHead">Body</p>
<Textarea {...textareaprops} />