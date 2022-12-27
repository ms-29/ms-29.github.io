---
title: AEM Authoring Dialog Cheat Sheet
---

### Text Field Dialog Field

> ```xml
  > <first-name
  >   jcr:primaryType = "nt:unstructured"
  >   sling:resourceType = "granite/ui/components/coral/foundation/form/textfield"
  >   fieldLabel = "First Name"
  >   name = "./firstName"
  >   emptyText = "Enter your First Name"  
  >   required = "{Boolean}true" />
