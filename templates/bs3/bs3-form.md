---
guid: 909abbda-4cda-4058-b8a6-6fe5b46e0fe2
type: Live
reformat: True
shortenReferences: True
categories: bootstrap 3
scopes: InHtmlLikeFile
parameterOrder: action, method, title, label, submit
action-expression: constant("")
method-expression: constant("POST")
title-expression: constant("Form title")
label-expression: constant("label")
submit-expression: constant("Submit")
---

# bs3-form

Form

```
<form action="$action$" method="$method$" role="form">
    <legend>$title$</legend>
    <div class="form-group">
        <label for="">$label$</label>
        <input type="text" class="form-control" id="" placeholder="Input field">
    </div>
    $END$
    <button type="submit" class="btn btn-primary">$submit$</button>
</form>
```
