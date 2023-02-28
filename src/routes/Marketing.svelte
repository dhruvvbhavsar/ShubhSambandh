<script>
    export let title = '';
  </script>
  
  <section class="marketing">
    <div class="marketing-content">
      <h2>{title}</h2>
      <p>This is some marketing content</p>
    </div>
  </section>
  
  <style>
     .marketing {
    height: 100vh;
    min-width: 100vw;
    background-color: blue;
    color: #333;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border: 1px solid black;
  }
  
    
    .marketing-content {
      height: 100vh;
      width: 100% ;
      text-align: center;
    }
    
    h2 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    
    p {
      font-size: 1.5rem;
    }

  
  </style>
  
