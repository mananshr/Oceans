  
<script>
  let count = 0;
  
    function incrementCount() {
      // event handler code goes here
      count+=1;
    }  
  </script>
  
  <button class="m-6" on:click={incrementCount}>
    Clicked {count}
    {count === 1 ? 'time' : 'times'}
  </button>