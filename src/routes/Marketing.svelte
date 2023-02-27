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
      width: 100%;
      background-color: #fff;
      color: #333;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    
    .marketing-content {
      max-width: 800px;
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
  
