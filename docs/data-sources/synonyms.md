---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "typesense_synonyms Data Source - terraform-provider-typesense"
subcategory: ""
description: |-
  Search terms that should be considered equivalent
---

# typesense_synonyms (Data Source)

Search terms that should be considered equivalent



<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- **id** (String) The ID of this resource.

### Read-Only

- **collection_name** (String) Name of the collection
- **name** (String) Name of the synonyms
- **root** (String) Root for one-way synonym
- **synonyms** (List of Object) Target collection names (see [below for nested schema](#nestedatt--synonyms))

<a id="nestedatt--synonyms"></a>
### Nested Schema for `synonyms`

Read-Only:

