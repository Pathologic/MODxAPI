# MODxAPI
Legacy libs for Evolution CMS 3.0.

To use with FormLister set the model parameter according to documentation:
```
[!FormLister?
&controller=`Login`
&model=`Pathologic\EvolutionCMS\MODxAPI\modUsers`
...
!]

[!FormLister
&controller=`Content`
&model=`Pathologic\EvolutionCMS\MODxAPI\modResource`
&userModel=`Pathologic\EvolutionCMS\MODxAPI\modUsers`
!]
```

To use somewhere else:
```
use Pathologic\EvolutionCMS\MODxAPI\modResource; 
...
$doc = new modResource($modx);
...
```



