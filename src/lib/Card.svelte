<script>
   export let title = 'change me'
</script>

<div class='card'>
   
  <div class='header'>
     <h2> {title} </h2>
  </div>

  <div class='content'>
     <slot>Coming Soon</slot>
  </div>
  
</div>

<style>
   .card {
      border: 1px solid rgb(12, 12, 12);
      width: 500px;
      margin: 3rem auto;
      border-radius: 50px;
      box-shadow: -5px 8px 33px -1px rgba(0,0,0,0.35);
      overflow: hidden;
      position: relative;
   }
   
   .header {
      background: rgb(113, 170, 255);
      color: rgb(0, 0, 3);
      height: 75px;
      margin-bottom: 2.5rem;
      
   }

   h2 {
      --size: 100px;
      line-height: var(--size);
      width: var(--size);
      height: var(--size);
      background: rgb(255, 248, 248);
      border-radius: 100%;
      position: absolute;
      left: 0;
      right: 0;
      margin: auto;
      box-shadow: 0px 11px 50px -23px #00000073;
      top: 10px;
      
   }

   .content {
      padding: 1rem;
      padding-top: 0;
   }
</style>