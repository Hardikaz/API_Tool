<script>
  import { Textarea, Label } from 'flowbite-svelte';
  let text=`{
    "Sample":"sample",
    "contact_email":"xyz@gmail.com";
}`;
</script>

<Label for="textarea-id" class="mb-2 respHead">Response</Label>
<Textarea id="textarea-id" placeholder={text} rows="4" name="message" />