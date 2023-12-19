<img src="https://cd.foundation/wp-content/uploads/sites/78/2020/11/tekton-stacked-color-400.png">

<h1>tekton_studies</h1>

Arquivos gerados durante os estudos sobre tekton pipelines

É necessário ter um ambiente kubernetes e o tekton pipelines instalado.

https://tekton.dev/docs/installation/    

Alguns procedimentos de checagem de instalação e permissões:

`oc api-resources --api-group=tekton.dev`

`oc auth can-i create pipeline.tekton.dev`

`oc auth can-i create task`

`oc auth can-i create pipelineresource`

`oc auth can-i create pipelinerun`

`oc get serviceaccount pipeline`
