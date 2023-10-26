<script>
import { Label, Input } from 'flowbite-svelte';
import { Button } from 'flowbite-svelte';
import { Dropdown, DropdownItem, DropdownDivider, DropdownHeader } from 'flowbite-svelte';
import { ChevronDownSolid } from 'flowbite-svelte-icons';
    
</script>

<div class="inputBox">

<Button>Dropdown button<ChevronDownSolid class="w-3 h-3 ml-2 text-white dark:text-white" /></Button>

<Dropdown>
  <DropdownItem>Dashboard</DropdownItem>
  <DropdownItem>Settings</DropdownItem>
  <DropdownItem>Earnings</DropdownItem>
  <DropdownItem>Sign out</DropdownItem>
</Dropdown>

<div class="mb-6">
  <Label for="default-input" class="block mb-2">Default input</Label>
  <Input id="default-input" placeholder="Default input" />
 
</div>

<Button color="green" type="Submit" pill>Send</Button> 


</div>