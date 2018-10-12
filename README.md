Tensorflow with R
======================================================

![](images/tfwr.png)

## Contents

### R Notebook

R document that details the process of creating and deploying the model.  

- Copy published to RStudio Connect: http://colorado.rstudio.com:3939/content/1553/tensorflow-w-r.nb.html

### Exported Keras/Tensorflow model

A folder that contains a Keras Neural Network model developed, and created in the R Notebook.  The resulting files are Tensorflow, not R.  The main file is a [Protocal Buffer](https://developers.google.com/protocol-buffers/?hl=en)

The model was also deployed to RStudio Connect and can be found here: http://colorado.rstudio.com:3939/connect/#/apps/1532/access

### Shiny app

Source code for the Shiny application that uses the deployed Keras model in RStudio Connect as its source.  It uses `shinymaterial` to make it more mobile-friendly.

- Deployed app on RStudio Connect: http://colorado.rstudio.com:3939/churn/overtime/
- Short link to the same app: http://rstd.io/churn

<br/>
<img src = "images/app1.png" width = '400px' align = 'left'>
<img src = "images/app2.png" width = '400px' align = 'right'>

### Presentation 

Companion presentation deck in PDF format. 

<div>
<img src = "images/presentation.png" width = '600' >
</div>