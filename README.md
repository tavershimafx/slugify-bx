# slugify-bx
 An angular based slug transformer. Converts plain texts, sentences into a slug based representation for urls
 
 Applications which may want to automatically create a slug of an entity which is a good practice for SEO, would use the pipe to convert the entity name into a slug form to create a url.
 The slug pipe takes care of diacritics, converting them to an english alphabet equivalent.
 
 # Usage
 
 ```HTML
<!-- All the classes and blocks are just for sample case -->
<div class="form-group>
  <input type="text" [(ngModel)]="product.name" />
</div>

<!--the value of the attribute of the slug pipe is the source variable which the text to be obtained is gotten-->
<div class="form-group>
  <input type="text" slugify-bx="product.name" />
</div>
 ```
