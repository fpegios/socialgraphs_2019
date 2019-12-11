<template>
  <div id="explainer-notebook" class="overflow-hidden">
    <h1>Explainer Notebook</h1>

    <p class="text-right">
      <a class="btn btn-primary" target="_blank" 
      href="https://nbviewer.jupyter.org/github/fpegios/socialgraphs_2019/blob/master/project/Explainer%20Notebook.ipynb" role="button">
        Open Explainer Notebook in a new page</a>
    </p>

    <iframe src="https://nbviewer.jupyter.org/github/fpegios/socialgraphs_2019/blob/master/project/Explainer%20Notebook.ipynb" frameborder="0"></iframe>

  </div>
</template>

<script>
export default {
  name: 'ExplainerNotebook'
}
</script>

<style scoped>
#explainer-notebook {
    height: 100%;
}

iframe {
    width: 100%;
    height: 100%;
}
</style>
