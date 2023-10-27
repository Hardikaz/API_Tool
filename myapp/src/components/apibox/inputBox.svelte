<script>
import { Label, Input } from 'flowbite-svelte';
import { Button } from 'flowbite-svelte';
import { Dropdown, DropdownItem, DropdownDivider, DropdownHeader } from 'flowbite-svelte';
import { ChevronDownSolid } from 'flowbite-svelte-icons';
    
</script>

<div class="inputBox">


<Button class="dropDownBtn">GET <ChevronDownSolid class="w-3 h-3 ml-2 text-white dark:text-white" /></Button>

<Dropdown class="dropDown">
  <DropdownItem>GET</DropdownItem>
  <DropdownItem>POST</DropdownItem>
  <DropdownItem>PUT</DropdownItem>
  <DropdownItem>DELETE</DropdownItem>
  <DropdownItem>HEAD</DropdownItem>
</Dropdown>

<div class="mb-6">
 
  <Input id="default-input" class="inp" placeholder="https://api.challenge.hennge.com/challenges/003" />
 
</div>

<Button color="green" class="sendBtn" type="Submit" pill>Send</Button> 


</div>