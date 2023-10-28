<script>
import { Label, Input } from 'flowbite-svelte';
import { Button } from 'flowbite-svelte';
import { Dropdown, DropdownItem, DropdownDivider, DropdownHeader } from 'flowbite-svelte';
import { ChevronDownSolid } from 'flowbite-svelte-icons';
    
let method="GET";

function handleClick(event){
  method=event.target.value
}
</script>

<div class="inputBox">


<Button class="dropDownBtn">{method}<ChevronDownSolid class="w-3 h-3 ml-2 text-white dark:text-white" /></Button>

<Dropdown class="dropDown">
  <DropdownItem on:click={handleClick} value="GET">GET</DropdownItem>
  <DropdownItem on:click={handleClick} value="POST">POST</DropdownItem>
  <DropdownItem on:click={handleClick} value="PUT">PUT</DropdownItem>
  <DropdownItem on:click={handleClick} value="DELETE">DELETE</DropdownItem>
  <DropdownItem on:click={handleClick} value="HEAD">HEAD</DropdownItem>
</Dropdown>

<div class="mb-6">
 
  <Input id="default-input" class="inp" placeholder="https://api.challenge.hennge.com/challenges/003" />
 
</div>

<Button color="green" class="sendBtn" type="Submit" pill>Send</Button> 


</div>