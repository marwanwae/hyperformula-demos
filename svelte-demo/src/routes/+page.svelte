<script>
  import HyperFormula from './Hyperformula.svelte';
  
  const data = [['10', '20', '3.14159265359', '=SUM(A1:C1)']];
  const options = {
    precisionRounding: 10,
    licenseKey: 'gpl-v3'
  };

</script>

<style>
  #main {
    padding: 50px;
  }
</style>

<div id="main">
  <h1>Hyperformula SvelteKit example</h1>
  <HyperFormula {data} {options} />
</div>
