# user:delete
एप्लीकेशन के लिए यूजरस को हटाये

**Usage:**
```
drupal user:delete [options]
ud
```

## Available options
Option | Details
-------|-------------
--user-id | यूजर आईडी हटाया जाना है
--roles | यूजरस के लिए एसोसिएटेड रोल्स को हटाए जाना है

## Examples
* Delete user specifying the id and the user role
```
drupal user:delete  \
  --user-id="2"
  --roles='authenticated'
```
* Delete user specifying its id
```
drupal user:delete  \
  --user-id="3"
```
