~~~xml
<table 
 name="itemRecord" 
 abstract="true" 
 allowPkInsert="true" 
 baseClass="propel.om.BaseObject2" 
 basePeer="propel.om.BasePeer2" 
 heavyIndexing="true" 
 idMethod="none" 
 isI18N="true" 
 i18nTable="language" 
 namespace="\records" 
 package="Records" 
 phpNamingMethod="underscore" 
 phpName="ItemRecord" 
 readOnly="true" 
 reloadOnInsert="true" 
 reloadOnUpdate="true" 
 schema="/Schema/" 
 skipSql="false" 
 treeMode="MaterializedPath">
  <column name="id"/>
  ....
  <vendor type="mysql">
    <parameter name="Engine" value="InnoDB"/>
  </vendor>
</table>  
~~~
