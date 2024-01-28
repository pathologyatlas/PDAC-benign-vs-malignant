









```
r language PDAC-benign-vs-malignant, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis pankreatobilier tip duktal adenokarsinom, benign ve malign duktus farkları TR, echo = (language == "TR")
## PDAC-benign-vs-malignant - pankreatobilier tip duktal adenokarsinom, benign ve malign duktus farkları {#sec-PDAC-benign-vs-malignant }
```


```
asis  a pancreatic ductal adenocarcinoma to show differences between benign and malignant ducts EN, echo = (language == "EN")
## PDAC-benign-vs-malignant -  a pancreatic ductal adenocarcinoma to show differences between benign and malignant ducts {#sec-PDAC-benign-vs-malignant }
```






```
r PDAC-benign-vs-malignant screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/thumbnail_PDAC-benign-vs-malignant-HE.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/PDAC-benign-vs-malignant/HE.html",
  file = "./screenshots/thumbnail_PDAC-benign-vs-malignant-HE.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/PDAC-benign-vs-malignant/HE.html](https://images.patolojiatlasi.com/PDAC-benign-vs-malignant/HE.html)





```
asis, echo = (language == "TR")

**pankreatobilier tip duktal adenokarsinom, benign ve malign duktus farkları**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/thumbnail_PDAC-benign-vs-malignant-HE.png){width="25%"}](https://images.patolojiatlasi.com/PDAC-benign-vs-malignant/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/PDAC-benign-vs-malignant/HE.html)
```

```
asis, echo = (language == "EN")

** a pancreatic ductal adenocarcinoma to show differences between benign and malignant ducts**

[![Click for Full Screen WSI](./screenshots/thumbnail_PDAC-benign-vs-malignant-HE.png){width="25%"}](https://images.patolojiatlasi.com/PDAC-benign-vs-malignant/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/PDAC-benign-vs-malignant/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/PDAC-benign-vs-malignant/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/PDAC-benign-vs-malignant/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

pankreatobilier tip duktal adenokarsinom, benign ve malign duktus farkları

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

 a pancreatic ductal adenocarcinoma to show differences between benign and malignant ducts

:::

```









:::::












