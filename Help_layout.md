| **Name** | **DiagramObjectLinkOnEvolve** | **Version** | 
| --- | --- | --- |
| **Updated by** | Mathias PFAUWADEL | 1.2 | 

## Patch Notes

* 1.2 : Replace the drillDown by dbClick when clicking on a cross
* 1.1 : Allow to use hash change
* 1.0 : 1st version working

## TBD

* Intermodel

## Description 
Allow you use diagram objectLink on evolve. THis only work if the diagram is in the same model
You can put hask link like that (#/cwtype=index&cwview=index_services_innovants&lang=fr)

On the last version, Replace the drillDown by dbClick when clicking on a cross

## Options 

(to be configure in C:\Casewise\Evolve\Site\bin\webDesigner\custom\Marketplace\libs\cwDiagramObjectLinkOnEvolve\src\DiagramObjectLinkOnEvolve.js)
```
   var DiagramObjectLinkOnEvolveConfig = {
    behaviour : "dbclick" // drill-down or dbclick  
  };
```


### Double Click:
    
If you set behavious with value "dbclick", if you click on the objectLink of a diagram, you will go to the object page of the diagram of the object link

### Drill-Down :

If you set behavious with value "drill-down", if you click on the objectLink of a diagram, you will activate a drilldown to the diagram of the objectLink

## Cohabitation with other specific

Here is a list of all the specific and the function they modified. If you have other personnal specific that use the same function, you will need to merge them in to the main.js
https://docs.google.com/spreadsheets/d/19Mi3LsdQlRuTGFAZiGtLFPGcLhrScWZFTSsm-qQ_BiY/edit#gid=0



